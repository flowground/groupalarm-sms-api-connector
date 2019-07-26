# ![LOGO](logo.png) groupalarm SMS API **flow**ground Connector

## Description

A generated **flow**ground connector for the groupalarm SMS API API (version 1.15.0).

Generated from: https://app.groupalarm.com/api/v1/sms<br/>
Generated at: 2019-07-26T13:59:35+03:00

## API Description

The sms service implements all sms functions for GroupAlarm<br/>
<br/>
# Authentication<br/>
<br/>
<!-- ReDoc-Inject: <security-definitions> --><br/>

## Authorization

Supported authorization schemes:
- API Key
- API Key

## Actions

### ListConfigurations
> Returns all sms-alarming configurations<br/>

*Tags:* `alarming`

#### Input Parameters
* `organization_id` - _required_ - requesting organization<br/>

### UpdateConfiguration
> Updates an existing sms-alarming configuration<br/>

*Tags:* `alarming`

### CreateConfiguration
> Creates a new sms-alarming configuration<br/>

*Tags:* `alarming`

### DeleteConfiguration
> Deletes an existing sms-alarming configuration<br/>

*Tags:* `alarming`

#### Input Parameters
* `configurationID` - _required_ - ID of an existing sms-alarming configuration<br/>

### GetDisabledOrganization
> Returns whether the given organization has disabled this way of alarming or not<br/>

*Tags:* `organizations`

#### Input Parameters
* `organization_id` - _required_ - requesting organization<br/>

### SetDisabledOrganization
> Sets whether the given organization has this way of alarming disabled or not<br/>

*Tags:* `organizations`

#### Input Parameters
* `organization_id` - _required_ - requesting organization<br/>

### List
> Returns all gsm numbers for queried owner<br/>

*Tags:* `gsm`

#### Input Parameters
* `owner_id` - _required_ - requested owner by using his user ID<br/>
* `organization_id` - _optional_ - requesting organization, not required if user accesses his own resources<br/>

### Update
> Updates an existing gsm configuration<br/>

*Tags:* `gsm`

#### Input Parameters
* `organization_id` - _optional_ - requesting organization, not required if user accesses his own resources<br/>

### Create
> Create a gsm configuration for specific user<br/>

*Tags:* `gsm`

#### Input Parameters
* `organization_id` - _optional_ - requesting organization, not required if user accesses his own resources<br/>

### Delete
> Delete an existing gsm configuration<br/>

*Tags:* `gsm`

#### Input Parameters
* `mobileID` - _required_ - ID of an existing mobile configuration<br/>
* `organization_id` - _optional_ - requesting organization, not required if user accesses his own resources<br/>

### List
> Returns an gsm number configuration<br/>

*Tags:* `gsm`

#### Input Parameters
* `mobileID` - _required_ - ID of an gsm configuration<br/>
* `organization_id` - _optional_ - requesting organization, not required if user accesses his own resources<br/>

## License

**flow**ground :- Telekom iPaaS / groupalarm-sms-api-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
