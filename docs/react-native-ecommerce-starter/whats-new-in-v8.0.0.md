#  What's new in 8.0.0

#### New Features

*	Integrated ESlint, linter tool for identifying and reporting on patterns in javascript.
*	Integrated Husky
	*	Prevents bad commit, push and more
	*	Builds precommit and other git hooks to run commands within your package.json before a commit is allowed.
*	Integrated Prettier
	*	Reformats and reindents bookmarklet, ugly javascript code.
	*	Removes all original styling and ensures that all outputted code conforms to a consistent style.

#### Upgraded Features

*	Integrated React Navigation
	*	Navigators allow you to define your application's navigation structure. 
	*	Navigators also render common elements such as headers and tab bars which you can configure.
	*	React Navigation includes the following functions to help you create navigators:
		*	StackNavigator
		*	TabNavigator
		*	DrawerNavigator
*	Upgraded NativeBase from 2.1.0-rc.2 to 2.3.1
*	Upgraded React from 15.4.0 to 16.0.0-alpha.12
*	Upgraded React Native from 0.42.3 to 0.48.4
*	Upgraded Expo from 15.1.0 to 21.0.2
*	Other upgraded packages:
    *   color: 0.11.3 to 1.0.3
	*	react-redux: 4.4.5 to 5.0.5
	*	redux: 3.5.2 to 3.7.2
	*	redux-persist: 3.2.2 to 4.10.0
    *   redux-thunk: 2.1.0 to 2.2.0
    *   remote-redux-devtools: 0.3.3 to 0.5.0
	*	remote-redux-devtools-on-debugger: 0.4.6 to 0.8.0
*   Upgraded dev dependencies
*   UI fixes
*	Modified structure of the project more efficiently.
*   Removed NB 0.x theme and ejected new theme from NativeBase 2.3.1
*   Removed unused packages
