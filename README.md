# Suricata Alert Dashboard For Splunk
This is a dashboard designed to provide Suricata alert information to analysts in the most readable format

## Requirements & Recommendations:
### Requirements:
- **Splunk Common Information Model (CIM)**
  - https://splunkbase.splunk.com/app/1621
- **Known_Scanners.csv** Lookup File
- **Suricata_Suite_Datamodel.json** must be configured and installed (Name: Suricata_Suite)
- **Suricata Alert Overview___.xml** is the source code for the dashboard
### Recommendations: 
- **Splunk App For Lookup File Editing**
  - https://splunkbase.splunk.com/app/1724

## Current Version Notes:
- Version 3 enables the dashboard to operate off the datamodel
