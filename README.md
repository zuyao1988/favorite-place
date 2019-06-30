# favorite-place

```
This is my fav place app
> Sabah
> In msia

```




# livepersondemo
##  Twitter tweet search with nodejs backend

###### Installing
Install tools / programs below:
1. [NodeJs](https://nodejs.org/en/download/) v11.15.0
2. [PM2](https://www.npmjs.com/package/pm2) v2.0.15

###### Start an application
1. Go to the root folder. 
```
npm install
```

2. If you wish to run pgm in `prod mode`, else goto 3
```
pm2 start ecosystem.config.js --env production
```

Available urls:
Main page: http://localhost:5000
To get the Tweeter result: http://localhost:5000/api/getEntries


3. Run pgm in dev mode:
```
node index.js
```

Available urls:
- Main page: 
> http://localhost:8080
- To get the Tweeter result: 
> http://localhost:8080/api/getEntries


######  Unit testing
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
