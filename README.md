# Program demonstrate clustering in NODE.js

## Run
* Run application
```
node index.js
```
* Run browser with URL `http://localhost:3000/api/5000000`

<br></br>

## Versions

* `index.js` - simple node version
* `index-with-cluster.js` - the same but with clusters

<br></br>

## Testing

* Install `loadtest` globally
```
npm install -g loadtest
```
* Run application
```
node index.js
```
* In another terminal run loadtest
```
loadtest http://localhost:3000/api/5000000 -n 1000 -c 100
```

<br></br>

### References
- https://blog.appsignal.com/2021/02/03/improving-node-application-performance-with-clustering.html