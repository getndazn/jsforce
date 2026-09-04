![No longer maintained](https://img.shields.io/badge/Maintenance-OFF-red.svg)

### ⚠️ Deprecated

This repository is no longer actively maintained and has been archived by the [Security team](https://teams.microsoft.com/l/channel/19%3A38b4a7fa05ac4ec782143b767304c53c%40thread.skype/General?groupId=99480e15-059f-4bea-b7cc-4912903bd6f6&tenantId=30459df5-1e53-4d8b-a162-0ad2348546f1).
The repository is retained for historical and reference purposes and is read-only while archived.
If this repository is required in the future, it can be unarchived. Please raise a request with the [CodX team](https://teams.microsoft.com/l/channel/19%3Aa654db0c76f84164aebe0cccf297e6de%40thread.skype/CoDX%20Support?groupId=602f2603-465a-49fa-be9e-abfe0b05b551&tenantId=30459df5-1e53-4d8b-a162-0ad2348546f1) to have it unarchived.

# jsforce 

Salesforce API Library for JavaScript applications (both on web browser and Node.js)

[![CircleCI](https://circleci.com/gh/jsforce/jsforce.svg?style=svg)](https://circleci.com/gh/jsforce/jsforce)

## Overview

JSforce (f.k.a. Node-Salesforce) is an isomorphic JavaScript Library utilizing Salesforce's API: It works both in the browser and with Node.js.

It capsulates the access to various APIs provided by Salesforce in asynchronous JavaScript function calls.

It also has command line interface (CLI) which gives interactive console (REPL), so you can learn the usage without hassle.

Supported Salesforce APIs are the following:

- REST API (SOQL, SOSL, describe, etc.)
- Apex REST
- Analytics API
- Bulk API
- Chatter API
- Metadata API
- SOAP API
- Streaming API
- Tooling API

## Documentation

See documentation in http://jsforce.github.io/ .

## Releases

See [Releases](https://github.com/jsforce/jsforce/releases).

## License

See [license](LICENSE) (MIT License).

## Authors

- Shinichi Tomita <shinichi.tomita@gmail.com>


## Notes

If you have any questions first file it on [issues](https://github.com/jsforce/jsforce/issues) before contacting authors via e-mail.

## Tests

In order to run tests you will need a [Salesforce Developer Org](https://developer.salesforce.com/signup)

You will also need to install the JsforceTestSuite package, which can be done by running:

    SF_USERNAME=myusername SF_PASSWORD=password+securityToken ./test/bin/org-setup

You may need to run this more then once if you encounter timeouts or dropped connections/

Finally, to run the tests simply do:

    SF_USERNAME=myusername SF_PASSWORD=password+securityToken npm run test:node

    SF_USERNAME=myusername SF_PASSWORD=password+securityToken npm run test:browser

## Contributions

Your contributions are welcome: both by reporting issues on [GitHub issues](https://github.com/jsforce/jsforce/issues) or pull-requesting patches.

If you want to implement any additional features, to be added to JSforce to our master branch, which may or may not be merged please first check current [opening issues](https://github.com/jsforce/jsforce/issues?q=is%3Aopen) with milestones and confirm whether the feature is on road map or not.

If your feature implementation is brand-new or fixing unsupposed bugs in the library's test cases, please include addtional test codes in the `test/` directory.




