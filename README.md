# ![LOGO](logo.png) Actions **flow**ground Connector

## Description

A generated **flow**ground connector for the Actions API (version 1.0.0).

Generated from: https://sap-iot-noah-live-{appname}.cfapps.{host}<br/>
Generated at: 2020-02-17T10:49:42+00:00

## API Description

Actions service is used to save and retrieve the action information<br/>

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Creates an action
> With this method, you can create an action. You can create different type of actions: Email, In-App, HTTP/Service Integration<br/>

*Tags:* `Actions`

### Updates action using action guid
> With this method, you can update certain attributes associated with action.<br/>

*Tags:* `Actions`

### Retrieves actions
> With this method, you can retrieve all the existing actions.<br/>

*Tags:* `Actions`

### Retrieve an action based on action guid
> With this method, you can retrieve the details of a specified action.<br/>

*Tags:* `Actions`

#### Input Parameters
* `guid` - _required_ - action Id<br/>

### Delete an action based on action guid
> With this method, you can delete an action with specific action ID.<br/>

*Tags:* `Actions`

#### Input Parameters
* `guid` - _required_ - action Id<br/>

### Update an action event
> With this method, you can update status of an event based on action event id<br/>

*Tags:* `Actions`

### Retrieve an action event
> With this method, you can retrieve action events with pending/all status<br/>

*Tags:* `Actions`

#### Input Parameters
* `$filter` - _required_ - Filter condition to be applied; the only valid filters are all and pending,The filter operators supported are =<br/>

## License

**flow**ground :- Telekom iPaaS / actions-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
