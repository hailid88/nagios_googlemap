
Nagios Google Map on Traffic Sensors
===========================
Nagios Google Map project is an initiative to create the application to integrate Nagios with Google maps.
The built-in Map of Nagios only shows the relationship among the hosts, with no information about the locations. By using google map, managers could quickly identify the exact locations where down hosts are, and send the person in charge to fix the problems.

We significantly improved the codes written by Maco to support the visualization of the SNAPS sensors on the Google map.

Usage
------------------
By using the AddHost function (shown in the repository at https://github.com/hailid88/nagios_addhost), users can input the spatial location. Then both spatial and logical relations between SNAPS sensors are shown on Google map. One example is illustrated as follows:
![](https://github.com/hailid88/nagios_googlemap/blob/master/nagmap%20web%20interface.png)




