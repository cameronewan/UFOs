# UFOs

## Overview of the analysis:
Dana wanted us to create a dynamic webpage for her to share her UFO data with the public. She wanted to filter the data based on several different parameters, which gives the User of her website a very interactive experience. I used Javascript and D3 to create an HTML webpage that will work perfectly for what she needs. To all the alien doubters out there, check out this webpage, and it might just change your mind. 


## Results:
Once the webpage is open, Users are greeted with a nice header and an introduction to what the webpage is about. Scroll down a little, and you will see the search/filter options which are available. You can filter by City, State, Country, or Shape. You can either search for very specific events and fill out all the fields, or you can simply search by just one field, such as state, and you will see all the sightings in that state. The data is presented right next to the filter, so the webpage is easy to read. 
<img width="1310" alt="Screen Shot 2021-05-02 at 10 21 33 PM" src="https://user-images.githubusercontent.com/75695931/116836517-cabfa980-ab94-11eb-884b-deaba673c293.png">
Above you can see I have searched for all the sightings in NY state, and the webpage returned all the results regardless of the other filters because they were empty. I made the web page user-friendly by showing examples of searches in each filter to guide the user on how to use the search functions. Users should also note that the filters are case sensitive - so all text should be lowercase, with state abbreviations and no special characters.

## Summary:
One drawback is that if we look at all the data that we had access to, one field is not on our web page, and that is "Duration." We have this data in our "data.js" file but no field for it because the data is a little messy, and it would not be easy to apply a filter to it. The data is not standardized. There is a lot of different formats in the data file. Unfortunately, we do not have a way right now of creating that filter in a functioning way. However, this is an aspect of the webpage we could re-work or manage to incorporate the "duration" filter because I think people will find that interesting. Another aspect I would like to change is to make the table that shows the filter results look a little more presentable and engaging. Adding some formatting and maybe a couple more images will take that webpage to the next level. As of right now, the table just appears a little bland and unprofessional, but nothing we cannot fix. 
