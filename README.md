# Citi Bike New York
For those who want to practice exploratory data analysis and do not have a good project to start with, 
this is a really good project to start practicing your analytic skills!

# Background Information
Citi Bike is a public sharing bike system serving the New York City in Manhattan, Queens and Brooklyn. 
Citi Bike provides biketrips historical datasets from 2013 to 2019 for data enthusiasts and developers to explore.

# Project Description

## Bike Terminology
**Dock**: place at bike stations for bike users to park their bikes

**Dock Availability**: whether there are empty docks at the destination station for bike users to park their bikes when they arrive

Sometimes it is really hard for bike users to find a station to park their bikes, because users don't know if there are empty docks at the destination station when they arrive. 
In order to improve user experience, we decided to develop an in-app tool to predict whether there are empty docks when users arrive at the destination station.

This tool works like this: 

(1) users enter their destinations

(2) the tool will recommend to users stations with empty docks when they arrive

This tool is expected to help users reduce time on finding a station to park their bikes.

# What data analysis can do for this project?

To predict dock availability, we need to analyze the bike throughput of each station in a day and understand what factors will influence the bike throughput in a day. 
Bike throughput here means accumulated number of bikes that are being taken or being returned in a day. Presumably, factors such as weather, locations, day of the week should be taken into account when we try to predict dock availability.
For example, for stations located in office districts, people will ride their bikes there on weekdays, consequently there will be more bikes being returned on weekdays compared to weekends, so it is more likely for those stations to run out of empty docks.

Now we understand the purpose of this project and how data analysis can play a part, let us get started to gain some hands-on experience! 

You can download my python code and give it a try!
