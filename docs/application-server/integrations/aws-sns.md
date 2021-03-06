---
description: Receiving LoRaWAN device-data using AWS Simple Notification Service (SNS).
---

# AWS SNS

The [Simple Notification Service (SNS)](https://aws.amazon.com/sns/) integration
publishes all the events to a SNS Topic to which other applications or AWS
services can subscribe for further processing.

## Events

The AWS Simple Notification Service integration exposes all events as
documented by [Event types](events.md).

### Message attributes

The following message attributes are added to each published message:

* `event` - the event type
* `dev_eui` - the device EUI
* `application_id` - the ChirpStack Application Server application ID

