# kDash
A web dashboard which allows you to view your Kiezelpay sales data via your API key. It's a heavily modified version of the [K·pay merchant API module](https://github.com/KiezelPay/fitbit_kpay_merchant_api).

## How does it work?

👉 Add your kPay API key with the key button in the top right of the page. Find your API key here: https://kiezelpay.com/account/api

👉 Recent sales are paged - click the numbers under the list to look further back.

ℹ️ kDash refreshes every 5 minutes, and again when you come back to the tab.

## Demo

You can try it out here: https://john-reno.github.io/kDash/

If you want to try it without a real API key, you can use the Kiezelpay test API key ```0123456789abcdef0123456789abcdef``` - but please note that it will not display any product information (as the history API doesn't exist for the test API key).

## Usage

Open the HTML file locally, or upload it somewhere to use. The documentation for the Kiezelpay API can be found here: https://kiezelpay.com/api/merchant/documentation

## Note

Please ensure you take adequate care with your API key. Do not enter your API into anything you do not trust, as your sales data may be viewed by others. kDash will not expose your API key, however please take precaution with any other apps or clock faces that ask for your Kiezelpay API key, and ensure you are able to see that your API is not being exposed. 

Your API key is stored in the localstorage of your browser, and you can remove it any time with the Remove key button.

## Finally...

Thank you so much for reading, and let me know if you have any questions or issues. 😊
