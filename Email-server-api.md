### Brief 

YOSGO support you to send email easily without hosting an email server. All you need is design your own email content. The email will be send by `support@yosgo.com`.

### CURL Example

All params are required.

| params | type | description |
| --- | --- | --- |
| receiver | string | Someone will reveive this mail |
| subject | string | Subject of this email |
| message | string | Content of this email |
| email_private_key | string | If you want to use email server api, contact support@yosgo.com |



```
curl -X POST https://yosgo-api-policer-dev.herokuapp.com/yosgo-model/email/send  \
-d '{ 
  "receiver": "kcin1993@gmail.com", 
  "subject": "Cool yosgo email api", 
  "message": "Hi you are a cool guy", 
  "email_private_key": "YOUR_KEY" 
  }' \
-H "Content-Type: application/json" 
```
