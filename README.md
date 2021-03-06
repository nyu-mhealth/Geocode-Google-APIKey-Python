# Geocode-Google-APIKey-Python
Code and documentation for developing a python script to geocode more than 2500 records in Google using API.  
Comes from this: https://github.com/googlemaps/google-maps-services-python

## Steps to get API Key and billing for Geocoding in Google  

#### Create an account on Google Cloud services (I signed up for free trial)  
- https://console.cloud.google.com/home/dashboard?project=focus-appliance-131314&authuser=0

#### Create Project  
From: https://developers.google.com/maps/documentation/geocoding/get-api-key#get-an-api-key  
- Go to the Google Developers Console.
- Create or select a project.
- Click Continue to Enable the API.
- On the Credentials page, get a Server key (and set the API Credentials). 
- Note: If you have an existing Server key, you may use that key.
- To prevent quota theft, secure your API key following these best practices.
- (Optional) Enable billing. See Usage Limits for more information.

https://developers.google.com/maps/documentation/geocoding/start#policies  

## Setting up Dev Environment  

#### Install googlemaps module  

    $ pip install -U googlemaps

###Virtual envirnoment for packages
https://www.jetbrains.com/help/pycharm/2016.1/adding-existing-virtual-environment.html
http://docs.python-guide.org/en/latest/dev/virtualenvs/

## Google documentation
https://developers.google.com/maps/documentation/geocoding/intro  

### Converting json to csv in python  
http://blog.appliedinformaticsinc.com/how-to-parse-and-convert-json-to-csv-using-python/  

### Reading and writing to csv from json  
https://automatetheboringstuff.com/chapter14/

###pandas and csv writing
https://www.safaribooksonline.com/library/view/python-cookbook/0596001673/ch01s06.html
http://chrisalbon.com/python/pandas_dataframe_importing_csv.html

##Time to run 3500 records
Start time: 2016-05-22 21:28:41.408059
End time: 2016-05-22 21:45:47.507958
34 minutes

###Google API  
Go to Google API Dashboard
account: ho449@nyu.edu