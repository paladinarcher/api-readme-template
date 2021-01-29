# For initial project set up click **[here](SET-UP.md)**. Delete this line afterwards

* logo(optional) goes here
<h1 align="center">
	<img
		width="300"
		alt=""
		src="https://github.com/paladinarcher/padawan/blob/master/Logo%20Pack/PNG/redcirclesm300x300.png"
	> 
</h1>

# API Documentation Template
Description Goes Here

## Response Codes 
### Response Codes
```
200: Success
400: Bad request
401: Unauthorized
404: Cannot be found
405: Method not allowed
422: Unprocessable Entity 
50X: Server Error
```
### Error Codes Details
```
100: Bad Request
110: Unauthorized
120: User Authenticaion Invalid
130: Parameter Error
140: Item Missing
150: Conflict
160: Server Error
```
### Example Error Message
```json
http code 402
{
    "code": 120,
    "message": "invalid crendetials",
    "resolve": "The username or password is not correct."
}
```

## Login
**You send:**  Your  login credentials.
**You get:** An `API-Token` with wich you can make further actions.

**Request:**
```json
POST /login HTTP/1.1
Accept: application/json
Content-Type: application/json
Content-Length: xy

{
    "username": "foo",
    "password": "1234567" 
}
```
**Successful Response:**
```json
HTTP/1.1 200 OK
Server: My RESTful API
Content-Type: application/json
Content-Length: xy

{
   "apitoken": "e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855",
   "expirationDate": "2018-02-13T15:31:55.559Z"
}
```
**Failed Response:**
```json
HTTP/1.1 401 Unauthorized
Server: My RESTful API
Content-Type: application/json
Content-Length: xy

{
    "code": 120,
    "message": "invalid crendetials",
    "resolve": "The username or password is not correct."
}
``` 

## Overview
 * overview of project goes here example...  
	- **API Features** Push notifications, link previews, new message markers, and more bring IRC to the 21st century.
	- **Always connected.** Remains connected to IRC servers while you are offline.
	- **Cross platform.** It doesn't matter what OS you use, it just works wherever Node.js runs.
	- **Responsive interface.** The client works smoothly on every desktop, smartphone and tablet.
	- **Synchronized experience.** Always resume where you left off no matter what device.
	

## Installation and usage  
* How to connect

### Running stable releases  

 * running and stable releases info goes here

### Running from source  

The following commands install and run the development version of:

```sh
* git commands goes here
```


## Development setup  

Simply follow the instructions to run The project from source above, on your own
fork.
