# UFOs
## Overview
The purpose of this project was to create a user-friendly, interactive web application to filter and display recent (2010) UFO sighting information from a large dataset. Using JavaScript and Bootstrap, an aesthetically pleasing and easy to use web application, make filtering for unique UFO data interesting and exciting. The objective was to allow users to filter the data in multiple different ways, from very specific to extremely broad. Options to filter by date, city, state, country, and shape make this a very transformable dataset. 
## Resources
JavaScript, HTML, D3 library, Bootstrap, CSS
## Results
### How-to-Use web app
As stated in the Overview, this web application is extremely user friendly. There are just a couple of important details to make note of, like ensuring you hit the 'ENTER' key on the keyboard versus clicking a search button with your mouse. The other important factor is ensuring you click the top left "UFO Sightings" phrase to clear the input boxes and create a fresh search.  The search process is outlined below:

Upon opening the web application, the input boxes are ready for the filters to be put in.  The input boxes have placeholders inside of them so the user can see the appropriate format to use when entering text. There are five input boxes, the user may fill all or none of the boxes to obtain data, then press the 'Enter' key on the keyboard to return the search results. After the user is finished working through the returned data, they may click the top left phrase "UFO Sightings" to clear the input boxes and ready them for a new search.  Another option is that the user simply edit the text boxes as they wish. When the text boxes hold the desired information, the user simply has to press 'Enter' to have the data returned to them. 
  
Examples of Searches:
The image below shows the search performed on the UFO data with the only filter being for the 'state' input box.  I have searched for all UFO Sightings in the state of Texas.  See below:

![TX_UFO_Search](https://user-images.githubusercontent.com/106348899/186559269-3bb8d5c5-0692-4eab-972d-613d23572968.png)

Once you have gone through your search results, simply click the "UFO Sightings" phrase in the top left corner of the page to clear the input boxes.  Now it is ready for a fresh search!!

To show a very specific search, using all input boxes for filters, I have search for UFO Sightings on 1/01/2010, in El Cajon, California, in the United States and with a shape of 'triangle'. See below for the returned results:

![Multi_Criteria_Search](https://user-images.githubusercontent.com/106348899/186768660-f9be2698-289a-41fe-888b-a767dfd6843c.png)


## Summary
### Drawback
This web application is super easy to use and undeniably fun but there are a couple of drawbacks:
  - If a user misspells anything while entering search criteria in the text boxes, the web application will not respond, the table stays blank and there is no indication of what the error is. This can definitely cause frustration in the users experience. 
  - This dataset is very limited. The dataset here only shows sightings from 1/1/2010 to 1/13/2010 which does not allow for spotting trends among the data. 
  - The data is not displayed visually  - the interactive table is really nice and super easy to use, but the data is not displayed in a visually appealing way. Sure, true researchers will not mind reading the small print that returns their search criteria but others may not want so spend that time sifting through the data.

### Recommendations
   - Add an error message if someone misspells something in the search boxes. If an error message pops up, the user will immediately know what is wrong and can fix it, instead of wasting time troubleshooting.
   - Add more data - Adding years worth of data would make this table even better. I know that would be an extremely large dataset but there have been UFO sightings for the past 100 years at least!  Adding as many years as this web application can support is ideal.  When there is that much data in one place, people will come back to this application over and over. Adding years worth of data would mean adding another search input box so that people could filter the data by year. 
   - Add interactive charts that are tied to the input boxes so that filtered data can be displayed visually. Interactive bar charts and histograms to show frequency of sightings and/or bubble charts to illustrate visits per state.  There are so many options for displaying the returned data in a more visually appealing way. 
