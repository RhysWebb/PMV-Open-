# PMV-Open

This piece of work has been pulled from my repository and altered (passwords removed) to showcase my work with PowerShell. This was a temporary piece of work which had been pulled together while the AWS Lambda and API were being built. 

Each Function within the script is meant to be a seperate file which can be called remotely from a master script. The outputs were then pulled and sent to the AWS database which inturn passed the data to a React JS front end. 

The aim was to automate server management and PMVs (Preventative Maintenance visits). These PMVs often took upwards of a week to resolve as data stored on servers was extremely sensitive. The tool, which would be installed as part of server builds, prevented this requirement by having immutable code installed on the server that could only be called by Roche Product Specialists. 

The script stored here output everything to a separate file and stored it on the server. Even without the remote management the script still cut PMVs down to 30 minutes from 40 hours. With the data being obtained manually. 
