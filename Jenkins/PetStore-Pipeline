pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                git branch: 'main', url: 'https://github.com/QAInsights/JMeter-Exercises.git'
            }
        }
        stage('Execute JMeter') {
            steps {
            
                bat """
                c:\\Tools\\apache-jmeter-5.4\\bin\\jmeter.bat -n -t "Test Plans\\PetStore-End-to-End-Flow.jmx" -p "Test Plans\\data\\PetStore_LoadTest.properties" -JTOTAL_THREADS=2 -JTEST_DURATION=60 -l MyRun1.jtl
                """
            
            }
        }
        stage('Publish Report') {
            steps {
            
                perfReport filterRegex: '', sourceDataFiles: '**/*.jtl'
            
            }
        }
    }
}
