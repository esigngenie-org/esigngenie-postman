# eSign Genie Postman Collections
Welcome to the Postman Collections Quickstart Guide! If you're looking for a quick and easy way to get started with the eSign Genie API with no additional code, this is the place for you. [Postman](https://www.getpostman.com/product/api-client) is a great tool that allows users explore API functionality by manually sending API requests and receiving responses. We have created a collection of pre-populated HTTP requests that can be sent to the eSign Genie API. This quickstart is a step-by-step guide that will get you up and running with Postman and the eSign Genie’s Postman [collection](https://learning.postman.com/docs/postman/collections/intro-to-collections/) to enable you for ad-hoc exploration and testing.

If you are looking for a more in-depth guide and reference for the eSign Genie API, please refer to the [eSign Genie API documentation](https://developer.esigngenie.com/api#overview).

![eSign Genie-postman-overview](/images/esign-genie-postman-overview.png)

## Getting started
Follow these steps to quickly get started with the [eSign Genie API](https://developer.esigngenie.com/api):

1. [Contact Us](mailto:api@esigngenie.com) at eSign Genie to get a set of API keys that are required for interacting with the API. [Here](https://developer.esigngenie.com/docs/auth) is some documentation explaining what these keys are.
2. Download and install the [Postman app](https://www.getpostman.com/downloads/)
3. Install the eSign Genie Postman Collection. Click the "Run in Postman" button below to install the eSign Genie collection!
  
    [![Run in Postman](https://run.pstmn.io/button.svg)](https://god.postman.co/run-collection/6b1010ff385a9991053c?action=collection%2Fimport)

    Note: you can also download this collection and import it manually by downloading [the collection in this repository](/eSign%20Genie%20API%20Endpoints%20Collection.json)

4. Once both the collection and the environment variables are imported into Postman, see the [Configuration](https://github.com/esigngenie-org/esign-genie-postman#configuration) section on how to correctly configure API keys with the collection.

### Configuration
The eSign Genie Postman collection uses [Postman environment variables](https://learning.getpostman.com/docs/postman/environments_and_globals/intro_to_environments_and_globals/) to simplify each API request. More information on managing Postman environments can be found at [Setting up an environment with variables](https://learning.getpostman.com/docs/postman/environments_and_globals/manage_environments/).

![eSign Genie-postman-configuration](/images/esign-genie-postman-config.png)

1. Select the `Sandbox Public` environment in the top right corner
2. Click the `eye` icon to open the environment settings
3. Copy in your [eSign Genie API keys from your eSign Genie Dashboard](https://www.esigngenie.com/esign/consumer/consumerdetails), into a new `access_token` field
4. Save your changes and start making eSign Genie API requests!

## Collection endpoints
The following collection is a fully-featured set of pre-filled requests that allow you to test the [eSign Genie API](https://eSign Genie.com/docs), and visualize the responses in a friendly format.

* **Example Request**
  * **Create Example Request** - Creates a `example_request` for the default request.

## Useful Tools
[Webhook Tester](https://webhook.site/) is a great tool for receiving webhook calls. Generate a webhook url on this site and use that url for any Postman requests that require you to specify a webhook url. You can go on Webhook Tester to see a list of all requests being made to that url.
