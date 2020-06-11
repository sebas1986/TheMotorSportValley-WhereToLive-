# Living in the MotorValley
## Which is the best place to live for those who start working in Ferrari?
##### This is the final project of the Coursera Applied Data Science Capstone course
###### By Sebastian D'Amico
<br/><br/> 
### Introduction
Ferrari headquarter is in Maranello, a small town at about 18 km from Modena, with a population of 17,504 (as of 2017). It is known worldwide as the home of Ferrari and Scuderia Ferrari Formula One racing team. Several other towns surround Maranello, and Modena, with 184.000-ish inhabitants, is the closest and biggest town with Shopping Centers, University, nightlife and many other services that push most of the people, joining Ferrari, to look for a house. Obviously is difficult to find all the services that are present in Modena in any other small town that surround Maranello, but which are the main differences between all the towns? The aim of this project is to classify the Maranello and surrounding towns in terms of available services and venues to help people joining Ferrari to judge, with real numbers, which is the place that better suits his own requirements.
<br/><br/> 
### The data
Different datasources will be used for this project. First of all I will take all the towns in the province of Modena (47 total municipalities) from the following website:
https://zip-codes.nonsolocap.it/emilia-romagna/91-cap-province-of-modena/  
I will then try to use the Geocoder Python to get coordinates from each postal code. In case of failing, I will manually extract Latitude and Longitude from Google Maps for each town.  
On top of that, the distance from Ferrari will be associated to each town such that people can judge also based on the time they will spend to go to the office. If I don't manage to get the distance using Google API, I will extract it manually.  
Finally, Foursquare will be used to explore each town, extracting information of all the venues categories that will be used for having a better picture of what can be found in each town.  
Plots and tables will help to better analize tha data and to drive the analysis also based on the results, still having as main target what already described in the introduction. 
<br/><br/> 
