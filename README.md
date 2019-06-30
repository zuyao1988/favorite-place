# favorite-place

```
This is my fav place app
> Sabah
> In msia

```




# livepersondemo
##  Twitter tweet search with nodejs backend

###### //------ BEFORE START ---------
Install tools / programs below:
1. NodeJs v11.15.0
> https://nodejs.org/en/download/

2. PM2 2.0.15
> https://www.npmjs.com/package/pm2


######  //-----  HOW TO START ---------
Steps to run the program.

- 1. Go to the root folder. 
> npm install

- 2.1 If you wish to run pgm in prod mode, else use 2.2:
> pm2 start ecosystem.config.js --env production

Available urls:
- Main page: 
> http://localhost:5000
- To get the Tweeter result: 
> http://localhost:5000/api/getEntries


- 2.2 Run pgm in dev mode:
> node index.js

Available urls:
- Main page: 
> http://localhost:8080
- To get the Tweeter result: 
> http://localhost:8080/api/getEntries


######  //-----  Run unit testing ---------
- 1. Go to the root folder and use the command below:
> npm test

- 2 Test cases covered:
```
a) sqlite insert
	- fields check
	- is able to insert
b) sqlite read
c) sqlite delete
d) Twitter API
```
