# ![LOGO](logo.png) NFL v3 Projections DFSR **flow**ground Connector

## Description

A generated **flow**ground connector for the NFL v3 Projections DFSR API (version 1.0).

Generated from: https://api.apis.guru/v2/specs/fantasydata.net/nfl-v3-projections-dfsr/1.0/swagger.json<br/>
Generated at: 2019-05-07T17:40:36+03:00

## API Description

NFL v3 Projections DFSR

## Authorization

Supported authorization schemes:
- API Key- API Key
## Actions

### DFSR Projected Fantasy Defense Game Stats

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: xml, json.
* `season` - _required_ - 
Year of the season and the season type. If no season type is provided, then the default is regular season.
<br>Examples: <code>2015REG</code>, <code>2015PRE</code>, <code>2015POST</code>.
* `week` - _required_ - 
Week of the season. Valid values are as follows: Preseason 0 to 4, Regular Season 1 to 17, Postseason 1 to 4.
Example: <code>1</code>

### DFSR Projected Player Game Stats

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: xml, json.
* `season` - _required_ - 
Year of the season and the season type. If no season type is provided, then the default is regular season.
<br>Examples: <code>2015REG</code>, <code>2015PRE</code>, <code>2015POST</code>.
* `week` - _required_ - 
Week of the season. Valid values are as follows: Preseason 0 to 4, Regular Season 1 to 17, Postseason 1 to 4.
Example: <code>1</code>

## License

**flow**ground :- Telekom iPaaS / fantasydata-net-nfl-v-3-projections-dfsr-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
