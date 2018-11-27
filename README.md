# RecommendationSystem
Using Ticketmaster API to recommend you some activities nearby you based on your favorite choice.
The user can register first, then login/logout. After login successfully, this website will use geolocation API to get user's location.
If geolocation API is failed, it will get the location from user's IP instead.
Base on this location, the website will retrieve events from Ticketmaster and then present them to the user.
The user can set events as their favorite. This website will base on their location and favorite categories to give some recommendation.
 
## Main Architectures
![alt text](https://raw.githubusercontent.com/changboar/RecommendationSystem/images/architecture.PNG)