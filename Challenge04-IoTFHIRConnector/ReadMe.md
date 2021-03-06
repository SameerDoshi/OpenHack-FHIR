# Challenge04 - IoT Converter for FHIR

## Scenario
The business unit you worked with is ecstatic with the data you provided and they’ve made tons of great progress driving new insights. Results have been so impressive that the Equipment Operations team has come to you with some hope – and some budget! They have lots of new COVID-related challenges as waves of infections cycle through some locations. They would love to know where equipment is, if it’s being used, and when was it last used and maintained.

Medical device companies are getting better and better at providing intelligence on telemetry data, events, and more.

As a software developer owning the Azure FHIR API, you must first set up the IoT ingestion.

For the second half of the challenge, you are switching hats to a data analysis role. You need to visualize and then analyze observations from a set of medical devices.
Data Scientist persona fits here, where they want to analyze streaming observations from devices to find patterns and make predictions. IoT remote patient monitoring sends basic healthcare telemetry. Do we need to explore respirator data?

Same data science team is now learning FHIR and are very excited - so of course they want more data! [Not sure it makes sense, but can we generate synthetic respirator data to maintain COVID story? I’m thinking some limited number of devices and data points they can get their heads around since not everyone will be savvy on device data.]

Task: Ingest IoT data [Jeff: ideally, this represents one or more COVID-related devices – like respirators. I think it’d be great to understand what machines were not/running and maybe last updated/maintained “checkpoints”.]

## Reference Architecture
<center><img src="../images/challenge04-architecture.png" width="350"></center>


## To complete this challenge successfully, you will perform the following tasks.

* **Setup IoT Central** using continuous patient monitoring application template.
* **Ingest data using IoT Connector for FHIR**. You will deploy the connector and use the simulated device to load that data into FHIR.
* **Validate data load**. You will validate the data using Postman.

## Before you start

Make sure you have completed the pre-work covered in the previous challenge: [Challenge00 - Pre-requisites: Technical and knowledge requirements for completing the Challenges](../Challenge00-Prerequistes/ReadMe.md).

## Getting Started

## Task #1: Setup IoT Central
Use the continuous data export feature in IoT Central to export data to Event Hub...

## Task #2: IoT Converter Preview
This section shows 
*

## Task #3: Validate data loaded using Postman
* 


## Congratulations! You have successfully completed Challenge04!

## Help, I'm Stuck!
* Below are some common setup issues that you might run into with possible resolution. If your error/issue is not here and you need assistance, please let your coach know.


***

[Go to Challenge05 - Analytics using FHIR Data: Analytics using Azure Data Factory, Databricks and PowerBI](../Challenge05-AzureDataAnalytics/ReadMe.md)
