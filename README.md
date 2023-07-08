# Postman-API_Interface_Test
#### This note shows how to use postman to test API interfaces.

# Set up
Download and install Postman:[https://www.postman.com/downloads/]

<br>

# Testing API
Click the '+' symbol in Postman to create a new request.

## AUTHORIZATION
Switch to the 'Auth' tab to identify the authorization method and parameters.

* Basic Auth
This method provides traditional login method with a Username and a Password to sign in to a site.

* API Key
This method is the basic for token authorization.<br>
Leave the Key with value 'Authorization'<br>
Put your token to Value<br>
Normally, token is Add to Header<br>
(Github is a token login website)

* OAuth 2.0
This is also a token authorization method.<br>
Place your Token in Access Token would work

## HEADER
* You can add key-value pairs in request header in Header tab.

## Parameters
* Add value you want to sent to the server in this tab.

## Body
* Add data or file you want to sent in this tab.

  You can send JSON, XML and other files here.<br>
  Sending request.data format in Django, will use raw - JSON format.


## Make a request
* First, select a reqeust method, mostly used methods are 'GET', 'POST', 'PUT', 'DELETE' and so on.

* Put the URL of the API to the blank after the request method and you can send request.  

* All of your requests will be saved in History tab with results.

<br>

### GET
* Get data from API (or simply a site), you can assign what format of raw data you are receiving.
* If you are going to receive a file like .doc, .xls and so on, you need to use download result and save them as that format.

### POST/PUT/DELETE
* Input desired data format in the block and send it to the server.
