# React_App_With_Stripe_Payment_Gateway

A simply configured React E-Commerce application with Node.js backend API and integrated with Stripe payment Gateway.

---

# React_App_With_Stripe_Payment_Gateway

[See the Project](https://github.com/IamVaibhavsar/React_App_With_Stripe_Payment_Gateway")
<br>
The front end of the application will look like this. <br>

![frontend](https://github.com/IamVaibhavsar/React_App_With_Stripe_Payment_Gateway/blob/master/images/frontend.png "frontend")

To buy the item click on the  `BUY REACT AT JUST 10$`<br>

The `Stripe` payment dialog box will get open and it will ask you to fill in the details.<br>

![StripeInitial](https://github.com/IamVaibhavsar/React_App_With_Stripe_Payment_Gateway/blob/master/images/StripeInitial.png "StripeInitial")

Fill in the sample details like email ID, name, address, pincode, country etc.<br>

![fillDetails](https://github.com/IamVaibhavsar/React_App_With_Stripe_Payment_Gateway/blob/master/images/fillDetails.png "fillDetails")

After filling the details, click on `payment info` Button. <br>

It will prompt you to fill the card details!<br>

![cardDetails](https://github.com/IamVaibhavsar/React_App_With_Stripe_Payment_Gateway/blob/master/images/cardDetails.png "cardDetails")

Relax, for the testing purpose Stripe provides the sample card which we can use to test our payment gateway!<br>
CARD NO: `4242 4242 4242 4242` <br>
EXPIRY DATE: `12/21` <br>
CVV: `123` <br>

![sampleDetails](https://github.com/IamVaibhavsar/React_App_With_Stripe_Payment_Gateway/blob/master/images/sampleDetails.png "sampleDetails")

after filling the card details, click on `PAY US$ 10.00` Button!<br>
after checking the credentials, the payment will be Succeed! <br>

![paymentSuccess](https://github.com/IamVaibhavsar/React_App_With_Stripe_Payment_Gateway/blob/master/images/paymentSuccess.png "paymentSuccess")

The checkmark will be shown in the `Green Button`, Means payment Sucessful!<br>
Kudos to you!<br>
---
The backend source code of this project is present in `stripebackend/index.js` file.<br>

The frontend source code of this project is present in `stripefrontend/src/App.js` file.<br>

to run this project, First run the `index.js` file from the backend.<br>

and then in another terminal, run the command `npm start` in the `/stripefrontend` directory.<br>

The Web-App will be up and running on the `localhost:3000`

---
### Thank You.
