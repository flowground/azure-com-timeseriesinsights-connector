# ![LOGO](logo.png) TimeSeriesInsightsClient **flow**ground Connector

## Description

A generated **flow**ground connector for the TimeSeriesInsightsClient API (version 2018-08-15-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/timeseriesinsights/2018-08-15-preview/swagger.json<br/>
Generated at: 2019-05-07T17:39:20+03:00

## API Description

Time Series Insights client

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all of the available Time Series Insights related operations.

*Tags:* `Operations`

#### Input Parameters
* `api-version` - _required_ - Version of the API to be used with the client request.

### Lists all the available environments within a subscription, irrespective of the resource groups.

*Tags:* `Environments`

#### Input Parameters
* `subscriptionId` - _required_ - Azure Subscription ID.
* `api-version` - _required_ - Version of the API to be used with the client request.

### Lists all the available environments associated with the subscription and within the specified resource group.

*Tags:* `Environments`

#### Input Parameters
* `subscriptionId` - _required_ - Azure Subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `api-version` - _required_ - Version of the API to be used with the client request.

### Deletes the environment with the specified name in the specified subscription and resource group.

*Tags:* `Environments`

#### Input Parameters
* `subscriptionId` - _required_ - Azure Subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `environmentName` - _required_ - The name of the Time Series Insights environment associated with the specified resource group.
* `api-version` - _required_ - Version of the API to be used with the client request.

### Gets the environment with the specified name in the specified subscription and resource group.

*Tags:* `Environments`

#### Input Parameters
* `subscriptionId` - _required_ - Azure Subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `environmentName` - _required_ - The name of the Time Series Insights environment associated with the specified resource group.
* `$expand` - _optional_ - Setting $expand=status will include the status of the internal services of the environment in the Time Series Insights service.
* `api-version` - _required_ - Version of the API to be used with the client request.

### Updates the environment with the specified name in the specified subscription and resource group.

*Tags:* `Environments`

#### Input Parameters
* `subscriptionId` - _required_ - Azure Subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `environmentName` - _required_ - The name of the Time Series Insights environment associated with the specified resource group.
* `api-version` - _required_ - Version of the API to be used with the client request.

### Create or update an environment in the specified subscription and resource group.

*Tags:* `Environments`

#### Input Parameters
* `subscriptionId` - _required_ - Azure Subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `environmentName` - _required_ - Name of the environment
* `api-version` - _required_ - Version of the API to be used with the client request.

### Lists all the available access policies associated with the environment.

*Tags:* `AccessPolicies`

#### Input Parameters
* `subscriptionId` - _required_ - Azure Subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `environmentName` - _required_ - The name of the Time Series Insights environment associated with the specified resource group.
* `api-version` - _required_ - Version of the API to be used with the client request.

### Deletes the access policy with the specified name in the specified subscription, resource group, and environment

*Tags:* `AccessPolicies`

#### Input Parameters
* `subscriptionId` - _required_ - Azure Subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `environmentName` - _required_ - The name of the Time Series Insights environment associated with the specified resource group.
* `accessPolicyName` - _required_ - The name of the Time Series Insights access policy associated with the specified environment.
* `api-version` - _required_ - Version of the API to be used with the client request.

### Gets the access policy with the specified name in the specified environment.

*Tags:* `AccessPolicies`

#### Input Parameters
* `subscriptionId` - _required_ - Azure Subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `environmentName` - _required_ - The name of the Time Series Insights environment associated with the specified resource group.
* `accessPolicyName` - _required_ - The name of the Time Series Insights access policy associated with the specified environment.
* `api-version` - _required_ - Version of the API to be used with the client request.

### Updates the access policy with the specified name in the specified subscription, resource group, and environment.

*Tags:* `AccessPolicies`

#### Input Parameters
* `subscriptionId` - _required_ - Azure Subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `environmentName` - _required_ - The name of the Time Series Insights environment associated with the specified resource group.
* `accessPolicyName` - _required_ - The name of the Time Series Insights access policy associated with the specified environment.
* `api-version` - _required_ - Version of the API to be used with the client request.

### Create or update an access policy in the specified environment.

*Tags:* `AccessPolicies`

#### Input Parameters
* `subscriptionId` - _required_ - Azure Subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `environmentName` - _required_ - The name of the Time Series Insights environment associated with the specified resource group.
* `accessPolicyName` - _required_ - Name of the access policy.
* `api-version` - _required_ - Version of the API to be used with the client request.

### Lists all the available event sources associated with the subscription and within the specified resource group and environment.

*Tags:* `EventSources`

#### Input Parameters
* `subscriptionId` - _required_ - Azure Subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `environmentName` - _required_ - The name of the Time Series Insights environment associated with the specified resource group.
* `api-version` - _required_ - Version of the API to be used with the client request.

### Deletes the event source with the specified name in the specified subscription, resource group, and environment

*Tags:* `EventSources`

#### Input Parameters
* `subscriptionId` - _required_ - Azure Subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `environmentName` - _required_ - The name of the Time Series Insights environment associated with the specified resource group.
* `eventSourceName` - _required_ - The name of the Time Series Insights event source associated with the specified environment.
* `api-version` - _required_ - Version of the API to be used with the client request.

### Gets the event source with the specified name in the specified environment.

*Tags:* `EventSources`

#### Input Parameters
* `subscriptionId` - _required_ - Azure Subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `environmentName` - _required_ - The name of the Time Series Insights environment associated with the specified resource group.
* `eventSourceName` - _required_ - The name of the Time Series Insights event source associated with the specified environment.
* `api-version` - _required_ - Version of the API to be used with the client request.

### Updates the event source with the specified name in the specified subscription, resource group, and environment.

*Tags:* `EventSources`

#### Input Parameters
* `subscriptionId` - _required_ - Azure Subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `environmentName` - _required_ - The name of the Time Series Insights environment associated with the specified resource group.
* `eventSourceName` - _required_ - The name of the Time Series Insights event source associated with the specified environment.
* `api-version` - _required_ - Version of the API to be used with the client request.

### Create or update an event source under the specified environment.

*Tags:* `EventSources`

#### Input Parameters
* `subscriptionId` - _required_ - Azure Subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `environmentName` - _required_ - The name of the Time Series Insights environment associated with the specified resource group.
* `eventSourceName` - _required_ - Name of the event source.
* `api-version` - _required_ - Version of the API to be used with the client request.

### Lists all the available reference data sets associated with the subscription and within the specified resource group and environment.

*Tags:* `ReferenceDataSets`

#### Input Parameters
* `subscriptionId` - _required_ - Azure Subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `environmentName` - _required_ - The name of the Time Series Insights environment associated with the specified resource group.
* `api-version` - _required_ - Version of the API to be used with the client request.

### Deletes the reference data set with the specified name in the specified subscription, resource group, and environment

*Tags:* `ReferenceDataSets`

#### Input Parameters
* `subscriptionId` - _required_ - Azure Subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `environmentName` - _required_ - The name of the Time Series Insights environment associated with the specified resource group.
* `referenceDataSetName` - _required_ - The name of the Time Series Insights reference data set associated with the specified environment.
* `api-version` - _required_ - Version of the API to be used with the client request.

### Gets the reference data set with the specified name in the specified environment.

*Tags:* `ReferenceDataSets`

#### Input Parameters
* `subscriptionId` - _required_ - Azure Subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `environmentName` - _required_ - The name of the Time Series Insights environment associated with the specified resource group.
* `referenceDataSetName` - _required_ - The name of the Time Series Insights reference data set associated with the specified environment.
* `api-version` - _required_ - Version of the API to be used with the client request.

### Updates the reference data set with the specified name in the specified subscription, resource group, and environment.

*Tags:* `ReferenceDataSets`

#### Input Parameters
* `subscriptionId` - _required_ - Azure Subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `environmentName` - _required_ - The name of the Time Series Insights environment associated with the specified resource group.
* `referenceDataSetName` - _required_ - The name of the Time Series Insights reference data set associated with the specified environment.
* `api-version` - _required_ - Version of the API to be used with the client request.

### Create or update a reference data set in the specified environment.

*Tags:* `ReferenceDataSets`

#### Input Parameters
* `subscriptionId` - _required_ - Azure Subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `environmentName` - _required_ - The name of the Time Series Insights environment associated with the specified resource group.
* `referenceDataSetName` - _required_ - Name of the reference data set.
* `api-version` - _required_ - Version of the API to be used with the client request.

## License

**flow**ground :- Telekom iPaaS / azure-com-timeseriesinsights-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
