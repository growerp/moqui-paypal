## Mantle Authorize.NET Integration

[![license](http://img.shields.io/badge/license-CC0%201.0%20Universal-blue.svg)](https://github.com/growerp/paypal-moqui/blob/master/LICENSE.md)

Moqui component for Paypal that tie into Mantle payment processing.

To add this component to Moqui the easiest approach is to use the Gradle get component task:

git clone https://github.com/growerp/moqui-paypal.git runtime/component/paypal

To use simply:

1. load the demo configuration data in data/PaypalDemoData.xml or create your own configuration and load it; if you use the demo data, add the login and tranKey credentials
2. configure the store payment gateway with a ProductStorePaymentGateway record (see the demo data file for examples)
3. test the gateway with some test orders/payments
4. start receiving money...

