# Lodash and Moment Lambda layer

example of How To Add NodeJs Library Dependencies in a AWS Lambda Layer With Serverless Framework

## How to use

```
cd layer/nodejs
npm install --save lodash moment
```

Go back to root directory

```
sls deploy
```

## How to test

```
sls invoke --function hello --data=2
```
