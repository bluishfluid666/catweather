# Static Website

The goal of this website is to support the workshop "Building Serverless Applications".

This folder is designed to be cloned locally and then uploaded as is to S3, strictly following the instructions in the workshop guide.,


Throughout the lab you may need to edit a config file. Simpy replace the `null` with your content.

For example inside config.json you would replace

```JavaScript
var G_API_GATEWAY_URL_STR = null;
```

with

```JavaScript

var G_API_GATEWAY_URL_STR = "https://xxxxxxxxxx.execute-api.us-east-1.amazonaws.com/test"
```
according to the lab guide.


Then push that back up to the root of the website.