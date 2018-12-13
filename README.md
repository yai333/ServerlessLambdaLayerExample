# Lodash and Moment Lambda layer

example of How To Add NodeJs Library Dependencies in a AWS Lambda Layer With Serverless Framework
https://medium.com/neami-apps/how-to-add-nodejs-library-dependencies-in-a-aws-lambda-layer-with-serverless-framework-d774cb867197

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
