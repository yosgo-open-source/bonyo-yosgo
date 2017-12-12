## Brief

Welcome to YOSGO-API. If you come here with first, Please reading this doc and following steps.

**About Yosgo-Lina**

Yosgo-Lina is an API moudle let you create a product of seperately payment feature with a super easy way.

</br>

### STEP.1 Create an account

You can apply yosgo account [here](https://dashboard.yosgo.com/signup).

If you have account already login [here](https://dashboard.yosgo.com/login).

</br>

### STEP.2 Get API key

After create and login your account. Click with `廠商資訊` -> `開發人員區` -> `產生新的API Key`to get your company's API Key.

*Note*
* Keep API key secret. Don't expose it at front-end.
* Your can renew your API key. Remeber repalce API key in your application, if you have renewed your API key.

</br>

### STEP.3 Set your Ecpay account

You can use your own ECpay account. Customer's payment will be in your ECpay account.

Click with `廠商資訊` -> `金流選項`, and then 
* `綠界收款帳戶` -> Choose the option 使用我的綠界帳戶
* `HaskKey`, `HashIV`, `MerchantNo` -> Enter with your own ECpay account information.

</br>

### STEP.4 Read yosgo API

You can go to this [yosgo-api-doc](https://github.com/yosgo-open-source/bonyo-yosgo/blob/master/API.md) to learn more about YOSGO API.

</br>

### STEP.5 Try it

Before you start wrire any code. We highly recommend you can do following
1. Read this [troubleshooting](https://github.com/yosgo-open-source/yosgo-lina-doc/blob/master/Troubleshooting.md). This will help you avoid some mistake when using YOSGO API
2. Play with our [default postman template](https://github.com/yosgo-open-source/yosgo-lina-doc/blob/master/yosgo-lina-default.postman_collection.json).

Defult postman template is an example show how each YOSGO APIs work. The steps are: `brand` -> `product` -> `group` -> `order` -> `payment`. 

This postman template has already mockup each YOSGO APIs structure(e.g headers setting, body json). All you need is import the template to your postman, then enter the YOUR_OWN_API_KEY and relative data.

</br>

### STEP.6 Dashboard

After finish the example you can go to dashboard to view the group, order, payment data.

 Something should know
 
* Dashboard will log out after one hour. You have to login again.
* In productDetail page. There is a button `重新整理`. If you need get the lastest data, you can click this button.

<br />

### Troubleshooting

You can find out some common troubles [here](https://github.com/yosgo-open-source/yosgo-lina-doc/blob/master/Troubleshooting.md).

### More!


1. Need instant helping? Contact us: 
    * support@yosgo.com 
    * https://yosgo.com 
    * [Slack channel](https://join.slack.com/t/yosgo-open-source/shared_invite/enQtMjg1MjYyNDEyNTk2LTJjNzViN2IwZTJhNDZhZDE0Y2ZhNDBiOTYzODk2MWU4NWExMjhhM2FhOWJjZmVkODIwODVmMzc2MDFjYWNjN2M) for developer
2. If you find an problem or bugs. Sending an issue to us directly, we are appreciating!

