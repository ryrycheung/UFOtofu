# FindMe
A web/mobile app that lets users locate nearby emergency services locations and report their needs and physical conditions during an event of natural disaster in BC, Canada. 
Created and owned by Ryan Cheung and Ruimeng Pang.

## Mission Statement
The three digits telephone number '911' has been designated as a nationwide number that provides the public a fast and easy access to reach for emergency assistance. It is designed to handle a fair amount of calls at a given time. However, during an event of natural disaster, this communication network could be overwhelmed. This number would immediately pop up in the heads of people with concerns or in danger. At times like these, it is crucial that urgent emergencies receive priority attention. We understand that people could be desperate in finding out whether they are safe or who they could reach for help during natural disasters, therefore, we created the web, tablet and mobile application **FindMe** that allows people with concerns and/or suffering from less life-threatening situations to report their physical conditions and look-up emergency services locations, as well as real-time evacuation orders and alerts issued by the EmergencyInfoBC. We hope that **FindMe** could help alleviate the tension at the 911 call center and provide the public with crucial information about situations of the event.  

## Application Descriptions and Layers
Users could access to 3 main functions on **FindMe** - Look up emergency services locations, report physical conditions and locations and real-time emergency orders and alert. Nagivation through the tabs for these functions. The general app interface also links the users to the "Public emergency preparation and recovery" by the BC Government, and provides a link to all the Emergency Management B.C. office contacts.

### Emergency Services Locations
Launching **FindMe** will bring users to the 'Emergency Services' tab by default. From here, users have the ability to locate themselves on the map and pinpoint emergency services locations such as fire and police stations. Users can use the search bar to look for a specific facility. By selecting the name of the facility, the map view will automatically zoom to the selected feature.

### FindMe (Emergency Report)
The FindMe Emergency Report is a survey designed with Survey123. The survey collects information from the users on the event they experience at the time of filling the report, personal information, their physical conditions, supply sufficiency and locations. All of the columns are null-able, which means that the survey can be submitted with only the location in extreme urgent situtions.

### Emergency Orders and Alerts
EmergencyInfoBC is active during partial and full-scale provincial emergencies such as events of tsunami, wildfire and earthquakes. They share official response and information about the situation as well as real-time evacuation alerts and orders. Users could easily access these information on **FindMe**. 

## Open Data Sources
[1] Open Government License - British Columbia, Evacuation Orders and Alerts 
https://catalogue.data.gov.bc.ca/dataset/7efd46d0-b5d3-4dff-af80-d376c42aec33

[2] Open Government License - British Columbia, BC First Responder Locations
https://hub.arcgis.com/datasets/exchange::bc-first-responders/about

## References
[1] 

[2] University of Oxford, Natural Disaster Data Explorer
https://ourworldindata.org/natural-disasters#:~:text=States%20(not%20comparable)-,Natural%20disasters%20kill%20on%20average%2060%2C000%20people%20per%20year%20and,disaster%20event%20claims%20many%20lives
