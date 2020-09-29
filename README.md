# Healthcare Telemetry

Case study by Anurag Thakur

Description:
Understand the data packets and communication configuration from the protocol document of the Device. Data packet will include patient vital information (measurement, setting, mode). Application to read data(patient vitals) from generic simulator(acting as a device) through virtual COM port. Parse the data based on device protocol document and display the parse data on the web UI. Which can be accessed remotely.
 
We will develop this in two segments.

## COM port reader and Data parser

Setup a virtual COM port and a simulator behind it. Implement a program that reads from the COM port and parses the data.

## Webserver application to display real time data on the web UI

You can use python with [streamlit](https://docs.streamlit.io/en/stable/) to show the data
