# Suricata Alert Dashboard For Splunk
This is a dashboard designed to provide Suricata alert information to analysts in the most readable format

## Requirements & Recommendations:
### Requirements:
- **Splunk Common Information Model (CIM)**
  - https://splunkbase.splunk.com/app/1621
- **Known_Scanners.csv** lookup file containing known scanners
- **Suricata_Suite_Datamodel.json** must be configured and installed (Datamodel ID: Suricata_Suite)
- **Suricata Alert Overview___.xml** is the source code for the dashboard
- **Disabled_Suricata_Rules.csv** lookup file containing all the SIDs you do not wish to have within the datamodel
### Recommendations: 
- **Splunk App For Lookup File Editing**
  - https://splunkbase.splunk.com/app/1724

## Current Version Notes:
- Version 4 integrated the use of the _Disabled_Suricata_Rules.csv_ file

## Other Notes:
- Any modifications to a CSV file will not be automatically applied to the datamodel when in accelerated mode. To integrate changes, you must rebuild the datamodels
