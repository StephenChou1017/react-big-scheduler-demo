# react-big-scheduler-demo

It's easy to create a react-big-scheduler demo with `create-react-app` and `yarn`. Install `create-react-app` and `yarn` first if you haven't.

```
$ npm install -g create-react-app yarn
```

Create the demo app and install `react-big-scheduler`:

```
$ create-react-app react-big-scheduler-demo
$ cd react-big-scheduler-demo
$ yarn add react-big-scheduler
```

Copy `src/Basic.js` and `src/withDnDContext.js` from this repo to the `src` folder, and replace all the `App` words with `Basic` in `src/index.js`. Then start the demo:

```
$ yarn start
```