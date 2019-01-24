# BVack-End Developer Task -  NASA Mars Photos Gallery

**A small, Symfony-based project checking your backend development skills.** 



### Requirements/perequisites:
* Don't spend time on making nice/styled frontend
* Symfony 4.x, Doctrine, MariaDB/MySQL



### Preparation
Sign-up for free *NASA API* key https://api.nasa.gov/index.html#apply-for-an-api-key
to use the *MARS PHOTOS API* - https://api.nasa.gov/api.html#MarsPhotos for this project.






### Task description
Create a Symfony app with a REST API returning JSON contanining holiday info + photo information (image-related data, image url) taken on a given date or date range



1. Get/calculate a list of polish holidays in 2018 only and save them to the database 

2. Prepare anonymous API with endpoint that allows to return a JSON containing:

* a list of holidays occuring on defined date/date range (all holidays in 2018 if no date parameters are sent within the api call)
* list of images & image data (mission, camera type) taken on each holiday date

Within the api call, allow to define the following image-related parameters:
* rover (Curiosity, Opportunity, Spirit), 
* Camera (FHAZ, RHAZ)

If no image-related parameters are set in the API call, return images from all cameras from all 3 missions.




**Once completed, submit to your github account and provide us with link.**

## Have fun!
