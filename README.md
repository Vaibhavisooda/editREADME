Weatherapi

Building a Backend API for Weather Forecast using Python as the Programming language and Flask as the framework and testing the api with postman

For execution of script follow these steps
#step1
run this script in the vs code make sure you have installed python on your device and also make sure the required libraries are installed like flask,requests
#step2
after hitting the run button in the terminal you will see the base url like http://127.0.0.1:5000 just open this in your browser.
by default this link is selected when you open this link you will see 404 error to fetch the weather you have to append this base url with api endpoint
/weather?location=city name #replace the city name with the name of the city of which you have to get the weather data
add this above url with city name to base url and then you will get the weather data ex:-http://127.0.0.1:5000/weather?location=bengaluru
Thats it now you can see the json file NOTE:-make sure your script is running parallely in vs code


![image](https://github.com/Vaibhavisooda/editREADME/assets/150245603/425c98b1-3950-4934-9090-45e87188b744)

few screenshots to show how the code is executed

![image](https://github.com/Vaibhavisooda/editREADME/assets/150245603/8f7ef6fb-e44b-4e3b-abc5-b57a36a1a4a6)

![image](https://github.com/Vaibhavisooda/editREADME/assets/150245603/389d1d96-3aa6-4da4-b623-caf21b4bc854)

output

![image](https://github.com/Vaibhavisooda/editREADME/assets/150245603/b411029f-da46-40ad-81d5-dd1d6a4168ba)

following all the steps you will get the result in json file you can also change the city name and try with other locations
after getting the output copy that url in your browser and test the api with postman

![image](https://github.com/Vaibhavisooda/editREADME/assets/150245603/5b692663-39d6-4d2a-824e-46ad9fe6f357)





