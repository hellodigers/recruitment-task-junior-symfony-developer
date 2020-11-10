# Back-End Developer Task -  NASA Mars Photos Gallery

**A small, Symfony-based project checking your backend development skills.** 



### Requirements/perequisites:
* Don't spend time on making nice/styled frontend
* Symfony 5.x, Doctrine, MariaDB/MySQL



### Preparation
Sign-up for free *NASA API* key https://api.nasa.gov/index.html#apply-for-an-api-key
to use the *MARS PHOTOS API* - https://api.nasa.gov => Section "Mars Rover Photos" for this project.






### Task description
Create a Symfony app with a REST API returning JSON contanining holiday info + photo information (image-related data, image url) taken on a given date or date range



1. Get / calculate a list of polish holidays in 2020 only and save them to the database (prepare console comand to refresh data)

2. Get a list of all images & image data for 2020 holidays' dates from NASA API and save them to the database (prepare console comand to refresh data)

3. Prepare *anonymous API with two endpoints*:

a) one endpoint that allows to return a JSON containing:

* a list of photos (image id, earth date, rover, camera) taken during holidays occuring on defined date/date range (all holidays in 2020 if no date parameters are sent within the api call)

Within the api call, allow to define the following image-related parameters:
* rover (Curiosity, Opportunity, Spirit), 
* Camera (FHAZ, RHAZ)

b)  Second endpoint - allowing to get detailed data for a single photo:
* image url
* image earth date
* rover
* camera

If no image-related parameters are set in the API call, return images from all cameras from all 3 missions.




**Once completed, submit to your github account and provide us with link.**

## Have fun!
