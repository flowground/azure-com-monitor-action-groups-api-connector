# ![LOGO](logo.png) Azure Action Groups **flow**ground Connector

## Description

A generated **flow**ground connector for the Azure Action Groups API (version 2018-09-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/monitor-actionGroups_API/2018-09-01/swagger.json<br/>
Generated at: 2019-05-07T17:38:24+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Get a list of all action groups in a subscription.

#### Input Parameters
* `subscriptionId` - _required_ - The Azure subscription Id.
* `api-version` - _required_ - Client Api Version.

### Get a list of all action groups in a resource group.

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `subscriptionId` - _required_ - The Azure subscription Id.
* `api-version` - _required_ - Client Api Version.

### Delete an action group.

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `actionGroupName` - _required_ - The name of the action group.
* `subscriptionId` - _required_ - The Azure subscription Id.
* `api-version` - _required_ - Client Api Version.

### Get an action group.

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `actionGroupName` - _required_ - The name of the action group.
* `subscriptionId` - _required_ - The Azure subscription Id.
* `api-version` - _required_ - Client Api Version.

### Updates an existing action group's tags. To update other fields use the CreateOrUpdate method.

#### Input Parameters
* `subscriptionId` - _required_ - The Azure subscription Id.
* `resourceGroupName` - _required_ - The name of the resource group.
* `actionGroupName` - _required_ - The name of the action group.
* `api-version` - _required_ - Client Api Version.

### Create a new action group or update an existing one.

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `actionGroupName` - _required_ - The name of the action group.
* `subscriptionId` - _required_ - The Azure subscription Id.
* `api-version` - _required_ - Client Api Version.

### Enable a receiver in an action group. This changes the receiver's status from Disabled to Enabled. This operation is only supported for Email or SMS receivers.

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `actionGroupName` - _required_ - The name of the action group.
* `subscriptionId` - _required_ - The Azure subscription Id.
* `api-version` - _required_ - Client Api Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-monitor-action-groups-api-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
