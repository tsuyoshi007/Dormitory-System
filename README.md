# Dormitory-System

 **Note** : The loop of requesting cards : 1mn

## Getting Started

### Prerequisites

Setup Instructions

    1. Go to the Google Developers Console
    2. Select your project or create a new one (and then select it)
    3. Enable the Drive API for your project

    * In the sidebar on the left, expand APIs & auth > APIs
    * Search for "drive"
    * Click on "Drive API"
    * click the blue "Enable API" button

    4. Create a service account for your project

    * In the sidebar on the left, expand APIs & auth > Credentials
    * Click blue "Add credentials" button
    * Select the "Service account" option
    * Select "Furnish a new private key" checkbox
    * Select the "JSON" key type option
    * Click blue "Create" button
    * your JSON key file is generated and downloaded to your machine (it is the only copy!)
    * note your service account's email address (also available in the JSON key file)

    5. Share the doc (or docs) with your service account using the email noted above


**Note**: SHEET_ID,CRED_PATH and SLACK_TOKEN will be passed into the function as [String][1]
          PORT will be passed into the function as Integer

### Inside .env file

* CRED_PATH=[string][1]
* SHEET_ID=[string][1]
* PORT=Integer
* SLACK_TOKEN=[string][1]


You also need :
  * @slack/web-api: "5.0.1
  * cron: 1.7.1
  * dotenv: 8.0.0
  * express: 4.17.1
  * google-spreadsheet-to-json: 1.0.0
  * nedb: 1.8.0

### Installing

```
npm install
```

## Running the tests

For Example:

```bash
node main.js
```

### And coding style tests

```bash
semistandard --fix
```
[![js-semistandard-style](https://img.shields.io/badge/code%20style-semistandard-brightgreen.svg?style=flat-square)](https://github.com/Flet/semistandard)

## Built With

* [NodeJS](https://nodejs.org/en/)

## Authors

* **Hun Vikran** 

[1]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String