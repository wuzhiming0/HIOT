# Hybrid IOT - able to work offline

## Requirements:

  - Setup, control device. 
  - Monitor, process, record measurements.
  - Work when internet is aviable and not aviable.
  

## Sub Projects:

  - Client:  WPF Client
  - Center Server: Global Dbase API.  Product/Asset/UNS/...  
  - Local Server: Mqtt Broker; Device manager;  Local DBase API. Device/Measurement 
  - Sensor: A mqtt sensor, starts with support of temperature, humidity, pressure, luminosity.  
