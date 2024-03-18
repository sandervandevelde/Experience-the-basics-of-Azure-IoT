# Prerequisites of the Experience-the-basics-of-Azure-IoT workshop

Welcome to the Experience the Basics of Azure IoT workshop

# Prerequisites

Before you can start the IoT workshop you will need some prerequisites. 

Make sure you have arranged these software applications and accounts before the workshop starts.

_Note_: If you have installed these applications in the past, please update to the most recent version.

## Install software

Install the latest versions of the following applications:

- <a href="https://code.visualstudio.com/?WT.mc_id=IoT-MVP-5002324" target="_blank">Visual studio code</a>

  > This tool is used as an editor for the device simulation application

- <a href="https://nodejs.org/en/download/" target="_blank">Node.js runtime</a>

  > *Note*: You need administrator rights on your laptop to install Node.js.

  > *Note*: This course is tested using the latest LTS version.

  > *Note*: If Node is already installed, check the version with:

      node --version

- <a href="https://github.com/Azure/azure-iot-explorer/releases?WT.mc_id=IoT-MVP-5002324" target="_blank">Azure IoT Explorer (Preview)</a>

  > *Note*: This tool is used for checking out the device-to-cloud and cloud-to-device communication. As an alternative, the <a href="https://marketplace.visualstudio.com/items?itemName=vsciot-vscode.azure-iot-toolkit&WT.mc_id=IoT-MVP-5002324" target="_blank">Visual Studio Code extension for IoT Hub</a> can be used (out of scope for this tutorial)

- <a href="https://git-scm.com/downloads" target="_blank">Git</a>

  > *Note*: Using Git, you can download the app within Visual Studio Code.

## Create an Azure account

Register for the accounts:

- <a href="https://azure.microsoft.com/en-us/free/" target="_blank">Microsoft account</a>
  > *Note*: You should be able to access the Azure portal and create resources. Please, contact your administrator if needed.
  
  > *Note*: Although this is a guided workshop, some basic knowledge about Azure would be welcome. Please, contact the organizers if you need help to get started.

## Network

We will connect laptops to the internet using HTTPS and MQTTS over the (WIFI) network. 

Restricted networks (eg. using Zscaler) can interrupt the communication so it's recommended to have a less restrictive network during the workshop. 

An alternative is using a private hotspot/tethering.
