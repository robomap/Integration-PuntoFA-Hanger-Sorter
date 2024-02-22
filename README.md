# Integration Punto FA Hanger Sorter
Intralogistics integration to Robomap Cloud for exchanging data. The integration is between the Robomap Cloud Platform and the customer Punto Fa located in Lliça de Munt, Spain. The integration basically consists to extract data from the PLC Device and sending it to the cloud through an API. On the first versions the idea is to integrate the basic incidences of the system and, in the future, integrate more and more data in order to do a mirror of the PLC to the Cloud.

## Metadata
- **Customer**: Punto Fa.
- **Integration** Protocol: API.
- **Location**: Lliça, Spain.
- **Collaborators**: Robomap Cloud members and MIM Maintenance organization (PLC Team).

## Example
On the following link there's an example of an integration to Robomap Cloud done by MIM Patchworksevice in another customer [Example code](https://github.com/Group-MIM/2023MP030-Decantalo).

## Architecture
The integration consists of different elements; 
  · Robomap Cloud. Server where the application is hosted, this server runs on the cloud and is the one handling the reuqests from the customer integration.
  · Integration. Located on the customer side, is the software component that takes the data from the PLC Device and sends it, through the API.
  · PLC Device. Is where the

![image](https://github.com/robomap/Integration-PuntoFA-Hanger-Sorter/assets/35137073/4130ec92-5f8a-4629-90a8-a819157c34b5)

## Description
The Customer Integration software is developed in "Java?". Here are the main configurations.
  · **Development environment:** Visual Studio Code.
  · **Code language:** Java.
  · 

## API
The API (Application Protocol Interface) is the protocol exchanging the data between the Robomap Cloud and the Customer Integration. For the information related with the API check the following document. [API Document](https://github.com/robomap/Robomap-Cloud/blob/main/documentation/API.md).

## OPC-UA
OPC-UA is an industrial protocol for exchanging data with PLC Devices. In this case, we use the protocol to exchange data between the 

## Pending Tasks
- Test the API Integration by using Postman.
- Developing the API integration and do some tests.
- Test the network usage when downloading data from the PLC.

## Build
Once the software code is ready, will be exported in a .jar file and next translated to a .exe file. Afterwars, will be added as a service on the customer pc.

## Copyright
Robomap Technologies 2023 © Copyritght .
