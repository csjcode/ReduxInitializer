# ReduxInitializer
Experiments with Authentication in React Redux, Higher Order Components &amp;

From the Advanced React course

33 - What is a Higher Order Component (HOC)? 3:06  

* Installed redux simplestarter  
* npm install
* Combine regular Component and HOC = ComposedComponent (enhanced, wrapping functionality around Component)

34 - Connect and Provider 5:49  

In app.js import connect (redux) and mapStateToProps

35 - Authentication HOC Overview 4:19  

Resources Component is going to be wrapped with authentication check (HOC)

* ResourceList Component + require_auth HOC = ComposedComponent (checks authentication status before rendering)

36 - Header Setup 6:54  

Create Header Component with links

37 - React Router Setup 7:36  

Setup routes for links

38 - Authentication Reducer 7:05  

Change the Sign In/Out button

* Call action creator with boolean flip.

* types.js - change_auth
* index.js - export to authenticate (include type/payload)
* authentication.js reducer -give default false state

39 - Action Creator Hookup 8:04  

40 - Authentication Higher Order Component 4:57  

41 - HOC Scaffold Code 9:09  

42 - Nesting Higher Order Components 4:48  

43 - Accessing React Router on Context 5:30  

44 - Class Level Properties 2:12  

45 - Handling HOC Edge Cases 5:03  

46 - Higher Order Components Review 3:05  
