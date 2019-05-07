# ![LOGO](logo.png) PolicyClient **flow**ground Connector

## Description

A generated **flow**ground connector for the PolicyClient API (version 2018-05-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/resources-policySetDefinitions/2018-05-01/swagger.json<br/>
Generated at: 2019-05-07T17:38:47+03:00

## API Description

To manage and control access to your resources, you can define customized policies and assign them at a scope.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Retrieves built-in policy set definitions.

> This operation retrieves a list of all the built-in policy set definitions.

*Tags:* `PolicySetDefinitions`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the operation.

### Retrieves a built in policy set definition.

> This operation retrieves the built-in policy set definition with the given name.

*Tags:* `PolicySetDefinitions`

#### Input Parameters
* `policySetDefinitionName` - _required_ - The name of the policy set definition to get.
* `api-version` - _required_ - The API version to use for the operation.

### Retrieves all policy set definitions in management group.

> This operation retrieves a list of all the a policy set definition in the given management group.

*Tags:* `PolicySetDefinitions`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the operation.
* `managementGroupId` - _required_ - The ID of the management group.

### Deletes a policy set definition.

> This operation deletes the policy set definition in the given management group with the given name.

*Tags:* `PolicySetDefinitions`

#### Input Parameters
* `policySetDefinitionName` - _required_ - The name of the policy set definition to delete.
* `api-version` - _required_ - The API version to use for the operation.
* `managementGroupId` - _required_ - The ID of the management group.

### Retrieves a policy set definition.

> This operation retrieves the policy set definition in the given management group with the given name.

*Tags:* `PolicySetDefinitions`

#### Input Parameters
* `policySetDefinitionName` - _required_ - The name of the policy set definition to get.
* `api-version` - _required_ - The API version to use for the operation.
* `managementGroupId` - _required_ - The ID of the management group.

### Creates or updates a policy set definition.

> This operation creates or updates a policy set definition in the given management group with the given name.

*Tags:* `PolicySetDefinitions`

#### Input Parameters
* `policySetDefinitionName` - _required_ - The name of the policy set definition to create.
* `api-version` - _required_ - The API version to use for the operation.
* `managementGroupId` - _required_ - The ID of the management group.

### Retrieves the policy set definitions for a subscription.

> This operation retrieves a list of all the policy set definitions in the given subscription.

*Tags:* `PolicySetDefinitions`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the operation.
* `subscriptionId` - _required_ - The ID of the target subscription.

### Deletes a policy set definition.

> This operation deletes the policy set definition in the given subscription with the given name.

*Tags:* `PolicySetDefinitions`

#### Input Parameters
* `policySetDefinitionName` - _required_ - The name of the policy set definition to delete.
* `api-version` - _required_ - The API version to use for the operation.
* `subscriptionId` - _required_ - The ID of the target subscription.

### Retrieves a policy set definition.

> This operation retrieves the policy set definition in the given subscription with the given name.

*Tags:* `PolicySetDefinitions`

#### Input Parameters
* `policySetDefinitionName` - _required_ - The name of the policy set definition to get.
* `api-version` - _required_ - The API version to use for the operation.
* `subscriptionId` - _required_ - The ID of the target subscription.

### Creates or updates a policy set definition.

> This operation creates or updates a policy set definition in the given subscription with the given name.

*Tags:* `PolicySetDefinitions`

#### Input Parameters
* `policySetDefinitionName` - _required_ - The name of the policy set definition to create.
* `api-version` - _required_ - The API version to use for the operation.
* `subscriptionId` - _required_ - The ID of the target subscription.

## License

**flow**ground :- Telekom iPaaS / azure-com-resources-policy-set-definitions-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
