### Basic concepts of Lina(If you don't know Lina-api)

Lina is a groupbuy API module helping you create a product with groupbuy ability. And your customer will pay seperately for this product. Lina handle the email sender and chargeback money if the groupbuy doensn't meet the goal. Lina help you build products with groupbuy ability by super easy way!


### Using API

**◆ Question: Create `group` or `order` fail**

A: You can check the product's endDateTime and group's groupEndDateTime. If time passed, you can't create a group from certain product or create order from certain group.

**◆ Reminder: Must contain registration data when create order**

A: When you create order you must pass the registration data(name, email, ...). Because we need the basic info for each customers. Go more detail [here](https://github.com/yosgo-open-source/yosgo-lina-doc/blob/master/API.md#typeinfo-4).


**◆ Reminder: Product maxQuantity and minQuantity will effect order create**

A: Each product has maxQuantity and minQuantity setting. If the product's maxQuantity is 10 and there is group create from this product. The orders' quantity can't be more than ten.

### Checklist when encounter API error

* [ ] Make sure your account is validated by yosgo.
* [ ] Make sure your api-key is right and same as the api-key in your dashboard.
* [ ] Make sure each params' format is right. e.g unitPrice's format is `number` rather than `string`.
* [ ] If you meet error when createing product or group, you can use [GET] `products` & `groups` to make sure the product or group is created or not.

If you still encounter API error. Please you can find help by

1. Send email support@yosgo.com
2. Go to https://yosgo.com . We have already set the (FB)messenger to discuss.
3. Send issue to this repo.

















