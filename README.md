# Splunk-Suricata-Dashboard
This is a dashboard designed to provide Suricata alert information to analysts in the most readable format

## Requirements & Recommendations:
### Requirements:
- Splunk Common Information Model (CIM)
  - https://splunkbase.splunk.com/app/1621
### Recommendations: 
- Splunk App For Lookup File Editing:
  - https://splunkbase.splunk.com/app/1724

## Notes:
- The Splunk CIM may be needed for proper operation.
- For proper operation, the index for your suricata logs must be specified in each panel.
- A lookup file MUST be created under the name "Known_Scanners.csv" with the field "scannerip". It can be used to filter out all known scanners.

## App Links:
### Splunk App For Lookup File Editing:
- https://splunkbase.splunk.com/app/1724
### Splunk Common Information Model (CIM):
- https://splunkbase.splunk.com/app/1621
