<div align="center">

# Telnyx Node Getting Started

![Telnyx](logo-dark.png)

Sample application demonstrating Node SDK Basics

</div>

## Documentation & Tutorial

The full documentation and tutorial is available on [developers.telnyx.com](https://developers.telnyx.com/docs/v2/development/dev-env-setup?lang=dotnet&utm_source=referral&utm_medium=github_referral&utm_campaign=cross-site-link)

## Pre-Reqs

You will need to set up:

* [Telnyx Account](https://telnyx.com/sign-up?utm_source=referral&utm_medium=github_referral&utm_campaign=cross-site-link)
* [Telnyx Phone Number](https://portal.telnyx.com/#/app/numbers/my-numbers?utm_source=referral&utm_medium=github_referral&utm_campaign=cross-site-link) enabled with:
  * [Telnyx Call Control Application](https://portal.telnyx.com/#/app/call-control/applications?utm_source=referral&utm_medium=github_referral&utm_campaign=cross-site-link)
  * [Telnyx Outbound Voice Profile](https://portal.telnyx.com/#/app/outbound-profiles?utm_source=referral&utm_medium=github_referral&utm_campaign=cross-site-link)
* Ability to receive webhooks (with something like [ngrok](https://developers.telnyx.com/docs/v2/development/ngrok?utm_source=referral&utm_medium=github_referral&utm_campaign=cross-site-link))
* [Node & NPM](https://developers.telnyx.com/docs/v2/development/dev-env-setup?lang=node&utm_source=referral&utm_medium=github_referral&utm_campaign=cross-site-link) installed

## What you can do

| Example                                        | Description                                                                                                         |
|:-----------------------------------------------|:--------------------------------------------------------------------------------------------------------------------|
| [Express Messaging](express-messaging)         | Example working with inbound MMS & SMS messages, downloading media from inbound MMS, and uploading media to AWS S3. |
| [Webinar Demo](webinar-demo) | Example code from the intro to [Node Webinar](https://telnyx.com/resources/node-sdk-recap) |

### Install

Run the following commands to get started

```
$ git clone https://github.com/d-telnyx/demo-node-telnyx.git
```
