# build-your-own-euba-splunk
Use Splunk's CIM to build your own fully manageable EUBA
## Requirements
Having Splunk configured properly with the Common Information Model installed. Enterprise Security App not required, but can be very useful for alert management. This was put together without Splunk's Enterprise Security being required. Validate that all required indexes and datamodels are created prior to deployment.
### Common Information Model(CIM) Requirements
Ensure you have the app installed on the search head in use and each security data source has the appropriate CIM mappings using TAs and Add-ons.
### DataModel Requirements
Not much acceleration is needed for each of the security domains. A week at most, but it won't be needed for this.
## Quick Startup Mode
Run each of the saved risk building searches over the past 30 days ad hoc to populate index=risk with data you can use right away. No need to wait.
### Setup
Save all the searches as defined in each config file and then build your processes and procdures for response with testing and results. I'm not an app builder, but I wanted to give back to the community that gave so much to me.
# Do half the Math outside of Splunk
You can run searches against Splunk's Rest API from a remote server that can utilize data science tools locally once you have index=risk populated with usable data. 
