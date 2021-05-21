# ⚡ Apache JMeter Exercises
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-1EAEDB)]()
[![saythanks](https://img.shields.io/badge/say-thanks-1EAEDB.svg)](https://saythanks.io/to/catch.nkn%40gmail.com)
[![](https://img.shields.io/badge/license-MIT-0a0a0a.svg?style=flat&colorA=1EAEDB)](https://qainsights.com)
[![](https://img.shields.io/badge/%E2%9D%A4-QAInsights-0a0a0a.svg?style=flat&colorA=1EAEDB)](https://qainsights.com)
[![](https://img.shields.io/badge/%E2%9D%A4-YouTube%20Channel-0a0a0a.svg?style=flat&colorA=1EAEDB)](https://www.youtube.com/user/QAInsights?sub_confirmation=1)
[![](https://img.shields.io/badge/donate-paypal-1EAEDB)](https://www.paypal.com/paypalme/NAVEENKUMARN)

![JMeter Exercise](./assets/JMeter-Exercise.png)

These exercises were designed to learn JMeter by doing. This exercise series is a part of **Performance Testing Trilogy 🔺**. 

Looking for LoadRunner Exercises? [Here it is](https://github.com/QAInsights/LoadRunner-Exercises).

> Currently these series under active development.

# ⚠ Important Notes

- 🛑 Please do not inject any load into the below mentioned demo web application. 
- 🆘 If you do not know how to proceed with the exercises, please raise an issue. I will help you out. But before that, please watch all my JMeter tutorials in [YouTube](https://www.youtube.com/playlist?list=PLJ9A48W0kpRIjLkZ32Do9yDZXnnm7_uj_) 📽.

# 🛠 Enviroment Setup

Below exercises were created using the following configurations:

- [Apache JMeter 5.4.1](https://jmeter.apache.org/)
- **Sampler**: HTTP Sampler
- **OS**: Windows 10 Pro 10.0.19041 Build 19041
- CPU 2 Cores, 4 Logical Processors and Intel Core i7-7500U CPU @ 2.70GHz

|   Component   |   Version |
|   ---------   |   ------- |
|   Apache JMeter   |   5.4.1  |
|   JMeter Plugins  |   1.6  |
|   OpenJDK         |   15 |

# 🏑 Exercises

<details>
    <summary>
    00 Record the simple business flow
    </summary>
<br/>
<div markdown="1">

- Start recording
- Launch [Pet Store](https://petstore.octoperf.com/actions/Catalog.action) application
- Click on `Fish`
- Click on the product ID
- Click on `Return to FISH`
- Stop recording
- Add a `View Results Tree` listener
- Run the test plan
- Go thru each sampler response data

</div>
</details><br/>

<details>
    <summary>
    10 Use CSV Data Set Config for the products [Fish, Dogs, etc.]
    </summary>
<br/>
<div markdown="1">

- Launch [Pet Store](https://petstore.octoperf.com/actions/Catalog.action) application
- Click on `Fish`

Use CSV Data Set Config for the products and then Replay.

Hint: `https://petstore.octoperf.com/actions/Catalog.action?viewCategory=&categoryId=<P_PRODUCTS>`

</div>
</details><br/>

<details>
    <summary>
    30 Extract the footer text
    </summary>
<br/>
<div markdown="1">

- Launch [Pet Store](https://petstore.octoperf.com/actions/Catalog.action) application
- Extract the footer text `www.mybatis.org` 

</div>
</details><br/>

<details>
    <summary>
    40 Extract the Title text
    </summary>
<br/>
<div markdown="1">

- Launch [Pet Store](https://petstore.octoperf.com/actions/Catalog.action) application
- Extract the title

Hint: Use `<title></title>` tags in `Boundary Extractor`

</div>
</details><br/>

<details>
    <summary>
    50 Extract the types of products
    </summary>
<br/>
<div markdown="1">

- Launch [Pet Store](https://petstore.octoperf.com/actions/Catalog.action) application
- Extract the types of products and its count

Hint: Use `href="/actions/Catalog.action?viewCategory=&categoryId=(.+?)"`

</div>
</details><br/>

<details>
    <summary>
    60 Validate Cart
    </summary>
<br/>
<div markdown="1">

- Launch [Pet Store](https://petstore.octoperf.com/actions/Catalog.action) application
- Click on the cart icon
- Validate the text `Your cart is empty.` and the cart total `$0.00`

</div>
</details><br/>

<details>
    <summary>
    70 Find all the hyperlinks
    </summary>
<br/>
<div markdown="1">

- Launch [Pet Store](https://petstore.octoperf.com/actions/Catalog.action) application
- Find all the hyperlinks
- Print them in the `Log Viewer`

</div>
</details><br/>

<details>
    <summary>
    80 Update Cart up to $100 worth of items
    </summary>
<br/>
<div markdown="1">

- Launch [Pet Store](https://petstore.octoperf.com/actions/Catalog.action) application
- Add items to the cart upto $100 worth

</div>
</details><br/>

<details>
    <summary>
    90 Register an Account
    </summary>
<br/>
<div markdown="1">

- Launch [Pet Store](https://petstore.octoperf.com/actions/Catalog.action) application
- Click on `Sign in`
- Click on `Register Now`
- Fill the mandatory details
- Click on `Save Account Information`
- Login with the credentials you created
- Logoff


</div>
</details><br/>

<details>
    <summary>
    100 Login, Search, and Logoff
    </summary>
<br/>
<div markdown="1">

- Launch [Pet Store](https://petstore.octoperf.com/actions/Catalog.action) application
- Click on `Sign in`
- Enter the credentials you created in previous exercise
- Perform a search for `ES`
- Click on `Search`
- Click on the product
- Click on `Sign Out`


</div>
</details><br/>

# ⏭ What's next?

* [LoadRunner Exercises](https://github.com/QAInsights/LoadRunner-Exercises)

# 💰 Donate
☕ <a target="_blank" href="https://www.buymeacoffee.com/qainsights">Buy me a tea</a>
