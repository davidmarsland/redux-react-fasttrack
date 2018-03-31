# redux-react-fasttrack
### Welcome to FastTrack to Redux with React Training

<a target="_redux" href="https://redux.js.org" alt="redux">![redux](images/redux-128.png)</a>
<a target="_reactjs" href="https://reactjs.org" alt="react">![react](images/128px-React.svg.png)</a>

#### Instructor: David Marsland

#### Macy's SF Schedule: 4/5-4/6/2018 9:30am – 4:30pm

 ![DevelopIntelligence](images/Develop-Intelligence-logo-f.png)
 
<a target="_git_react" href="https://davidmarsland.github.io/redux-react-fasttrack/">https://davidmarsland.github.io/redux-react-fasttrack/</a>

 © 2018 David Marsland 

---
### FastTrack to Redux with React Training
**FastTrack to Redux with React Training** ​teaches students how to use two important React-related libraries: Redux and React Router.

 Building upon the solid foundation of Flux principles, Redux is explained and demonstrated as it related to Flux and React. 
 
 Additionally, routing with React Router is explored and integrated with Redux. 
 
 Utilizing best practices, students build a real application from scratch utilizing the more import aspects of React, Redux and React Router.

* Prerequisites: Advanced JavaScript ES6 and React Development Experience

  Ideally attendees of **FastTrack to React Training** with 3-6 months of recent Javascript experience.

* If you want to learn more about ES6, aka ES2015, here are some good tutorials:
      <br><a target="_babel" href="https://babeljs.io/learn-es2015/">https://babeljs.io/learn-es2015/</a>
      <br><a target="_udacity" href="https://www.udacity.com/course/es6-javascript-improved--ud356
  ">ES6 - JavaScript Improved | Udacity</a>

---
### Course Objectives
* Describe Redux and the problem it solves
* Configure a React and Redux development environment
* Explore the basic architecture of a React Redux application
* Develop applications using React and Redux

---
### Course Outline and Topics

* Flux & Redux Overview
* Three Principles of Redux
* Immutable Data
* Configuring Actions
* Creating Reducer Functions
* Working with Stores
* Combining Reducers
* Integrating with React
* Middleware Overview
* Creating Custom Middleware
* Redux Thunk and Asynchronous Actions
* Creating Containers with React-Redux
* Integrating React Router with React/Redux
* Configuring Paths
* Working with URL Parameters
* Testing Redux Reducers

---
### Lab Setup

#### Ensure that you have `node` and `npm` installed
In a terminal, powershell, or cmd prompt:

```
node -v
```
Should be >= 8.0
```
npm -v
``` 
Should be greater than 5.2.

#### If needed, install `Node.js LTS` from <a target="_setup" href="https://nodejs.org/">https://nodejs.org/</a>

If you need multiple versions of Node installed, you may want to install <a target="_ref" href="https://github.com/creationix/nvm">Node Version Manager for Mac or Linux</a> or <a target="_ref" href="https://github.com/coreybutler/nvm-windows">NVM for Windows</a>

Add node to your path, then **launch a new** terminal, cmd prompt, or powershell:

```
node -v
```
Should be >= 8.0
```
npm -v
``` 
Should be greater than 5.2.

Install eslint
```
npm install -g eslint
```
If npm -g doesn't work, you may have permissions issues. A workaround is `npx` which will get from npm if needed and install in local directory.
```
npx install -g eslint
```
  <a target="_ref" href="https://docs.npmjs.com/getting-started/fixing-npm-permissions">Fixing NPM Permissions on Mac or Linux</a>

---
#### Ensure that you have `git` installed
In a terminal, powershell, or cmd prompt:
```
git --version
```
Should be greater than 2.0

#### If needed, install `git` from <a target="_setup" href="https://git-scm.com/downloads">https://git-scm.com/downloads</a>

---
### For this course you'll need either a Text Editor or an IDE.

#### Recommended Text Editors:
* Visual Studio Code: install from <a target="_setup" href="https://code.visualstudio.com/">https://code.visualstudio.com/</a>
* Sublime Text
<a target="_setup" href="https://www.sublimetext.com/">https://www.sublimetext.com/</a>

---
### Recommended IDEs (not needed, Text Editor preferred)
Jetbrains IDEs, either WebStorm or IntelliJ.
<a target="_setup" href="http://www.jetbrains.com/">http://www.jetbrains.com/</a>

---
### Setting Up Your React Dev Environment Easily 
* Create React App simplifies setup 
* <a target="_ref" href="https://www.kirupa.com/react/setting_up_react_environment.htm">https://www.kirupa.com/react/setting_up_react_environment.htm</a>
* <a target="_ref" href="https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md">Create React App Docs</a>

 We'll do more setup in class as needed

---
### Introducing your instructor, David Marsland
<a target="_ref" href="https://www.linkedin.com/in/davidemarsland">https://www.linkedin.com/in/davidemarsland</a>
<br>
<br>
Web Development since the Dawn of the Web <br>
<a target="_ref" href="https://web.archive.org/web/19970616152144fw_/http://reality.sgi.com:80/mars_corp/"><img src="https://web.archive.org/web/19971210071250im_/http://reality.sgi.com:80/images/sgipowered.gif" />
<br>Wayback Machine 1997 reality.sgi.com/mars_corp</a>

---
### Life after SGI
* Sun Java Certified Developer and Instructor 1998-2004
* eBay Chief Instructor 2004-2009
* Sencha Chief Instructor / Training Director 2010-2015
* Marsland Enterprises Chief Instructor 2015-
* DevelopIntelligence Senior Technical Instructor 2017-

---
### Flux
<a target="_ref" href="http://facebook.github.io/flux/docs/in-depth-overview.html#content">Flux from Facebook

---
### Redux
<a target="_ref" href="https://redux.js.org/">redux.js.org</a>

<a target="_ref" href="http://blog.isquaredsoftware.com/presentations/2017-02-react-redux-intro/#/33">
State Management with React and Redux</a>

---
### Redux can be described in three fundamental principles:
* Single source of truth. The state of your whole application is stored in an object tree within a single store.
* State is read-only (immutable). The only way to change the state is to emit an action, an object describing what happened. 
* Changes are made with pure functions.

<a target="_ref" href="https://github.com/reactjs/redux/blob/master/docs/introduction/ThreePrinciples.md">Three Principles of Redux</a>

---
### Immutable Data

<a target="_ref" href="https://redux.js.org/faq/immutable-data">Redux Immutable Data</a>

---
### Redux Example and Lab
<a target="_ref" href="https://csb-62zvqom7kk-janthncuwn.now.sh/">
Redux Example Incrementer</a>

---
### Redux DevTools

<a target="_ref" href="https://chrome.google.com/webstore/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd?hl=en">Redux DevTools - Chrome Web Store</a>

Note, you must add a line to source code to enable tooling.  Try this on a Redux example without this and it will provide instructions:
<br>*No store found. Make sure to follow the <a target="_ref" href="https://github.com/zalmoxisus/redux-devtools-extension#usage">instructions</a>.*

For a basic Redux store simply add:            
```javascript
 const store = createStore(
   reducer, /* preloadedState, */
   window.__REDUX_DEVTOOLS_EXTENSION__ &&
     window.__REDUX_DEVTOOLS_EXTENSION__()
 );
```

---

### Redux Todo Example App from Redux Course 
* <a target="_redux" href="https://github.com/sadams/todo-redux-react-webpack">https://github.com/sadams/todo-redux-react-webpack</a>

* Make a directory `redux-fasttrack` where you want to save the course labs
```
cd redux-fastrack
```
```
git clone https://github.com/sadams/todo-redux-react-webpack.git
npm install
```

---
### Redux Labs from <a target="_thinkster" href="https://thinkster.io/tutorials/learn-redux/">thinkster.io</a>

<a target="_thinkster" href="https://thinkster.io" alt="thinkster.io">![thinkster](images/thinkster.png)</a>

 <a target="_thinkster" href="https://thinkster.io/tutorials/learn-redux/">Thinkster: Learn The Fundamentals of Redux from <a target="_thinkster" href="https://thinkster.io/tutorials/learn-redux/">thinkster.io</a></a>

Create a free account and/or login with github on <a target="_thinkster" href="https://thinkster.io/tutorials/learn-redux/">thinkster.io: Learn The Fundamentals of Redux</a>

<br>Note, to do the labs you will have to change git commands similar to this:

Starting from `redux-fasttrack` directory:
```
git clone -b 00 https://github.com/gothinkster/react-redux-realworld-example-app.git
```
Then `cd react-redux-realworld-example-app` and <br> `npm install` to download node modules (may take a while on windows) and `npm run start` to run a development server
```
cd react-redux-realworld-example-app
npm install
npm run start
```

---
### Lab: Learn the Fundamentals of Redux
* Do the first <a target="_thinkster" href="https://thinkster.io/tutorials/learn-redux">thinkster.io Lab: Learn the Fundamentals of Redux</a>

* Optionally you can create your own git branches to save key steps of your labs. 
  From a new terminal or powershell:
```
cd react-redux-realworld-example-app
git branch mylabs00start
git checkout mylabs00start
git add .
git commit -am "starting point for labs"
git checkout -b mylabs01reduxtodos
git branch
git status
```
* Add Redux store with `createStore()`
* Add DevTools to `createStore()` as on the previous page:

For a basic Redux store simply add:            
```javascript
 const store = createStore(
   reducer, /* preloadedState, */
   window.__REDUX_DEVTOOLS_EXTENSION__ && window.__REDUX_DEVTOOLS_EXTENSION__()
 );
```

---
### <a target="_thinkster" href="https://thinkster.io/tutorials/learn-redux/">thinkster.io</a> Lab: Displaying the State

Follow the steps in this <a target="_thinkster" href="https://thinkster.io/tutorials/learn-redux/displaying-the-state">thinkster.io Lab: Displaying the State<a>
* Subscribe the store to React's `setState()`
* Display checkbox tied to state
* <a target="_reduxsolutions" href="./redux-solutions/mars01todos/">Lab Solution Online</a>

Optional: when you're done you can commit your work and diff
```
git branch
git add .
git commit -am "Added redux store, reducer, and dispatch to todos checkbox"
git diff -b mylabs00start
```

---
### <a target="_thinkster" href="https://thinkster.io/tutorials/learn-redux/">thinkster.io</a> Lab: Using react-redux to Develop Conduit Site
Follow the steps in this <a target="_thinkster" href="https://thinkster.io/tutorials/setting-up-react-redux/introducing-react-redux">thinkster.io Lab: Setting up react-redux</a>

Optional: create and checkout a new branch for the next lab
```
git checkout -b mylabs02conduit
```
* Remember to remove App component from index.js
* Add components folder to src and create App.js in  `src/components/App.js`
* Building Conduit Site and adding `react-redux` Provider
* Subscribing to Redux Store with `store.subscribe()`
* Dispatching Actions with `store.dispatch()`
* Using `mapStateToProps()` and `react-redux connect()`
* <a target="_reduxsolutions" href="./redux-solutions/mars02conduit/">Lab Solution Online</a>


Optional:
```
git add .
git commit -am "Started Conduit site with react-redux"
git diff -b mylabs01reduxtodos
```
---
### <a target="_thinkster" href="https://thinkster.io/tutorials/learn-redux/">thinkster.io</a> Lab: Redux with Multiple Components
Follow the steps in this <a target="_thinkster" href="https://thinkster.io/tutorials/setting-up-react-redux/communicating-across-multiple-components">thinkster.io Lab: Communicating Across Multiple Components</a>
* <a target="_reduxsolutions" href="./redux-solutions/mars03conduitloading/">Lab Solution Online</a>

Optional: before you start coding:
```
git checkout -b mylabs03conduitloading
```
Optional: when you're done with the lab
```
git add .
git commit -am "Added comm across multiple components to loading..."
git diff -b mylabs02conduit
```
---
### <a target="_thinkster" href="https://thinkster.io/tutorials/learn-redux/">thinkster.io</a> Lab: Communicating Across Components, Middleware, and AJAX Calls
Follow the steps in this <a target="_thinkster" href="https://thinkster.io/tutorials/react-redux-ajax-middleware">thinkster.io Lab: AJAX Middleware</a>
* Making AJAX calls with `superagent` HTTP client library to lead conduit data feed
* <a target="_reduxsolutions" href="./redux-solutions/mars03conduitloading/">Lab Solution Online</a>

---
### <a target="_thinkster" href="https://thinkster.io/tutorials/learn-redux/">thinkster.io</a> Lab: Loading Data Feed
```
git checkout -b mylabs04conduitfeed
```
Follow the steps in this <a target="_thinkster" href="https://thinkster.io/tutorials/react-redux-ajax-middleware/creating-promise-middleware">thinkster.io Lab: Creating Promise Middleware</a>
* Using Middleware, `Promise`, and `mapDispatchToProps` to dispatch actions asynchronously

* Note: To enable Redux DevTools with Middleware, see <a target="_ref" href="https://github.com/zalmoxisus/redux-devtools-extension#12-advanced-store-setup">Redux DevTools Advanced Store Setup</a>

In this case, to use Redux DevTools modify `src/index.js`:
```js
// const store = createStore(reducer, applyMiddleware(promiseMiddleware));

/* eslint-disable no-undef */
const composeEnhancers = window.__REDUX_DEVTOOLS_EXTENSION_COMPOSE__ || compose;
const store = createStore(reducer, composeEnhancers(applyMiddleware(promiseMiddleware)));
/* eslint-enable */
```

---
### Displaying Retrieved Data in Components
Follow the steps in this <a target="_thinkster" href="https://thinkster.io/tutorials/react-redux-ajax-middleware/displaying-retrieved-data">thinkster.io Lab: Displaying Retrieved Data in Components</a>
* Update `reducer` to handle `action HOME_PAGE_LOADED`
* Build `ArticlePreview` component
* <a target="_reduxsolutions" href="./redux-solutions/mars03feed/">Lab Solution Online</a>

Optional:
```
git add .
git commit -am "Loaded data feed and dispatched actions"
git diff -b mylabs03conduitloading
```

---
### Routing in React
#### <a target="_ref" href="https://medium.com/@thejasonfile/basic-intro-to-react-router-v4-a08ae1ba5c42">Intro to React Router v4</a>

---
### <a target="_thinkster" href="https://thinkster.io/tutorials/learn-redux/">thinkster.io</a> Lab: Adding React Router
```
git checkout -b mylabs05router
```
Follow the steps in this <a target="_thinkster" href="https://thinkster.io/tutorials/react-router">thinkster.io Lab: React Router</a>
* <a target="_reduxsolutions" href="./redux-solutions/mars04router/">Lab Solution Online</a>

 To make the Redux DevTools work now, modify 
 `src/store.js`
 ```js
 // const store = createStore(reducer, middleware);

/* eslint-disable no-undef */
const composeEnhancers = window.__REDUX_DEVTOOLS_EXTENSION_COMPOSE__ || compose;
const store = createStore(reducer, composeEnhancers(middleware));
/* eslint-enable */
```

Optionally, when you're done:
```
git add .
git commit -am "Added react-router Links"
git diff -b mylabs04conduitfeed
git branch
```
---
### More Advanced Training Available from <a target="_thinkster" href="https://thinkster.io/tutorials/learn-redux/">thinkster.io</a>
* <a target="_thinkster" href="https://thinkster.io/topics/react">Advanced React and Redux Online Training (need PRO subscription)</a>

* More Advanced Online Training Available from <a target="_ref" href="https://thinkster.io/">thinkster.io</a>

---
### Mid-class Survey

Please let us know how class is going for you with this mid-class survey.  Comments are greatly appreciated!
#### <a target="_ref" href="http://bit.ly/react4-3-18">http://bit.ly/redux4-5-18</a>

---
### Redux Thunk and Asynchronous Actions

<a target="_ref" href="https://github.com/gaearon/redux-thunk">
Thunk Middleware for Redux:  redux-thunk</a> by Dan Abramov

<a target="_ref" href="https://codepen.io/stowball/post/a-dummy-s-guide-to-redux-and-thunk-in-react">Redux and Thunk in React Tutorial (long, optional)</a> by Matt Stow

 If you clone Matt's repo and run the example, to use Redux DevTools, modify
`src/store/configureStore.js` like this:
```javascript
export default function configureStore(initialState) {
    const composeEnhancers = window.__REDUX_DEVTOOLS_EXTENSION_COMPOSE__ || compose;
    const store = createStore(rootReducer, initialState, composeEnhancers(
        applyMiddleware(thunk),
    ));
    return store;    
}
```
 See <a target="_ref" href="https://github.com/zalmoxisus/redux-devtools-extension#12-advanced-store-setup">Redux DevTools: Advanced Store Setup
 
---
### React Redux Tutorial: Learning Redux in 2018

<a target="_valentinog" href="https://www.valentinog.com/blog/react-redux-tutorial-beginners/">Excellent React Redux Tutorial for Beginners: learning Redux in 2018</a> by Valentino Gagliardi

---
### React Redux Tutorial Labs

 Starting from `redux-fasttrack` directory:
 ```
 git clone https://github.com/valentinogagliardi/webpack-4-quickstart.git

 cd webpack-4-quickstart
 ```
 **Do not remove** the file ./src/App.js

 Optionally you can create your own git branch to save your labs. From a new terminal or powershell:
```
git branch 00start
git checkout 00start
git commit -am "starting point for labs"
git checkout -b 01store
git branch
npm install
```

---
### React Redux tutorial: getting to know the Redux store

Do the steps in <a target="_valentinog" href="https://www.valentinog.com/blog/react-redux-tutorial-beginners/#React_Redux_tutorial_getting_to_know_the_Redux_store">React Redux tutorial: getting to know the Redux store</a>

Add `__REDUX_DEVTOOLS_EXTENSION__` to `createStore()`:

For a basic Redux store simply add:            
```javascript
 const store = createStore(
   reducer, /* preloadedState, */
   window.__REDUX_DEVTOOLS_EXTENSION__ &&       
     window.__REDUX_DEVTOOLS_EXTENSION__()
 );
```

Optionally when you're done you can commit your work and diff, then create and checkout a new branch for the next lab. 
```
git branch
git add .
git commit -am "Added redux store"
git diff -b 00start
git checkout -b 02reducer
```

---
### React Redux tutorial: getting to know Redux reducers
<a target="_valentinog" href="https://www.valentinog.com/blog/react-redux-tutorial-beginners/#React_Redux_tutorial_getting_to_know_Redux_reducers">React Redux tutorial: getting to know Redux reducers</a>

After adding 'src/js/reducers/index.js' following the tutorial, do this to see the store in Redux DevTools:

Add this to `src/App.js`
```js
import store from "./js/store";
```
In a new terminal or powershell starting from `redux-fasttrack` 
```
cd webpack-4-quickstart
npm run start
```
Your redux app should finally run. Open DevTools and in Redux DevTools you should see State in the Store but it won't respond to Actions yet. 

Optionally:
```
git branch
git add .
git commit -am "Added reducer"
git diff -b 01store
```

---
### React Redux tutorial: getting to know Redux actions

```
git checkout -b 03actions
```
Do the steps in <a target="_valentinog" href="https://www.valentinog.com/blog/react-redux-tutorial-beginners/#React_Redux_tutorial_getting_to_know_Redux_actions">React Redux tutorial: getting to know Redux actions</a>

```
git branch
git add .
git commit -am "Added actions and constants"
git diff -b 02reducer
```
---
### React Redux tutorial: Redux store methods

```
git checkout -b 04storemethods
```
Do the first steps in <a target="_valentinog" href="https://www.valentinog.com/blog/react-redux-tutorial-beginners/#React_Redux_tutorial_Redux_store_methods">React Redux tutorial: Redux store methods</a> creating `src/js/index.js` and modifying `src/index.js`

Lab: Your redux app should run, but you won't see output. We're going to go under the hood in the console. 

Follow the instructions in <a target="_valentinog" href="https://www.valentinog.com/blog/react-redux-tutorial-beginners/#React_Redux_tutorial_Redux_store_methods">React Redux tutorial: Redux store methods</a> to interact with redux store in the console. 

Now you should know how to do all this with a `store`:
* access the current state with `getState()`.
* dispatch an action with `dispatch()`
* listen for state changes with `subscribe()`

```
git branch
git add .
git commit -am "Create src/js/index.js, mod src/index.js to expose store and action creator addArticle"
git diff -b 03actions
```
---
### React Redux tutorial: connecting React with Redux

<a target="_valentinog" href="https://www.valentinog.com/blog/react-redux-tutorial-beginners/#React_Redux_tutorial_connecting_React_with_Redux">React Redux tutorial: connecting React with Redux</a>
```
git checkout -b 05reactredux
```
Now we need to connect React and Redux with `react-redux`
```
npm i react-redux --save-dev
```
* `the mapStateToProps()` connects part of the Redux state to props
* `mapDispatchToProps()` connects Redux actions to React props

---
### React Redux tutorial: App component and Redux store

<a target="_valentinog" href="https://www.valentinog.com/blog/react-redux-tutorial-beginners/#React_Redux_tutorial_App_component_and_Redux_store">React Redux tutorial: App component and Redux store</a>

---
### React Redux tutorial: List component and Redux state

<a target="_valentinog" href="https://www.valentinog.com/blog/react-redux-tutorial-beginners/#React_Redux_tutorial_List_component_and_Redux_state">React Redux tutorial: List component and Redux state</a>

---
### React Redux tutorial: Form component and Redux actions
<a target="_valentinog" href="https://www.valentinog.com/blog/react-redux-tutorial-beginners/#React_Redux_tutorial_Form_component_and_Redux_actions">React Redux tutorial: Form component and Redux actions</a>

```
git branch
git add .
git commit -am "Add react-redux connect, use Provider"
git diff -b 04storemethods
```

```
git checkout -b 04storemethods
```

#### To get bootstrap styles like `col-md-4` to work, add:

```javascript
// src/js/index.js

import 'bootstrap/dist/css/bootstrap.min.css';
```

Then stop the server and:
```
npm i bootstrap –save-dev
npm run start
```
---
### React Redux tutorial: wrapping up
<a target="_valentinog" href="https://www.valentinog.com/blog/react-redux-tutorial-beginners/#React_Redux_tutorial_wrapping_up">React Redux tutorial: wrapping up</a>

Optionally when you're done you can commit your work and diff, then create and checkout a new branch for the next lab. 
```
git branch
git add .
git commit -am  "added List and Form and put inside Provider"
git diff -b 04storemethods
```

---
### Optional Lab: Catalog with React and Redux
* Port your simple catalog in React to use Redux for state management
* Previously, you modularized this code <a target="_ref" href="https://reactjs.org/docs/thinking-in-react.html">Thinking in React Shopping https://reactjs.org/docs/thinking-in-react.html</a>
* Refactor to use Redux 
* Use Todo Redux example for inspiration <a target="_redux" href="https://github.com/sadams/todo-redux-react-webpack">https://github.com/sadams/todo-redux-react-webpack</a>
* See previous page for setup
* Optional challenges: use your own test data for real shopping! 

---
### Free Course Videos from Dan Abramov
#### Learn Redux from its creator:

* <a target="_ref" href="https://egghead.io/series/getting-started-with-redux">Part 1: Getting Started with Redux (30 free videos)</a>

* <a target="_ref" href="https://egghead.io/courses/building-react-applications-with-idiomatic-redux">Part 2: Building React Applications with Idiomatic Redux (27 free videos)</a>

* <a target="_ref" href="https://github.com/tayiorbeii/egghead.io_redux_course_notes">Redux Course Notes</a>

---
### More React and Redux Learning Resources

* <a target="_ref" href="https://www.fullstackreact.com/30-days-of-react/">FullStack React 30 Days of React and Redux</a>

* <a target="_ref" href="https://www.fullstackreact.com/articles/react-tutorial-cloning-yelp/">React Tutorial: Cloning Yelp</a>

* <a target="_ref" href="http://cabin.getstream.io/">Learn React & Redux With Cabin</a>

* <a target="_ref" href="https://survivejs.com/react/introduction/">Survive JS - Webpack and React Book</a>

* <a target="_ref" href="https://github.com/ReactTraining/react-router">https://github.com/ReactTraining/react-router</a>

* <a target="_ref" href="https://github.com/reactjs/react-router-tutorial">react-router tutorial https://github.com/reactjs/react-router-tutorial</a>

---
### Redux Video Course by Wes Bos

* <a target="_ref" href="https://courses.wesbos.com/account/access/5a34aee80e25892227e21408">Wes Bos Redux Video Course</a>

* <a target="_ref" href="https://medium.com/netscape/my-recommended-free-resources-to-learn-react-68f4d20a8dc1">Free Resources to Learn React</a>
* <a target="_ref" href="https://livebook.manning.com/#!/book/react-quickly/">React Quickly book by Azat Mardan</a>
* <a target="_ref" href="https://livebook.manning.com/#!/book/react-quickly/chapter-9">React Quickly Free Chapter Menu Project</a>

* <a target="_ref" href="https://egghead.io/series/getting-started-with-redux">Part 1: Getting Started with Redux (30 free videos)</a>

* <a target="_ref" href="https://egghead.io/courses/building-react-applications-with-idiomatic-redux"> Part 2: Building React Applications with Idiomatic Redux (27 free videos)</a>

---
### Tools
* <a target="_ref" href="https://codesandbox.io/s/62zvqom7kk">Code Sandbox</a>

* <a target="_ref" href="https://csb-62zvqom7kk-janthncuwn.now.sh">Zeit for deployment</a>

* <a target="_ref" href="http://jsbin.com/mipesawapi/edit?js,output">JS Bin Online Editor</a>

---
### Github Tutorial
* <a target="_ref" href="http://kbroman.org/github_tutorial/pages/init.html">Github tutorial</a>

---
### Routing with Backbone and React
* React Quickly has a Backbone routing example in Ch. 13
* <a target="_ref" href="https://github.com/azat-co/react-quickly/tree/master/ch13">https://github.com/azat-co/react-quickly/tree/master/ch13</a>

---
### Backbone router to render React components by doing the following:
* Defining a router class with the routes object as a mapping from URL fragments to functions
* Rendering React elements in the methods/functions of the Backbone Router class
* Instantiating and starting the Backbone the Router object

---
### React Native Intro
<a target="_ref" href="https://www.slideshare.net/ModusJesus/intro-to-react-native">Intro to React Native</a>

---
### Resources to learn more
* <a target="_ref" href="http://reactquickly.co/demos">http://reactquickly.co/demos</a>
* <a target="_ref" href=" ">Review React Foundation Course Videos from Azat Mardan</a>
<a target="_react-quickly" href="https://livebook.manning.com/#!/book/react-quickly">React Quickly Book by Azat Mardan: Livebook</a>
* <a target="_ref" href=" ">React Quickly Summaries</a>

---
### Testing React Components

<a target="_ref" href="https://facebook.github.io/jest/docs/en/tutorial-react.html">Facebook Tutorial:  Testing React Components with Jest</a>

<a target="_ref" href="http://www.softwareishard.com/blog/testing/modern-react-component-testing-with-create-react-app-jest-and-enzyme/">Modern React Component Testing with create-react-app, Jest, and Enzyme</a>

---
### Testing Redux Reducers and More with Jest

<a target="_ref" href="https://hackernoon.com/redux-testing-step-by-step-a-simple-methodology-for-testing-business-logic-8901670756ce">Redux Testing Step by Step: A Simple Methodology for Testing Business Logic</a>

---
### Optional Homework
<a target="_ref" href="mongolab/">Optional Homework: Final AutoComplete Project in React Foundation</a>

---

### React and Redux Resources

* <a target="_ref" href="https://www.robinwieruch.de/tips-to-learn-react-redux/">Tips to learn React + Redux in 2018</a>

---
### Course Review
### Course Objectives
<input type="checkbox">  Describe Redux and the problem it solves
<br><input type="checkbox">  Configure a React and Redux development environment
<br><input type="checkbox">  Explore the basic architecture of a React Redux application
<br><input type="checkbox">  Develop applications using React and Redux

---
### Course Outline and Topics

<br><input type="checkbox">  Flux & Redux Overview
<br><input type="checkbox">  Three Principles of Redux
<br><input type="checkbox">  Immutable Data
<br><input type="checkbox">  Configuring Actions
<br><input type="checkbox">  Creating Reducer Functions
<br><input type="checkbox">  Working with Stores
<br><input type="checkbox">  Combining Reducers
<br><input type="checkbox">  Integrating with React
<br><input type="checkbox">  Middleware Overview
<br><input type="checkbox">  Creating Custom Middleware
<br><input type="checkbox">  Creating Containers with React-Redux
<br><input type="checkbox">  Integrating React Router with React/Redux
<br><input type="checkbox">  Configuring Paths
<br><input type="checkbox">  Working with URL Parameters
<br><input type="checkbox">  Testing Redux Reducers

---
### Congratulations, you are now all React and Redux Developers!

<a target="_di" href="https://developintelligence.com">![DevelopIntelligence](images/Develop-Intelligence-logo-f.png)<br></a>
<br>
<a target="_git_react" href="https://davidmarsland.github.io/react-spike/">https://davidmarsland.github.io/react-spike/</a>
### Thanks, please fill out course eval now, your comments are greatly appreciated!
#### <a target="_ref" href="https://www.surveymonkey.com/r/KHSXLM8">https://www.surveymonkey.com/r/KHSXLM8</a>

© 2018 David Marsland 