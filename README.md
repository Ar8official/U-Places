<h3 align="center">U-Places</h3>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

## About <a name = "about"></a>

React frontend implementation for the MERN Fullstack App for sharing locations and pictures. Nodejs backend code available at [here](https://github.com/Ar8official/U_Places-backend)

App deployed to google firebase and heroku

## URL Routes:

`/`		

List of Users 	

No authentication required, always reachable.


`/:uid/places`	

List of Places for Selected Users	

No authentication required, always reachable.


`/authenticate` 

Signup + Login Form 	

Only unauthenticated have access.


`/places/new` 

New Place Form 		

Authentication required, only authenticated have access.


`/places/:pid` 

Update Place Form 		

Authentication required, only authenticated have access.

