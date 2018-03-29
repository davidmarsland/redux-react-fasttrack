# redux-react-fasttrack
### FastTrack to Redux with React Training

#### Instructor: David Marsland
<br>
<img src="http://www.developintelligence.com/sites/all/themes/diresponsive/images/Develop-Intelligence-logo-f.png">
<br>
<a target="_di" href="http://developintelligence.com">DevelopIntelligence.com</a>
<br>
<a target="_git_react" href="https://davidmarsland.github.io/redux-react-fasttrack/">https://davidmarsland.github.io/redux-react-fasttrack/</a>

---
### FastTrack to Redux with React Training
**FastTrack to Redux with React Training** ​teaches students how to use two important React-related libraries: Redux and React Router. Building upon the solid foundation of Flux principles, Redux is explained and demonstrated as it related to Flux and React. Additionally, routing with React Router is explored and integrated with Redux. Utilizing best practices, students build a real application from scratch utilizing the more import aspects of React, Redux and React Router.

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
* Immutable Programming
* Configuring Actions
* Creating Reducer Functions
* Working with Stores
* Combining Reducers
* Integrating with React
* Middleware Overview
* Creating Custom Middleware
* React-Thunk and Asynchronous Actions
* Creating Containers with React-Redux
* Integrating React Router with React/Redux
* Configuring Paths
* Working with URL Parameters

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

We'll do more setup in class as needed.

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

---
### Flux
<a target="_ref" href="http://facebook.github.io/flux/docs/in-depth-overview.html#content">Flux from Facebook

---
### Redux
<a target="_ref" href="https://redux.js.org/">redux.js.org</a>

<a target="_ref" href="http://blog.isquaredsoftware.com/presentations/2017-02-react-redux-intro/#/33">
State Management with React and Redux</a>


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
```JavaScript
 const store = createStore(
   reducer, /* preloadedState, */
+  window.__REDUX_DEVTOOLS_EXTENSION__ && window.__REDUX_DEVTOOLS_EXTENSION__()
 );
```

---

### Redux Todo Example App from Redux Course 
* <a target="_redux" href="https://github.com/sadams/todo-redux-react-webpack">https://github.com/sadams/todo-redux-react-webpack</a>
* Clone repo, then:
```
npm install
npm run start
```
* Launches on localhost:8080 by default.

---
### Redux Labs


* <a target="_thinkster" href="https://thinkster.io/tutorials/learn-redux/">Thinkster: Learn The Fundamentals of Redux from thinkster.io</a>
<br>Note, to do the labs you will have to change git commands similar to this:
```
git clone -b 00 https://github.com/gothinkster/react-redux-realworld-example-app.git
```
Then `cd react-redux-realworld-example-app` and <br> `npm install` to download node modules (may take a while on windows) and `npm run start` to run a development server
```
cd react-redux-realworld-example-app
npm install
npm run start
```
* Create a free account and/or login with github on <a target="_thinkster" href="https://thinkster.io/tutorials/learn-redux/">Thinkster: Learn The Fundamentals of Redux from thinkster.io</a>

---
### Lab: Learn the Fundamentals of Redux
* Do the first `thinkster` lab <a target="_thinkster" href="https://thinkster.io/tutorials/learn-redux">Lab: Learn the Fundamentals of Redux</a>
* Optionally you can create your own git branch to save your labs. From a new terminal or powershell:
```
cd react-redux-realworld-example-app
git branch mylabs00start
git checkout mylabs00start
git commit -am "starting point for labs"
git checkout -b mylabs01reduxtodos
git branch
```
* Add Redux store with `createStore()`
* Add DevTools to `createStore()` as on the previous page:

For a basic Redux store simply add:            
```JavaScript
 const store = createStore(
   reducer, /* preloadedState, */
   window.__REDUX_DEVTOOLS_EXTENSION__ && window.__REDUX_DEVTOOLS_EXTENSION__()
 );
```

---
### Lab: Displaying the State
<a target="_thinkster" href="https://thinkster.io/tutorials/learn-redux/displaying-the-state">Lab: Displaying the State<a>
* Subsribe the store to React's `setState()`
* Display checkbox tied to state
* <a target="_reduxsolutions" href="./redux-solutions/mars01todos">Lab Solution Online</a>

Optionally when you're done you can commit your work and diff, then create and checkout a new branch for the next lab. 
```
git commit -am "Added redux store, reducer, and dispatch to todos checkbox"
git diff -b mylabs00start
git checkout -b mylabs02conduit
```
---
### Lab: Using react-redux to Develop Conduit Site
<a target="_thinkster" href="https://thinkster.io/tutorials/setting-up-react-redux/introducing-react-redux">Setting up react-redux</a>
* Remember to remove App component from index.js
* Add components folder to src and create App.js in  `src/components/App.js`
* Building Conduit Site and adding `react-redux` Provider
* Subscribing to Redux Store with `store.subscribe()`
* Dispatching Actions with `store.dispatch()`
* Using `mapStateToProps()` and `react-redux connect()`
* <a target="_reduxsolutions" href="./redux-solutions/mars02conduit">Lab Solution Online</a>


Optionally when you're done:
```
git commit -am "Started Conduit site with react-redux"
git diff -b mylabs01reduxtodos
git checkout -b mylabs03conduitloading
```
---
### Lab: Redux with Multiple Components
<a target="_thinkster" href="https://thinkster.io/tutorials/setting-up-react-redux/communicating-across-multiple-components">Communicating Across Multiple Components</a>
* <a target="_reduxsolutions" href="./redux-solutions/mars03conduitloading">Lab Solution Online</a>

Optionally when you're done:
```
git commit -am "Added comm across multiple components to loading..."
git diff -b mylabs02conduit
git checkout -b mylabs04conduitfeed
```
---
### Lab: Communicating Across Multiple Components and AJAX Calls
<a target="_thinkster" href="https://thinkster.io/tutorials/setting-up-react-redux/react-redux-ajax-middleware">AJAX Middleware</a>
* Making AJAX calls with `superagent` HTTP client library to lead conduit data feed
* <a target="_reduxsolutions" href="./redux-solutions/mars03conduitloading">Lab Solution Online</a>

---
### Lab: Loading Data Feed
<a target="_thinkster" href="https://thinkster.io/tutorials/react-redux-ajax-middleware/creating-promise-middleware">Creating Promise Middleware</a>
* Using Middleware, `Promise`, and `mapDispatchToProps` to dispatch actions asynchronously
<a target="_thinkster" href="https://thinkster.io/tutorials/react-redux-ajax-middleware/displaying-retrieved-data">Displaying Retrieved Data in Components</a>
* Update `reducer` to handle `action HOME_PAGE_LOADED`
* Build `ArticlePreview` component
* <a target="_reduxsolutions" href="./redux-solutions/mars03conduitfeed">Lab Solution Online</a>

Optionally when you're done:
```
git commit -am "Loaded data feed and dispatched actions"
git diff -b mylabs03conduitloading
git checkout -b mylabs05router
git branch
```
---
### Routing in React
* <a target="_ref" href="https://medium.com/@thejasonfile/basic-intro-to-react-router-v4-a08ae1ba5c42">Intro to React Router v4</a>

---
### Lab: Adding React Router
<a target="_thinkster" href="https://thinkster.io/tutorials/setting-up-react-redux/communicating-across-multiple-components">React Router</a>
* <a target="_reduxsolutions" href="./redux-solutions/mars04router">Lab Solution Online</a>

Optionally, when you're done:
```
git commit -am "Added react-router Links"
git diff -b mylabs04conduitfeed
git branch
```
---
### More Advanced Training Available from Thinkster.io
* <a target="_thinkster" href="https://thinkster.io/topics/react">Advanced React and Redux Online Training (need PRO subscription)</a>

* More Advanced Online Training Available on <a target="_ref" href="https://thinkster.io/">thinkster.io</a>

---
### React Redux Tutorial: Learning Redux in 2018

<a target="_ref" href="https://www.valentinog.com/blog/react-redux-tutorial-beginners/">React Redux Tutorial for Beginners: learning Redux in 2018</a> by Valentino Gagliardi

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
#### Course Objectives
<input type="checkbox">  Describe React and the problem it solves
<br><input type="checkbox">  Explore the basic architecture of a React component
<br><input type="checkbox">  Gain a deep knowledge of React components and JSX
<br><input type="checkbox">  Learn how to manage application
state with Flux and Redux

---
#### Topics Review

| React Training | Redux & React + React Router |
| ------- | ------- |
| <input type="checkbox">  Intro to React | <input type="checkbox">  Uncontrolled Components |
| <input type="checkbox">  React vs other libraries | <input type="checkbox">  Component Life-Cycle  |
| <input type="checkbox">  Virtual DOM  | <input type="checkbox">  Forms |
| <input type="checkbox">  JSX | <input type="checkbox">  Building Apps |
| <input type="checkbox">  Precompiled JSX | <input type="checkbox">   Introduction to Flux
| <input type="checkbox">  Properties & State | <input type="checkbox">  Introduction to Redux |
| <input type="checkbox">  Reusable Components  | <input type="checkbox">  Related React Tools |
| <input type="checkbox">  Compositions | <input type="checkbox">  React Router |
| <input type="checkbox">  Events | <input type="checkbox">  Testing React Components |
| <input type="checkbox">  Controlled Components| <input type="checkbox">  Testing Redux Reducers |

---

#### PluralSight React Skills Assessment
15 minute test of your proficiency in React.  Should be able to take once with 1 redo.

<a target="_ref" href="https://www.pluralsight.com/paths/react">https://www.pluralsight.com/paths/react</a>

---
### Congratulations, you are now all React and Redux Developers!

<a target="_di" href="http://developintelligence.com"><img src="http://www.developintelligence.com/sites/all/themes/diresponsive/images/Develop-Intelligence-logo-f.png">
</a>
<br>
<a target="_git_react" href="https://davidmarsland.github.io/react-spike/">https://davidmarsland.github.io/react-spike/</a>
### Thanks, please fill out course eval now, your comments are greatly appreciated!

