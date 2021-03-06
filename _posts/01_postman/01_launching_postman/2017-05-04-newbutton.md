---
categories:
  - "postman"
  - "launching_postman"
title: "New button"
page_id: "newbutton"
warning: false

---


You can use the **New** button to initiate requests, collections, environments, monitors, documentation, and mock servers.

[![new_button](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/newButton_homePage_blk.png)](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/newButton_homePage_blk.png)

When you click the **New** button, the **Create New** modal appears.

[![new_button](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/newButton_createNewModal_blk.png)](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/newButton_createNewModal_blk.png)

In **BUILDING BLOCKS**, create a new request, collection, or environment.

In **ADVANCED**, create a new monitor, documentation, and a mock server.

You can select ‘Use a Template’ for templates that help you:
* Check links 

* Track Github issues

* Verify non-MFA access to AWS accounts

* Monitor status of URLS

* Check DNS records

* Use Postman Echos to test your REST client and make sample API calls

Select 'Show this window on launch' if you want to display the **Create New** modal each time you open Postman.

**Note**: You can directly create a new feature when you click the down arrow at the right side of the **New** button.

[![new_button](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/newButton_menu_blk.png)](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/newButton_menu_blk.png)

## BUILDING BLOCKS
### Creating requests
You can create any kind of [HTTP request.](/docs/postman/sending_api_requests/requests)

1. To create a request, click ‘Request’ in the **New** button drop down menu and enter a title and description. 
2. Select a collection and save the request in it. 

You can either create a new collection or select an existing one. After you save the request, you can add the URL, method, headers, and body to the request in the builder.

[![new_button](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/newButton_request_blk.png)](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/newButton_request_blk.png)

### Creating collections
A collection is a group of individual requests that you can organize into folders. 

1. To create a collection, click ‘Collection’ in the **New** button drop down menu and enter a name and description for it. 
2. After [creating the collection ](/docs/postman/collections/creating_collections), you can [save requests to this collection](/docs/postman/collections/creating_collections) and add folders for [better organization.](/docs/postman/collections/managing_collections)

[![new_button](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/newButton_collection_blk.png)](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/newButton_collection_blk.png)

### Creating environments
While working with APIs, you often need different setups, such as your local machine, the development server, or the production API. [Environments](/docs/postman/environments_and_globals/manage_environments) let you customize requests using variables. 

1. To create an environment, click ‘Environment’ in the **New**  button drop down menu and enter a name for it. 
2. Add the variables you want to save as key-value pairs.

[![new_button](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/newButton_environment_blk.png)](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/newButton_environment_blk.png)

## ADVANCED
### Creating monitors
A [monitor](/docs/postman/monitors/intro_monitors) runs a collection periodically to check its performance and response. You can [set a monitor](/docs/postman/monitors/setting_up_monitor) to run as frequently as every 5 minutes. 

1. To create a monitor, click ‘Monitor’ in the **New** button drop down menu and enter the URLs you want to monitor, and indicate the response time and the response code. You can also select an existing collection to monitor all those requests. 
2. Click ‘Next’ to enter the name of the monitor, how often you want the monitor to run, and the region you want to monitor.

Postman makes a collection of the URLs and adds a script that checks the response time and response code for each URL.

You receive notifications when either the response code doesn’t match or the response time falls below the expected values. You can also add the method, headers, and body to the individual URLs in the request builder, as well as add custom test scripts.

[![new_button](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/newButton_monitor_blk.png)](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/newButton_monitor_blk.png)

### Creating documentation
You can create [public or private documentation](/docs/postman/api_documentation/intro_to_api_documentation) and share it in a web page. Postman generates and hosts browser-based documentation for your collections automatically in real-time. 

1. To create documentation, click ‘Documentation’ in the **New** button drop down menu and enter the request URLs with the methods you want to document. 
2. Click ‘Next’ to enter the name for the APIs and a general description for your API. 

Postman creates a collection and generates documentation that you and your team can [ view.](/docs/postman/api_documentation/viewing_documentation)

[![new_button](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/newButton_documentation_blk.png)](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/newButton_documentation_blk.png)

### Creating mock servers
A [mock server  ](/docs/postman/mock_servers/setting_up_mock)simulates each endpoint in a Postman Collection. You can mock a request and response in Postman before you send the actual request or set up a single endpoint to return the response. 

1. To create a mock server, click ‘Mock Server’ in the **New** button drop down menu and enter the request endpoint and the expected response. 
2. Then click ‘Next’ to enter the name of your APIs. You can indicate if you want this mock server to be private.

Postman creates a collection and adds [examples](/docs/postman/mock_servers/mocking_with_examples) for individual requests. Postman also provides a mock URL you can share with the public, such as with front-end developers. They can send a request to this URL, followed by an endpoint, to get the corresponding response.

[![new_button](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/newButton_mockServer_blk.png)](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/newButton_mockServer_blk.png)






