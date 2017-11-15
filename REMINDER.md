### Basic concepts of Lina

Lina is a groupbuy API module helping you create a product with groupbuy ability. And your customer will pay seperately for this product. Lina handle the email sender and chargeback money if the groupbuy doensn't meet the goal. Lina help you build products with groupbuy ability by super easy way!


### Using API

**Question: Create `group` or `order` fail**

A: You can check the product's endDateTime and group's groupEndDateTime. If time passed, you can't create a group from certain product or create order from certain group.

**Reminder: Must contain registration data when create order**

A: When you create order you must pass the registration data(name, email, ...). Because we need the basic info for each customers. Go more detail [here](https://github.com/yosgo-open-source/yosgo-lina-doc/blob/master/API.md#typeinfo-4).


**Reminder: Product requiredQuantity will effect order create**

A: Each product has requiredQuantity setting. If the product's requiredQuantity is 4 and there is group create from this product. The orders' quantity can't be more than four.
















