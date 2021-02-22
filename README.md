# UFO-Sightings

## Overview of Project: Explain the purpose of this analysis.
The purpose of this project and analysis was to assist Dana in building a website that allows us to categorize/filter/pull UFO sightings and details from our large JSON file. Because the file is large we wanted to add an input section to the website (thru HTML) so users are able to sift through the sightings based on date, country, state, city and shape. In the module we only looked at adding a date filter, but in our challenge we created a dynamic filter system which creates filter criteria based on the keys in the JSON file. 

## Results: Describe to Dana how someone might use the new webpage by walking her through the process of using the search criteria. Use images of your webpage during the filtering process to support your explanation.
As opposed to the website we built in our module, in our challenge we have added new search criteria to sift through our UFO sightings. Instead of just date and 1 button to filter, we now have entries from our JSON keys (minus comments) and using "on change" through javascript our table automatically filters. This will allow our users to more easily find similar UFO sightings as well as find patterns throughout the data. Below is an image of how filter input can work in the new website:

![](https://github.com/DanMarks12/UFO-Sightings/blob/main/static/Images/filter_at_work.JPG)

Compared to the old website, we are able to use multiple filters in order to disect our data which is a big improvement for the wesbite as a whole. This was done with the following change to our app.js file:

![](https://github.com/DanMarks12/UFO-Sightings/blob/main/static/Images/filter_at_work.JPG)

## Summary: In a summary statement, describe one drawback of this new design and two recommendations for further development.
A couple draw backs to point out in changing the website is first the complexity of the code. It took me a lot more time coming up with a way to use dynamic filter so that a) multiple criteria can be selected and b) the code pulling out the correct filtering criteria. Although it currently works with the current data set, if there was ever an updated data set we would need to go back into the javascript code and further refactor it so match the new criteria. Speaking of new criteria, a suggestion I could give Dana is maybe add additional items for each sighting. The biggest I can think of is pictures (jpg) or videos (mp4) or links to these to provide further TANGIBLE evidence. Adding these will give these sightings more legitimacy to their accounts. Another thing they could add is witnesses, if the accounts are just reported by 1 person or maybe a family of 5, or a group of 20 strangers. Things like these can further describe the sitings we have. 
