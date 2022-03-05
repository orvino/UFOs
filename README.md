# UFOs
## UFOs Sightings

## Overview
Dana has requested a webpage with a dynamic table that provides more in-depth analysis of UFO sightings by allowing user to filer for multiple criteria, such as city, state, country, and shape.

## Results

### The Truth is Out There 
The title and header of the webpage where the user will land is first shown.  There is a brief four paragraphs from ufologists followed by our filter search and results columns.
<img width="1573" alt="Screen Shot 2022-03-05 at 11 42 10 AM" src="https://user-images.githubusercontent.com/91889241/156894256-43f764f3-81eb-4cb5-9956-e7ed5d88adf5.png">


### First Landing
The filters appear when first landing on the page default to all data shown from our source JSON file from the year 2010.  By typing into one of suggested placeholders as the filters, the result returns date, city, state, country, shape, duration and additional comments.  To ensure proper results, one has to type everything in lower case letters and no spaces at the end of the text. Press enter to initiate the filter. To reset the filter criteria, click the UFO Sightings at the top left of the website.
<img width="1576" alt="Screen Shot 2022-03-05 at 11 27 52 AM" src="https://user-images.githubusercontent.com/91889241/156894240-91182594-c3fe-496a-bad3-96e0543fa221.png">


### Example Probe Findings
Select Fresno and CA and get the following results. The results show only one reported sighting for 1 minute with lights hovering overhead before vanishing.
<img width="1454" alt="Screen Shot 2022-03-05 at 11 43 47 AM" src="https://user-images.githubusercontent.com/91889241/156894329-892c600c-d22b-4bcf-9603-2fe20ab3468b.png">

## Summary

### Drawback
The user must know specific dates, cities, or shapes to search. Some shapes like "light" might not be as intuitive. The filters require correct lower-case spellings and cannot include spaces at the end. The city used for example, could not be typed as "Fresno", “fresno_”, or "FRESNO". The only acceptable input would be "fresno".

## Recommendations
One recommendation is adding a dropdown list for all applicable selections in the filters box.  This way no typing would be necessary, all tables are read directly from the source material.  It would more easily allow for duplicate city names in differenct states and countries to be grouped properly.

The next addition to the filters should be to add a trim function to catch spaces at the end of words as well as allow for upper and lower cases.


