# Top 3 Taco Shops

## Application Purpose
Top 3 Taco Shops is a webpage that highlights the top three taco shops in Austin, Texas and allows users to view these three taco shops and their popular offerings, followed by voting for their favorite taco from that respective shop, and viewing the map below that shows the exact map location of their favorite taco shop. These three taco shops were carefully selected based on online reviews and personal experiences.

![Screenshot 1](./assets/tacoshophomepage1.png)
![Screenshot 2](./assets/tacoshophomepage2.png)

## Application Demonstration
When users visit the Top 3 Taco Shops website, they are introducted to a major header showing the official website logo, a phrase indicating its purpose ("Taco Shops in Austin"), its slogan ("Any day is a good day for a taco!") brings significance for the current weather forecast indicator below it. The weather forecast includes an icon highlighting the current weather in Austin followed by its temperature in degrees Fahrenheit. This was developed with the use of the OpenWeather One Call API which fetches current weather forecasts from any city in the world.
![Screenshot 3](./assets/tacoshopfeature1.png)

Following the main header, the user is introduced to three distinctive cards of information. These three cards display the top three taco shops in Austin, Texas, respectively Torchy's Tacos, Taco Deli, and Veracruz All Natural, which are highlighted by three significant details. First is the title of the taco shop and a fact about the shop, followed with the address and phone number of their shop location. The significant aspect is the Top Picks category, which allows users to see the top five tacos (selected by the developers/"contributors") to try at that particular shop. When the user hovers their mouse over the name of a particular taco (say Trailer Park from Torchy's Tacos), a toolpick appears showing the user the ingredients of that taco (which for the Trailer Park taco consists of fried chicken, green chiles, lettuce, pico de gallo and cheddar jack cheese with poblano sauce on a flour tortilla).
![Screenshot 4](./assets/tacoshopfeature2.png)

Once they are done looking over the three cards of information of the taco places, the user will then view a dropdown list asking them to choose their favorite taco. Based on the Top Picks from each of the three places, there are fifteen tacos displayed on the list. Users will be able to select one taco from the dropdown list and the selected taco is then saved into the user's local storage of their browser. The same taco will remain in the local storage until the user selects another taco.
![Screenshot 5](./assets/tacoshopfeature3.png)

Finally, the user will view a map highlighting the three taco shop locations in Austin, which are shown on the map with a fork and knife icon. This map content was developed with the Mapbox API that allows developers to fetch and establish particular locations to be present for the user to see, which in this case is the Top 3 Taco Shops. The footer is then presented with the developers/"contributors" name and concludes the overall content of the application.
![Screenshot 6](./assets/tacoshopfeature4.png)

## Application Developed With
* HTML - Meets Web Content Accessibility Guidelines
* CSS
* JavaScript 
* Materialize - CSS Framework that provides modern responsive web design and was used to establish the modern design for the website. 
* Mapbox GL JS API - client-side JavaScript library used for building maps and adding user interactivity and customization. Mapbox was used to create the map element for the website and added exact location data of the taco shops.
* OpenWeather - One Call API: This API was used to collect the information that directly pulls the current weather forecast for a specific city, which is Austin, Texas for this application. With AJAX, it pulls information of the URL and with jQuery, appended the information to its own div content to display the weather forecast with the current temperature and an appended image source highlighting the current weather status.
* jQuery & jQuery UI - jQuery was implemented to function with the OpenWeather and Mapbox APIs to allow the map to display its coordinates of the taco shop location and display the current weather forecast for Austin, Texas. It was also used to implement local storage of saving the user's favorite taco. 

## Developer work committed
* Kevin A. 
- Provided research and pictures of the taco shops, listed Taco Ingredients and enabled toolpick feature for users to view it on the Top Picks list, established the Choose a Taco feature, its dropdown selection, and local storage of saved taco 
- developed initial map with the Mapbox API with zoom function and full screen function.

* Akhila S.
- Created inital website and design
- Designed web page with the Materialize framework 
- Designed cards with CSS styling

* Mickey T. 
- Implemented Header design for website 
- Created temperature and weather image display for the current Austin weather forecast using the OpenWeather Map's One Call Weather API and jQuery 
- GitHub Repository Manager - overviewed the GitHub repository for the project, made sure everyone was able to push and pull their respective project files, overviewed the main website and contributions.
- Created and completed the README for the project

* Jeff W. 
- Mapbox API Lead - added taco shop locations locations, hover features, and points of interests for the map api 
- Built and designed the presentation

## Repository Link and Deployed Application Website
* Project Repository - https://github.com/trujilml/top-3-taco-shops
* Deployed Website - https://trujilml.github.io/top-3-taco-shops/

## Further Development and Future Notes  
* Mickey: Margarita/alcohol/beer locator
- Additional card highlighting whether the taco shop offers alcohol at their specific location. Torchy’s, Tacodeli serves alcohol/beer; Veracruz does not.

* Kevin: Dark mode
- Add a button to toggle between light and dark mode. 
- We will also add code to let the user’s operating system do that lifting for us by saving the user’s selection so that it will be applied consistently throughout the site and on subsequent visits. To do that, we can save the user’s choice to the localStorage when the theme is toggled using Pure CSS or JavaScript. 

## Special Thanks
Special thanks to our instructor Torre Taylor and our teaching assistants (Vicky and Fernando) at The Coding Bootcamp at the University of Texas at Austin. 🤘🏼

## Contribution
Developed with ❤️ by Kevin, Akhila, Mekayla, and Jeff

© 2021 All Rights Reserved.
