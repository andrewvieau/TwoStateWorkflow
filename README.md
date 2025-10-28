# TwoStateWorkflow
A simple workflow to help any Sitecore project get started with content governance

# Instructions
1. Navigate to your serialization folder, as defined by your sitecore.json file
2. git clone https://github.com/andrewvieau/TwoStateWorkflow
3. dotnet sitecore ser push -i TwoStateWorkflow

# Troubleshooting
**Environment default was not defined. Use the login command to define it.**

Make sure that you have defined a default environment in your .sitecore\user.json file. If you only have one environment, simply copy the details, rename it to "default" and make sure allowWrite is set to true. 
