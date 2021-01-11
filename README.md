# link-web-demo
A simple boilerplate for testing the LinkSDK

## Using this boilerplate

### Clone the repository
Clone this repository, and open `index.html` in your code editor of choice.

### Update values
Update values to reflect your own application settings (you can get access to the sandbox by signing up at [dev.leantech.me](https://dev.leantech.me)

`app_token: "[YOUR_APP_TOKEN]"` -> `app_token: "3fbefdbb82de4100a87a97d5fb076387"`

## Getting Values

| Value             | Source                                                                                                                                    |
|-------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| app_token         | Available in your dashboard at dev.leantech.me.                                                                                           |
| app_user_id       | Your own internal identifier.                                                                                                             |
| permissions       | An array of permissions you'd like to request with a data link.                                                                           |
| sandbox           | Link is in sandbox mode or not.                                                                                                           |
| reconnect_id      | Returned by the Data API when an OTP is required - [learn more about generating a `reconnect_id` here](https://docs.leantech.me/testing/) |
| customer_id       | A Customer object created with the [Payments API](https://docs.leantech.me/payment-api)                                                   |
| payment_intent_id | A Payment Intent object created with the  [Payments API](https://docs.leantech.me/payment-api)                                            |
