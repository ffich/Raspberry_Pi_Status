# Raspberry_Pi_Status
A Node-RED flow to monitor the status of my Raspberry Pi devices.

# Description
This simple flow allows to add to your Raspberry Pi devices, a page with status monitorin. This is done via some periodic inject nodes that trigger some execution nodes requesting some data to the linux system via the console interface.
The result is then elaborated and sent to indicator widgets (gauges and charts).

The current monitored elements are:

- CPU Temperature
- Percentage of used RAM Memory
- Percentage of used Disk space
- Percentage of used CPU

This is the simple flow implemented:

![image](https://github.com/user-attachments/assets/17bca033-b1c1-47ae-85c4-73aefe9bf6dd)

Have a look to the code for additonal details.

# How it looks
Here is an example of what the flow can visualize (this is the Raspberry CM4 that control my lab domotics):

![image](https://github.com/user-attachments/assets/4d272ff6-025c-4609-82ef-e99e029adade)


