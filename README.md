# Mastercard-Payment-Gateway-Integration
Mastercard integration sample template to use both mobile sdk and web payments


To Test:
	
	1) copy .env.sample to .env
	2) Update with MerchantId and Generated API Password
	3) Composer Install
	4) Run the index.php
	5) Test Web Payments
	6) Follow the instructions 
	7) Test Mobile SDK

The Mobile SDK assists you to develop a mobile application (app) that will accept digital payments via the MasterCard Payment Gateway.

The Mobile SDK is supported on the iOS and Android platforms. Integration guidelines for each platform are available in [Android] / [iOS]

The Mobile SDK uses the Update Session with Payer Data operation to pass card data from the mobile device to the gateway. This operation does not require authentication credentials because the Mobile SDK provides the sessionId in the URL context parameter. Please note that the merchant API password or certificate are secret and should never be inserted within a mobile app.


[Android]: https://github.com/Mastercard-Gateway/gateway-android-sdk
[iOS]: https://github.com/Mastercard-Gateway/gateway-ios-sdk