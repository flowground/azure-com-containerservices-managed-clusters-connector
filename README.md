# ![LOGO](logo.png) ContainerServiceClient **flow**ground Connector

## Description

A generated **flow**ground connector for the ContainerServiceClient API (version 2018-08-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/containerservices-managedClusters/2018-08-01-preview/swagger.json<br/>
Generated at: 2019-05-07T17:37:53+03:00

## API Description

The Container Service Client.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Gets a list of compute operations.

*Tags:* `managedClusters`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.

### Gets a list of managed clusters in the specified subscription.

> Gets a list of managed clusters in the specified subscription. The operation returns properties of each managed cluster.

*Tags:* `ManagedClusters`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Lists managed clusters in the specified subscription and resource group.

> Lists managed clusters in the specified subscription and resource group. The operation returns properties of each managed cluster.

*Tags:* `ManagedClusters`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.

### Deletes a managed cluster.

> Deletes the managed cluster with a specified resource group and name.

*Tags:* `ManagedClusters`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `resourceName` - _required_ - The name of the managed cluster resource.

### Gets a managed cluster.

> Gets the details of the managed cluster with a specified resource group and name.

*Tags:* `ManagedClusters`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `resourceName` - _required_ - The name of the managed cluster resource.

### Updates tags on a managed cluster.

> Updates a managed cluster with the specified tags.

*Tags:* `ManagedClusters`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `resourceName` - _required_ - The name of the managed cluster resource.

### Creates or updates a managed cluster.

> Creates or updates a managed cluster with the specified configuration for agents and Kubernetes version.

*Tags:* `ManagedClusters`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `resourceName` - _required_ - The name of the managed cluster resource.

### Gets an access profile of a managed cluster.

> Gets the accessProfile for the specified role name of the managed cluster with a specified resource group and name.

*Tags:* `ManagedClusters`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `resourceName` - _required_ - The name of the managed cluster resource.
* `roleName` - _required_ - The name of the role for managed cluster accessProfile resource.

### Gets cluster admin credential of a managed cluster.

> Gets cluster admin credential of the managed cluster with a specified resource group and name.

*Tags:* `ManagedClusters`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `resourceName` - _required_ - The name of the managed cluster resource.

### Gets cluster user credential of a managed cluster.

> Gets cluster user credential of the managed cluster with a specified resource group and name.

*Tags:* `ManagedClusters`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `resourceName` - _required_ - The name of the managed cluster resource.

### Reset AAD Profile of a managed cluster.

> Update the AAD Profile for a managed cluster.

*Tags:* `ManagedClusters`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `resourceName` - _required_ - The name of the managed cluster resource.

### Reset Service Principal Profile of a managed cluster.

> Update the service principal Profile for a managed cluster.

*Tags:* `ManagedClusters`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `resourceName` - _required_ - The name of the managed cluster resource.

### Gets upgrade profile for a managed cluster.

> Gets the details of the upgrade profile for a managed cluster with a specified resource group and name.

*Tags:* `ManagedClusters`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `resourceName` - _required_ - The name of the managed cluster resource.

## License

**flow**ground :- Telekom iPaaS / azure-com-containerservices-managed-clusters-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
