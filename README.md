This sample is an example of web services calls to Withings Public API from Postman.
The full documentation of the API is [here](https://developer.withings.com/)

# Quickstart

Before you get started, you'll need the following prerequisites:
* [A Withings account](https://account.withings.com/connectionuser/account_create)
* [A Withings developer app](https://account.withings.com/partner/account_login?b=add_oauth2)

To connect to withings' developer API through Oauth 2.0, update the Public_API_postman_collection.json at :
- line 17 : "https://account.withings.com/oauth2_user/authorize2?client_id=CLIENT_ID&redirect_uri=REDIRECT_URI&response_type=code&state=STATE&scope=SCOPE"
with your credentials.

For any further information, don't hesitate to check our full documentation.
