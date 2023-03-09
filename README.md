# Image Scraping with Python -Project
## A fully functional Scraping project written in PYTHON that uses FLASK framework and MONGODB.
 
The project shows an example of creating an Image Scraper that collects images from the Google and stores the data (image urls) in MongoDb using the Flask for deployment.

Here's a quick walkthrough of my project:
* Create an API to get the URL of the searched images
* The input is taken from the user using a simple form interface designed using basic HTML-CSS
* Using response.get to get all the 'img' tags
* Get the source(img_src) form the 'img' tags
* Store all the sources in a dictionary
* Store the sources in the form of a dictionary on the MongoDB server <br>
    Remember to replace the password of MongoDb server or else you'll end up pushing the data on my server and will not be able to access it.
* Use Flask to host the application.

Althogh i have tried to follow as many industry standards as possible and tried to write a clean code,
feel free to correct me in case of any error or an optimized way of writing this code. Your contribution is highly appreciated.
Also the project will be deployed on Azure soon.


    
