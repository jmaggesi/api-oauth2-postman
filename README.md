This sample is an example of web services calls to Withings Public API from Postman.
The full documentation of the API is [here](https://developer.withings.com/)

# Quickstart

Before you get started, you'll need the following prerequisites:
* [A Withings account](https://account.withings.com/connectionuser/account_create)
* [A Withings developer app](https://account.withings.com/partner/account_login?b=add_oauth2)

To connect to withings' developer API through Oauth 2.0, modify OAuth 2.0 [url](https://developer.withings.com/oauth2/#tag/OAuth-2.0) in the Postman sample

Then replace named place holder with :
* Client_id and Client_secret you got from your developer account
* Access token
* Refresh token [url](https://developer.withings.com/oauth2/#tag/OAuth-2.0%2Fpaths%2Fhttps%3A~1~1account.withings.com~1oauth2~1token%20%5Bgrant_type%3Drefresh_token...%5D%2Fpost) in the POST call
* Paths

For any further information, don't hesitate to check our full documentation.
