# favorite-place

```
This is my fav place app
> Sabah
> In msia

```




# livepersondemo
######  Twitter tweets search with NodeJS-Express back-end and Angular front-end

## Installing
Install tools / programs below:
1. [NodeJs](https://nodejs.org/en/download/) v11.15.0
2. [PM2](https://www.npmjs.com/package/pm2) v2.0.15


3. Copy/clone this project, and run the command below at the root folder. 
```
npm install
```

## Start application in PRODUCTION using PM2 + ecosystem.config.js (port 5000)
2.1 If you wish to run pgm in `prod mode` run the command below in the root folder else go to next section.
```
pm2 start ecosystem.config.js --env production
```
Main page: http://localhost:5000

To get the Tweeter result: http://localhost:5000/api/getEntries


## Start application in DEV (port 8080)
2.2 To run pgm in dev mode, use the command below:
```
node index.js
```
Main page: http://localhost:8080

To get the Tweeter result: http://localhost:8080/api/getEntries



## Unit testing**
1. Go to the root folder and use the command below:
```
npm test
```
2. Test cases covered:
- SQLite table insert
- SQLite table fields check
- SQLite table read
- SQLite table delete
- Twitter API
