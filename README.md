
# SpaceX program

I have created this program as a assigment by TechDome. This is front end application build using reactjs.

This program is develop to view different launches by SpaceX 
program. There are feature like filter.User can filter all record on the basis of filter by launch year, successful launch and successful landing.


## Methodology
I have created this project using ReactJS. To develop single page application.

Node.js v18.12.1

I have created responsive page using flex. Next create side view for filter. And in middle main content that receive data through api request. For using different api request i have created different components.   
## API Reference

#### Get all data

```http
https://api.spaceXdata.com/v3/lau
nches?limit=100
```
#### Launch Success Filter:

```http
https://api.spaceXdata.com/v3/launches?limit=100&launch_success=true
```
#### Launch Success Filter:

```http
https://api.spaceXdata.com/v3/launches?limit=100&launch_success=true&lan
d_success=true
```
#### Filter by year:

```http
https://api.spaceXdata.com/v3/launches?limit=100&launch_success=true&lan
d_success=true&launch_year=2014
```


## Run Locally
Clone the project

    git clone https://link-to-project

Install dependencies:

    npm install

Open it with any IDE and run command in cmd

    npm start
## Features

- Mobile view
- Tablate view
- Desktop view
- Single page application.