# Splunk-Suricata-Dashboard
This is a dashboard designed to provide Suricata alert information to analysts in the most readable format

## Notes:
- The Splunk CIM may be needed for proper operation
- For proper operation, the index for your suricata logs must be specified in each panel
- A lookup file must be created under the name Known_Scanners.csv with the field scannerip must be used to filter out all known scanners
