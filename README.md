# BVack-End Developer Task -  NASA Mars Photos Gallery

**A small, Symfony-based project checking your backend development skills.** 



### Requirements/perequisites:
* Don't spend time on making nice/styled frontend
* Symfony 4.x, Doctrine



### Preparation
Sign-up for free *NASA API* key https://api.nasa.gov/index.html#apply-for-an-api-key
to use the *MARS PHOTOS API* - https://api.nasa.gov/api.html#MarsPhotos for this project.






### Task description
Create a Symfony app with a REST API returning JSON contanining photo information (image-related data, image url) taken on a given date or date range


**Upon launch, the app should**

1. Display a button [Get Holiday Data]
2. On click, collect Polish national holiday dates *(for 2018 only!)* from external source and save this info to database
3. Display [Holiday Data Retreival Complete] message

4. Prepare anonymous API with enpoint that allows to return a JSON containing:

* a list of holidays occuring on defined date/date range 
* list of images & image data taken on each holiday date

Within the api call, allow to define the following image-related parameters:
* rover (Curiosity, Opportunity, Spirit), 
* Camera (FHAZ, RHAZ)

If no image-related parameters are set in the API call, return images from all cameras from all 3 missions.



**Once completed, submit to your github account and provide us with link.**

## Have fun!
