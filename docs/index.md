# Calisthenics API v1.0.0



- [Events](#events)
	- [Create events](#create-events)
	- [Delete events](#delete-events)
	- [Retrieve events](#retrieve-events)
	- [Update events](#update-events)
	
- [Exercises](#exercises)
	- [Create exercises](#create-exercises)
	- [Delete exercises](#delete-exercises)
	- [Retrieve exercises](#retrieve-exercises)
	- [Update exercises](#update-exercises)
	
- [Parks](#parks)
	- [Create parks](#create-parks)
	- [Delete parks](#delete-parks)
	- [Retrieve parks](#retrieve-parks)
	- [Update parks](#update-parks)
	


# Events

## Create events



	POST /events


### Parameters

| Name    | Type      | Description                          |
|---------|-----------|--------------------------------------|
| name			| 			|  <p>Events's name.</p>							|
| address			| 			|  <p>Events's address.</p>							|
| city			| 			|  <p>Events's city.</p>							|
| state			| 			|  <p>Events's state.</p>							|
| zip			| 			|  <p>Events's zip.</p>							|
| country			| 			|  <p>Events's country.</p>							|
| description			| 			|  <p>Events's description.</p>							|
| contact			| 			|  <p>Events's contact.</p>							|
| image			| 			|  <p>Events's image.</p>							|
| video			| 			|  <p>Events's video.</p>							|
| url			| 			|  <p>Events's url.</p>							|

## Delete events



	DELETE /events/:id


## Retrieve events



	GET /events/:id


## Update events



	PUT /events/:id


### Parameters

| Name    | Type      | Description                          |
|---------|-----------|--------------------------------------|
| name			| 			|  <p>Events's name.</p>							|
| address			| 			|  <p>Events's address.</p>							|
| city			| 			|  <p>Events's city.</p>							|
| state			| 			|  <p>Events's state.</p>							|
| zip			| 			|  <p>Events's zip.</p>							|
| country			| 			|  <p>Events's country.</p>							|
| description			| 			|  <p>Events's description.</p>							|
| contact			| 			|  <p>Events's contact.</p>							|
| image			| 			|  <p>Events's image.</p>							|
| video			| 			|  <p>Events's video.</p>							|
| url			| 			|  <p>Events's url.</p>							|

# Exercises

## Create exercises



	POST /exercises


### Parameters

| Name    | Type      | Description                          |
|---------|-----------|--------------------------------------|
| name			| 			|  <p>Exercises's name.</p>							|
| description			| 			|  <p>Exercises's description.</p>							|
| level			| 			|  <p>Exercises's level.</p>							|
| image			| 			|  <p>Exercises's image.</p>							|
| video			| 			|  <p>Exercises's video.</p>							|
| url			| 			|  <p>Exercises's url.</p>							|

## Delete exercises



	DELETE /exercises/:id


## Retrieve exercises



	GET /exercises/:id


## Update exercises



	PUT /exercises/:id


### Parameters

| Name    | Type      | Description                          |
|---------|-----------|--------------------------------------|
| name			| 			|  <p>Exercises's name.</p>							|
| description			| 			|  <p>Exercises's description.</p>							|
| level			| 			|  <p>Exercises's level.</p>							|
| image			| 			|  <p>Exercises's image.</p>							|
| video			| 			|  <p>Exercises's video.</p>							|
| url			| 			|  <p>Exercises's url.</p>							|

# Parks

## Create parks



	POST /parks


### Parameters

| Name    | Type      | Description                          |
|---------|-----------|--------------------------------------|
| name			| 			|  <p>Parks's name.</p>							|
| address			| 			|  <p>Parks's address.</p>							|
| city			| 			|  <p>Parks's city.</p>							|
| state			| 			|  <p>Parks's state.</p>							|
| zip			| 			|  <p>Parks's zip.</p>							|
| country			| 			|  <p>Parks's country.</p>							|
| description			| 			|  <p>Parks's description.</p>							|
| image			| 			|  <p>Parks's image.</p>							|
| video			| 			|  <p>Parks's video.</p>							|

## Delete parks



	DELETE /parks/:id


## Retrieve parks



	GET /parks


### Parameters

| Name    | Type      | Description                          |
|---------|-----------|--------------------------------------|
| q			| String			| **optional** <p>Query to search.</p>							|
| page			| Number			| **optional** <p>Page number.</p>							|
| limit			| Number			| **optional** <p>Amount of returned items.</p>							|
| sort			| String[]			| **optional** <p>Order of returned items.</p>							|
| fields			| String[]			| **optional** <p>Fields to be returned.</p>							|

## Update parks



	PUT /parks/:id


### Parameters

| Name    | Type      | Description                          |
|---------|-----------|--------------------------------------|
| name			| 			|  <p>Parks's name.</p>							|
| address			| 			|  <p>Parks's address.</p>							|
| city			| 			|  <p>Parks's city.</p>							|
| state			| 			|  <p>Parks's state.</p>							|
| zip			| 			|  <p>Parks's zip.</p>							|
| country			| 			|  <p>Parks's country.</p>							|
| description			| 			|  <p>Parks's description.</p>							|
| image			| 			|  <p>Parks's image.</p>							|
| video			| 			|  <p>Parks's video.</p>							|


