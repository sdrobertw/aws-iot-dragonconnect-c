---
layout: introduction
---
# Introduction
The DragonConnect project demonstrates recording events originating from the
DragonBoard and managing an LED.  The events are generated by pressing
the volume up and volume down keys on the DragonBoard.  When one of the
buttons is pressed, a client application written using the Amazon IoT C SDK
for embedded platforms uses MQTT to transfer the event to an Amazon data
center where it is stored in a DynamoDB table.

The LED is managed through the General Purpose IO (GPIO) of the DragonBoard
and uses AWS IoT Device Shadows.

The functionality of DragonConnect and how the application is configured is
detailed.  The documentation includes information on how to execute the client
and visit the dashboard.

Table of Contents
* * *
* Functionality
    * [Manage an LED](./functionality/circuit.html)
    * [Record Audio Button Events](./functionality/audioEvents.html)
* Administration
    * [General Configuration](./admin/general_conf.html)
    * [Foundational Elements](./admin/foundation.html)
    * [Create the Lambda Functions](./admin/lambda.html)
    * [DragonConnect API](./admin/api.html)
    * [DragonConnect Dashboard](./admin/dashboard.html)
    * [Manage Things](./admin/things.html)
* Execution
    * [Execute the Client](./execution/client.html)
    * [Visit the DragonConnect Dashboard](./execution/dashboard.html)