# Async Store Sample

**Note: This sample project has been moved to the [async-store](https://github.com/leapfrogtechnology/async-store) repository. Please find it [here](https://github.com/leapfrogtechnology/async-store/tree/master/examples/express-ts).**

Sample project for [async store](https://github.com/leapfrogtechnology/async-store) with [express](https://expressjs.com/). 

## Running
Install dependencies. 
```bash
$ yarn
```
Run the express app server. 
```
$ yarn start
```
Now you can test it through `curl`.
```
$ curl localhost:3000 -H x-id:1
```
```
Response to request: 1
```
