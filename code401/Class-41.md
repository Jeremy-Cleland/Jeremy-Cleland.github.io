# Class 41 Reading Notes | React Native

## [getting started with React native](https://facebook.github.io/react-native/docs/getting-started)

- Q: Name three Core Components of React Native and describe what they do.

  - A:
    - `<View>`:  A container that supports layout with flexbox, style, some touch handling and accessibility contorls.
    - `<Text></Text>`: Displays styles and neasts strings of text and even handles touch events.
    - `<ScrollView>`: A generic scrolling container that can contains multiple comonents.

- Q: What problem does React Native solve (why call it native)?

  - A: At runtime, React Native creates the corresponding Android and iOS views for those components. Because React Native components are backed by the same views as Android and iOS, React Native apps look, feel, and perform like any other apps. We call these platform-backed components Native Components.

- Q: What are the building blocks of a React Native app? How does that compare to a React app?

  - A: React Components, Community Components, Core Components, and my Native Components. 

## [expo](https://expo.io/)

- Q: What solution does expo provide?

  - A: Build one project that runs natively on all your users' devices


- Q: Expo tries to manage as much of the complexity of building apps as possible, which is why we call it the ____ workflow.

  - A: The Expo managed workflow provides a shared native runtime so you don't write native code, you focus on writing your React app in JavaScript. You don't have to worry about Android or iOS specific settings, or even opening up Xcode. Managed Expo projects have their own workflow including Expo CLI (a command line interface) to make developing and deploying easy.

- Q: What is the difference between React Native and Expo?

  - A: Expo extends the React Native platform by offering additional, battle-tested modules that are maintained by the team. This means you're spending less time configuring and more time building.

## [expo snack](https://snack.expo.io/)

- Q: Checkout this tool. What does snack allow you to do?

  - A: A live IDE for a Expo project

## [ejecting](https://docs.expo.io/versions/latest/expokit/eject)

- Q: What does “eject” mean within the context of Expo?

  - A: Ejecting in Expo us when you exit the standard Expo development environment, where you do not have to deal with build configuration or native code.

- Q: When should you not eject?

  - A: When you don't want to deal with build configuration or native code.

- Q: Why might you choose to eject?

  - A: Develop in Xcode and Android Studio

## Things I want to know more about
