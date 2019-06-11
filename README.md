# ![LOGO](logo.png) SubscriptionsManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the SubscriptionsManagementClient API (version 2015-11-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/azsadmin-AcquiredPlan/2015-11-01/swagger.json<br/>
Generated at: 2019-06-11T18:13:30+03:00

## API Description

The Admin Subscriptions Management Client.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Get a collection of all acquired plans that subscription has access to.

*Tags:* `AcquiredPlans`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription.The subscription ID forms part of the URI for every service call.
* `targetSubscriptionId` - _required_ - The target subscription ID.
* `api-version` - _required_ - Client Api Version.

### Deletes an acquired plan.

*Tags:* `AcquiredPlans`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription.The subscription ID forms part of the URI for every service call.
* `targetSubscriptionId` - _required_ - The target subscription ID.
* `planAcquisitionId` - _required_ - The plan acquisition Identifier
* `api-version` - _required_ - Client Api Version.

### Gets the specified plan acquired by a subscription consuming the offer.

*Tags:* `AcquiredPlans`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription.The subscription ID forms part of the URI for every service call.
* `targetSubscriptionId` - _required_ - The target subscription ID.
* `planAcquisitionId` - _required_ - The plan acquisition Identifier
* `api-version` - _required_ - Client Api Version.

### Creates an acquired plan.

*Tags:* `AcquiredPlans`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription.The subscription ID forms part of the URI for every service call.
* `targetSubscriptionId` - _required_ - The target subscription ID.
* `planAcquisitionId` - _required_ - The plan acquisition Identifier
* `api-version` - _required_ - Client Api Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-azsadmin-acquired-plan-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
