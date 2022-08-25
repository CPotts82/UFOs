# UFOs
## Overview
The purpose of this project was to create a user-friendly, interactive web application to filter and display recent (2010) UFO sighting information from a large dataset. Using JavaScript and Bootstrap, an aesthetically pleasing and easy to use web application make filtering for unique UFO data interesting and entertaining. The objective was to allow users to filter the data in multiple different ways, from very specific to extremely broad. Options to filter by date, city, state, country, and shape make this a very transformable dataset. 
## Resources
JavaScript, HTML, D3 library, Bootstrap, CSS
## Results
### How-to-Use web app
As stated in the Overview, this web application is extremely user friendly. There are just a couple of important details to make note of, like ensuring you hit the 'ENTER' key on the keyboard versus clicking a search button with your mouse. The other important factor is ensuring you click the top left "UFO Sightings" phrase to clear the input boxes and create a fresh search.  We will now walk through the search process:

  Upon opening the web application you will notice the input boxes are ready for the filters to be put in.  The input boxes have placeholders inside of them so the user can see the appropriate format to use when entering text. There are five input boxes, the user may fill any or none of the boxes to obtain data, then press the 'Enter' key on the keyboard to return the search results. After the user is finished working through the returned data, they may click the top left phrase "UFO Sightings" to clear the input boxes and ready them for a new search.  Another option is that the user simply edit the text boxes as they wish. When the text boxes hold the desired information, the user simply has to press 'Enter' to have the data returned to them. 
  
Examples of Searches:
The image below shows the search performed on the UFO data with the only filter being for the 'state' input box.  I have searched for all UFO Sightings in the state of Texas.  See below:

![TX_UFO_Search](https://user-images.githubusercontent.com/106348899/186559269-3bb8d5c5-0692-4eab-972d-613d23572968.png)

Once you have gone through your search results, simply click the "UFO Sightings" phrase in the top left corner o the page to clear the input boxes.  Now it is ready for a fresh search!!

To show a very specific search, using all input boxes for filters, I have search for UFO Sightings on 1/01/2010, in El Cajon, California, in the United States and with a shape of 'triangle'. See below for the returned results:

![Multi_Criteria_Search](https://user-images.githubusercontent.com/106348899/186768660-f9be2698-289a-41fe-888b-a767dfd6843c.png)


## Summary
### Drawback
This web application is super easy to use and undeniably fun but there are a couple of drawbacks:
  - If a user misspells anything while entering search criteria in the text boxes, the web application will not respond, the table stays blank and there is no indication of what the error is. This can definitely cause frustration in the users experience. 
  - This dataset is very limited. The dataset here only shows sightings from 1/1/2010 to 1/13/2010.
  - The data is not displayed visually. While the website is user friendly and visually appealling, the table data is not. The requested data is simply returned back to the user in a very basic table format.

   - limited data - This dataset is only from  Expand this set to include 10 years or more of data so trends can be spotted. 
   - not displayed visually  - the interactive table is really nice and super easy to use, but the data is not displayed in a visually appealing way. Sure, true researchers will not mind reading the small print that returns their search criteria but others may not want so spend that time sifting through the data.  
### Recommendations
   - add more data. Years worth of data. Add filter so you can filter by year.
   - Add interactive charts so that filtered data can be displayed visually. (Maybe a bubble chart that shows frequency of visits. Bar charts and histograms show frequency as will.  Bubble charts to illustrate visits per state.  Bar charts for cities?
