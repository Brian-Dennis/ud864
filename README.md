# ud864
This project follows along with Udacity and it's Full Stack Web Developer Nanodegree course. It focuses on the Neighborhood Map Project.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine.

### Prerequisites

What things you need to run this project

```
Google Maps API KEY:
Instructions to obtaining this is located at:
https://developers.google.com/maps/documentation/javascript/get-api-key
```

### Installing

A step by step series of examples that tell you have to get a development env running

First clone the repo

```
> git clone https://github.com/Brian-Dennis/ud864.git
```

change into project directory

```
> cd ud864
```
Add in your own API KEY provided by `Google` inside the project file add your api key within the script tag at bottom of the file<br>
Make sure to delete this from the URL structure and replace it with your provided API KEY `[[API_KEY_GOES_HERE]]`
```
<script async defer 
    src="https://maps.googleapis.com/maps/api/js?key=[[API_KEY_GOES_HERE]]&v=3&callback=initMap"> 
</script> 
```

## Author

* **Brian Dennis** - *Initial work* - [PurpleBooth](https://github.com/Brian-Dennis)

## Acknowledgments

* Hat tip to anyone who's code was used
* Udacity for putting on the course
* Google for the great API's and tools they provide
