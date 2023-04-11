## getting started with react native

Name three Core Components of React Native and describe what they do.
Three Core Components of React Native
View - A container that supports layout with flexbox, style, some touch handling, and accessibility controls.
Text - Displays, styles, and nests strings of text and even handles touch events.
Image - Displays different types of images, including network images, static resources, temporary local images, and images from local disk, such as the camera roll.

What problem does React Native solve (why call it native)?
React Native allows you to build native mobile apps using JavaScript and React. It uses the same design as React, letting you compose a rich mobile UI from declarative components.
What are the building blocks of a React Native app? How does that compare to a React app?
The building blocks of a React Native app are components. Components are the fundamental building blocks of any React Native app. You start with a small number of built-in components like View and Text, and then you compose and customize them to build the interfaces you need.

## expo

What solution does expo provide?
 It provides a number of features that make it easier to build apps, including a command line interface, a development server, and a platform for hosting your app.

Expo tries to manage as much of the complexity of building apps as possible, which is why we call it the Bare workflow.

What is the difference between React Native and Expo?
React Native is a framework for building native apps using JavaScript and React. Expo is a set of tools built around React Native to help you build native iOS and Android apps using JavaScript and React.

## expo snack

Checkout this tool. What does snack allow you to do?
Expo snack allows you to write and run React Native code right in your browser.

## ejecting

What does “eject” mean within the context of Expo?
Ejecting means to remove the Expo SDK from your project and use the underlying React Native build system instead.
When should you not eject?
You should not eject if you want to continue using Expo services, such as the Expo client app, Expo CLI, and Expo SDK.
Why might you choose to eject?
You might choose to eject if you want to use a native module that is not included in the Expo SDK.