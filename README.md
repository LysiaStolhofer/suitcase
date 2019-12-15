# Suitcase :handbag:

_If you're heading on a trip, Suitcase is the only app you need. Select your destination city, specify when you are going there, and Suitcase will provide you with all the essential information you need._

## Initial Pseudocode 
- The page loads with a generic background (Airport terminal backgroud)
- USER'S FIRST INTERACTION
	- User selects TRAVEL DATE (5 Day Range)
		Start Date | End Date
- After dates are selected, suitcase icon starts shaking with message to "Click Me". If user clicks icon, A destination will be slected   at random.
	- User selects city
	- User hits SUBMIT button

- The input fields and submit button will remain visible, so the user can make further requests
- The Suitcase app will then present 4 additional panes, e.g.
	- Weather
	- Accommodations
	- Local
	- Entertainment

- CATEGORY BREAKDOWN
	- WEATHER (Open Weather API)
		- Day of Travel
		- 5 Day forecast
	- ACCOMMODATIONS (Travel Payouts)
	- HOTEL - Topped Priced hotel based on stars. Will display top 5*, top 3*, top 1*, Data Given by us to API
		- Room Type: King
		- Num of Guest: 2
	- LOCAL (Yelp API)
		- Bars
		- Restaurant
		- Clubs
	- ENTERTAINMENT (Trip Advisor API)
		- Concerts & Shows
		- Sights & Landmarks
		- Shopping


- For each of the Panes (topics), the app will the assemble the API query URL and make the AJAX call.
- The response object will then be logged in the console, to enable inspection.
-  For each Pane, the relevant data will be pulled out of the object and displayed to that pane.
- Based on the category selected, different information will be displayed in the Panes.
-------------------------------------------------------------------------------------------------------------------------------

## Features :computer:

- Javascript & jQuery
- CSS/Materialize (instead of Bootstrap)
- Project management: GitHub
- Responsive layout design
- Firebase for persistent data storage
---------------------------------------------------------------------------------------------------------------------------------
## Structure 

- :file_folder: assets 
	- :file_folder: css
		- :page_facing_up: css.md
		- :page_facing_up: style.css
	- :file_folder: images
		- :page_facing_up: SuitCase.png
		- :page_facing_up: SuitCase2.png
		- :star: animated_favicon1.gif
		- :page_facing_up: main-bkgd.jpg
		- :page_facing_up: plane.png
	- :file_folder: java
		- :page_facing_up: apis.js
		- :page_facing_up: background_api.js
		- :page_facing_up: news.js
		- :page_facing_up: news_api.js
		- :page_facing_up: openweather_api.js
		- :page_facing_up: seatgeek_api.js
		- :page_facing_up: wikipedia_api.js
		- :page_facing_up: zomato.js
- :page_facing_up: Gameplan.md
- :page_facing_up: NJIB_sandpit.html
- :page_facing_up: README.md
- :page_facing_up: backgroundAPI.html
- :page_facing_up: demo.html
- :page_facing_up: index.html
- :page_facing_up: newlayout.html
- :page_facing_up: responsive_layout.html
- :page_facing_up: unsplash_photo_app.html
- :page_facing_up: Gameplan.md
- :page_facing_up: Gameplan.md
- :page_facing_up: Gameplan.md
- :page_facing_up: Gameplan.md
- :page_facing_up: Gameplan.md
-------------------------------------------------------------------------------------------------------------------------------
:earth_americas: https://guarded-lake-43731.herokuapp.com/
