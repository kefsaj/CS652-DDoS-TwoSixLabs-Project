------
# TwoSixLabs DDoS CS652 Project

------
Modified by Kefin Sajan

The aim for this project was to venture into solving DDoS attack that affect many systems. Using previous system states the future scenerios are predicted from 12 DDoS attacks from 36 data points. BGP are  a protocol used to connect between major internet service providers, by selecting the most efficient route to deliver information especially used when connecting long distances. These BPG connection are kept active by sending small messages to sustain the client to their destination. 

 Files used in this particular situation is Locatated: /content/drive/MyDrive/CS652101-Network-ArchProtocols/Twosixlabs 

Project requirements: https://pantelis.github.io/cs652/docs/cloud/projects/ddos-detection/

------

___For this project, data from various sourses were used___ 

This is based on "Detecting DDoS Attacks with Machine Learning" created by Chae Clark from Twosixlabs.
Based on: https://www.twosixlabs.com/detecting-ddos-attacks-with-machine-learning/  
Github link to project: https://github.com/chaeAclark/blog_ddos_detection


DataSet used to run this script was taken from "Two Six Labs Internet Disruption Dataset" By Chae Clark. Due to space limitations, specifically "Indian Ocean Earthquake" taking 215 MB and "Italy Blackout" taking 188.8 MB were the only datasets used in this particular situation. Some issues were presented when using other datasets, and script could not be run. These datasets are a collection over the years from various sources. 
- Two Six Labs Internet Disruption Dataset (BGP)
  - https://osf.io/ywz4t/
  
UOregon's Route Views Project was used to collect critical BGP data for this project. 
- University of Oregon Route Views Project
 - http://www.routeviews.org/routeviews/
 - http://archive.routeviews.org/

Datasets are labeled and described in CIDR blocks which includes the organization it belongs to and geolocation provided by MaxMind. 
Maxmind's GeoLite database provides approximate location related to each IP address related to each CIDR block 
 - MaxMind’s GeoLite2 free database  
  - https://dev.maxmind.com/geoip/geoip2/geolite2/ 
  
------

