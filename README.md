# Disjoin Front End

The user interface of the Disjoin web application, designed for mobile use

## Getting Started

Download the my-app folder or clone the [repo](https://github.com/Disjoin-Covid-19/frontend)

### Prerequisites

Node.js and npm (follow this [link](https://www.npmjs.com/get-npm) for instructions)

```
npm install
```

### Running the App

#### Determine where to load API requests 
1. Static file public/data - No Configuration necessary
1. Use express server to host JSON files
* Remove the public/data file
* Run the following commands

```
cd server 
node expressjson.js 
```

#### Run the front-end
1. Run the app (I would recommend using the "inspect element" tool on your browser to view the mobile interface of the app, check [here](https://www.sitepoint.com/how-to-simulate-mobile-devices-with-device-mode-in-chrome/) for help):

```
cd my-app
npm start
```

<p align="center">
  <img src="https://github.com/Disjoin-Covid-19/frontend/blob/master/screenshots/Screen%20Shot%202020-06-19%20at%209.09.47%20PM.png" width="20%" style="border: 1px solid black">
  <br>
  <em>Landing page</em>
</p>

<p align="center">
  <img src="https://github.com/Disjoin-Covid-19/frontend/blob/master/screenshots/Screen%20Shot%202020-06-19%20at%209.10.01%20PM.png" width="20%">
  <br>
  <em>List of local supermarket stores</em>
</p>

<p align="center">
  <img src="https://github.com/Disjoin-Covid-19/frontend/blob/master/screenshots/Screen%20Shot%202020-06-19%20at%2010.58.26%20PM.png" width="20%">
  <br>
  <em>Foot traffic information for a specific store</em>
</p>


## Built With

* [React](https://reactjs.org/) - JavaScript library for building user interfaces
* [MaterialUI](https://material-ui.com/) - React UI framework

## Authors

* **Kassie Wang** 

See also the list of [contributors](https://github.com/Disjoin-Covid-19/frontend/graphs/contributors) who participated in this project.
