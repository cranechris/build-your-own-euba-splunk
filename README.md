# build-your-own-euba-splunk
Use Splunk's CIM to build your own fully manageable EUBA
## Requirements
Having Splunk configured properly with the Common Information Model installed. Enterprise Security App not required, but can be very useful for alert management. This was put together without Splunk's Enterprise Security being required. Validate that all required indexes and datamodels are created prior to deployment.
### Common Information Model(CIM) Requirements
Ensure you have the app installed on the search head in use and each security data source has the appropriate CIM mappings using TAs and Add-ons.
### DataModel Requirements
Not much acceleration is needed for each of the security domains. A week at most, but it won't be needed for this.
