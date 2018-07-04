# Asset Tracking & Monitoring (ASTRA)
Asset Tracking & Monitoring Solution Accelerator

## About
1) This is the toplevel project which will provide the information regarding setup & deployment of Asset Monitoring Solution.
2) User is expected to follow the guidelines outlined & refer to the individual projects for further details.

## List of Repositories
Following are the repositories relevant for the accelerator:

1) [ARM-Template](https://github.com/MobiliyaTechnologies/ARM-Templates): Azure Resource Manager template for the solution.
2) [AMSMessagingServer](https://github.com/MobiliyaTechnologies/AMSMessagingServer): Node Server for passing Sensor data and rule break alerts.
3) [AMSMobileApplication](https://github.com/MobiliyaTechnologies/AMSMobileApplication): Xamarin based iOS & Android application.
4) [AMSPowerBI](https://github.com/MobiliyaTechnologies/AMSPowerBI): Reports & visualization templates.
5) [AMSRESTServer](https://github.com/MobiliyaTechnologies/AMSRESTServer): Backend server for the solution.
6) [AMSWebApp](https://github.com/MobiliyaTechnologies/AMSWebApp): Frontend web application for the solution.
7) [GatewayMiddleware](https://github.com/MobiliyaTechnologies/GatewayMiddleware): NodeJS application for passing sensor data to IoT hub.

## List of Documents
Following are the list of documents available for reference:

1) User guide: To use the solution deployed.
2) Admin guide: To configure and use the solution deployed.
3) Api Documentaion: Please refer '[AssetMonitoringApi.zip](https://github.com/MobiliyaTechnologies/AMSRESTServer/blob/master/AssetMonitoringApi.zip)' from AMSRESTServer repository.

## List of reference hardware (on premise)

Dell 5000 Gateway: Which acts as sensor aggregator, run edge analytics (Azure Stream Analytics on Edge)

TI Sensortags - 2650

Bosch Sensors - XDK
