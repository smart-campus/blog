---
layout: post
title:  "Building blocks to learning React Native"
author: airesh_bhat
categories: [React, React native, App development]
image: 
featured: true
hidden: true
---

An exhaustive list of resource to learn React and React native.

## ReactJS
ReactJS has revolutionized the way in which websites are built. The concept of components being used as building blocks, an analogy to an atom being the basic building block(The logo for React), has eased the life of many developers. This article aims to provide you links to help you get started with ReactJS and get coding. 
Before getting started, I will be sharing a few basic articles on web design and Javascript as it is required to get started with ReactJS.

### Step 1: A review of HTML
A very basic read up of HTML from [Level Up Tutorials](https://www.leveluptutorials.com/tutorials/html5-tutorials "Level up tutorials") to get started. For those who already know HTML, [this](https://www.w3schools.com/html/ "w3schools") can be used as a reference.
PS: A short [video](https://www.youtube.com/watch?v=Z3HGJsNLQ1E "CSS guide") for some help with CSS

### Step 2: A review of Javascript Basics
- [JavaScript Syntax](https://www.w3schools.com/js/js_syntax.asp)
- [Variables](https://www.w3schools.com/js/js_variables.asp)
- [Data Types](https://www.w3schools.com/js/js_datatypes.asp)
- [Operators](https://www.w3schools.com/js/js_operators.asp)
- [Arithmetic Operations](https://www.w3schools.com/js/js_arithmetic.asp)
- [Assignment](https://www.w3schools.com/js/js_assignment.asp)
- [JS Output](https://www.w3schools.com/js/js_output.asp)
- [Objects](https://www.w3schools.com/js/js_objects.asp)
- [Loop - Multiple ways to loop through an Array in jQuery JavaScript](http://www.yogihosting.com/multiple-ways-loop-array-jquery-javascript/)
- [Break & Continue](https://www.w3schools.com/js/js_break.asp)

### Step 3: Javascript ES6 essential concepts
- [Arrow Functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions)
- [Rest Parameters](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/rest_parameters)
- [Getter](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/get)
- [Setter](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/set)
- [Async function](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/async_function)
- [Generators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Iterators_and_Generators)

PS: The above links are meant only as reference. In any case you can't seem to understand what's happening in someone's code, hopefully the links above will be able to guide you.

### Step 4: ReactJS(Finally!!!)
This [video](https://www.youtube.com/watch?v=qrsle5quS7A&list=PL55RiY5tL51rrC3sh8qLiYHqUV3twEYU_) series is a short but sweet compilation on how to get started with React. This is a must see for anyone who wants to code in React. It also talks about using React Redux(used to handle data in React applications, which we use in our codebase).
An even shorter introduction to [React](https://www.youtube.com/watch?v=3HMtarQAt3A&authuser=0).

### Step 5: Advanced Topics
- [React Hooks](https://reactjs.org/docs/hooks-intro.html#motivation) was introduced by Facebook in the recent past. This update to ReactJS was accepted very grandly by the React community. This is a must know for anyone learning React as it is the future of ReactJS.
- Design Principles: 
    * Application Architecture: We use a part of the MVVM architecture to structure our code. Read [this]( https://medium.cobeisfresh.com/level-up-your-react-architecture-with-mvvm-a471979e3f21) article to understand what MVVM architecture is.
    * Higher Order Components: Understanding [Higher Order Components(HOC)](https://reactjs.org/docs/higher-order-components.html) in react
- Flow Typing: Using strict syntax to reduce buggy code with the help of [flow](https://flow.org).
- [Structuring a Redux application](https://jaysoo.ca/2016/02/28/organizing-redux-application/)


PS: For those who want to understand what's going on under the hood, [this](https://www.mattgreer.org/articles/react-internals-part-one-basic-rendering/) can give you an extremely wonderful understanding of the same.

## React Native
React Native has changed the way apps are being developed. Developing apps in React Native helps us create apps for both platforms, iOS and Android at the same time. With almost 90% of the codebase being same for both the apps, the developer time used for making apps has reduced significanltly thanks to React Native. In this article I will provide articles to help you get started with React Native and also provide links on the good practices used by the community.
React Native will require you to know the Javascript topics provided in the previous section(ReactJS basics).

### Step 1: React Native Basics
[This video](https://www.youtube.com/watch?v=6ZnfsJ6mM5c) covers a basic knowledge of React Native setup and development.

### Step 2: React Native Navigation
Our code base uses the library [react-native-navigation](https://github.com/wix/react-native-navigation) for handling native navigation. [This video](https://www.youtube.com/watch?v=osMg869VwFY&list=PLy9JCsy2u97nzztNpiBsJLQF-sixWvMEO) covers setting up and understanding the basic use of the library.

### Step 3: Data Handling Princicples
A proper understanding of Redux is required for any React Native application.
  * The [documentation](https://redux.js.org/introduction/getting-started) has a neat example on how Redux works and how to set it up in an application.
  * Another [source](http://teropa.info/blog/2015/09/10/full-stack-redux-tutorial.html) for understanding Redux in a full stack application.
  * [Redux thunk](http://teropa.info/blog/2015/09/10/full-stack-redux-tutorial.html): Handling asynchronous actions in a React application along with Redux.
  * [Reselect](https://github.com/reduxjs/reselect):
    * An [article](https://medium.com/@parkerdan/react-reselect-and-redux-b34017f8194c) to understand what Reselect actually is and does.
    * and a [video](https://www.youtube.com/watch?v=XCQ0ZSr-a2o) to help you visualise what is happening.
  * Finally coming to the [best practices](https://medium.com/@kylpo/redux-best-practices-eef55a20cc72) that are used in a Redux application.


### Step 4: Design
  * [FlexBox](http://flexboxfroggy.com/) design in React Native. To understand how structuring is done inside the app.
  * Application Architecture: We use a part of the MVVM architecture to structure our code. Read [this]( https://medium.cobeisfresh.com/level-up-your-react-architecture-with-mvvm-a471979e3f21) article to understand what MVVM architecture is.
  * Design Libraries to help ease the overall design of a React Native application. [react-native-extended-stylesheet](https://github.com/vitalets/react-native-extended-stylesheet)
  * Higher Order Components: Understanding [Higher Order Components(HOC)](https://reactjs.org/docs/higher-order-components.html) in react
  * Flow typing: Using strict syntax to reduce buggy code with the help of [flow](https://flow.org).


