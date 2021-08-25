# React Native
 
 ## Review, Research, and Discussion

 * **Compare and Contrast Redux Toolkit with Redux “Ducks”**

Ducks appears to be a method to modularize your redux code, making it more scalable and understandable. The Redux toolkit allows you to build up your Redux app with specific methods, making it easier to get your project up and running quickly.

 * **What is the principle advantage of Redux Toolkit?**

This is the way Redux recommends that you set up a Redux app. It includes a bunch of useful APIs, and it helps simplify Redux code.

## Document the following Vocabulary Terms

* **redux toolkit slices:** There is a redux toolkit function called createSlice() that takes in an initial state, an object of reducer functions, and a 'slice name', and it generates action creators and action types corresponding to the reducers and state.

* **namespace:** You can create namespaces for action creators in Redux. This allows multiple instances of components to co-exist with independent space.

## Preparation Materials


### getting started with react native
Welcome to the beginning of your React Native adventure! If you're looking for instructions on how to set up an environment, they've been relocated to their own area. Read on for an overview of the documentation, Native Components, React, and more!
React Native is used by a wide range of users, from experienced iOS developers to React novices to folks who are just starting started with programming. These documents were created for all types of learners, regardless of their degree of expertise or background.



* Learn the Basics

React Native is similar to React, except instead of using web components as building blocks, it utilizes native components. To comprehend the fundamental structure of a React Native app, you must first comprehend some of the fundamental React principles, such as JSX, components, state, and props. Even if you're already familiar with React, you'll need to learn certain React-Native-specific information, such as native components. This lesson is for everyone, whether you've worked with React before or not.

* What’s going on here?
* First of all, we need to import React to be able to use JSX, which will then be transformed to the native components of each platform.
* On line 2, we import the Text and View components from react-native

### Ejecting to ExpoKit

* **What is this for?**

If you created an Expo project and you want a way to add custom native modules, this guide will explain how to use ExpoKit for that purpose.
Normally, Expo apps are written in pure JS and never "drop down" to the native iOS or Android layer. This is core to the Expo philosophy and it's part of what makes Expo fast and powerful to use.
However, sophisticated developers may want native capabilities beyond what Expo provides out of the box in some instances. The most typical scenario is when a project requires a Native Module that React Native Core or the Expo SDK do not support.
Expo allows you to eject your pure-JS project from the Expo iOS/Android clients in this scenario, leaving you with native projects that you can access and develop using Xcode and Android Studio. Because those projects will be dependent on ExpoKit, everything you've already developed will continue to function normally.
We call this "ejecting" because you still depend on the Expo SDK, but your project no longer lives inside Expo Go. You control the native projects, including configuring and building them yourself.

* **Should I eject to ExpoKit?**

You might want to eject if:
Your Expo project needs a native module that Expo doesn't currently support. We're always expanding the Expo SDK, so we hope this is never the case. But it happens, especially if your app has very specific and uncommon native demands.
You should not eject if:
All you have to do now is publish your app on the App Store or Google Play. In such situation, Expo can create binaries for you. If you eject, we will no longer be able to create for you automatically.
You are apprehensive about developing native code. You'll need to handle Xcode and Android Studio projects if your program is ejected.
Expo's easy React Native updates are appealing to you. Breaking changes in React Native may effect your project differently after it is ejected, and you may need to find out what they are for your specific circumstance.
You require Expo's push notification services. After ejecting, since Expo no longer manages your push credentials, you'll need to manage your own push notification pipeline.
You rely on asking for help in the Expo community. In your native Xcode and Android Studio projects, you may encounter questions which are no longer within the realm of Expo.
