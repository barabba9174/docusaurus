---
id: doc6
title: Testing
sidebar_label: Testing
---

## Testing React with Jest and Enzyme

### Jest

Jest is a JavaScript unit testing framework, used by Facebook to test services and React applications.

CRA comes bundled with Jest; it does not need to be installed separately.

Jest acts as a **test runner**, **assertion library**, and **mocking library**.

Jest also provides **Snapshot testing**, the ability to create a rendered ‘snapshot’ of a component and compare it to a previously saved ‘snapshot’. The test will fail if the two do not match. Snapshots will be saved for you beside the test file that created them in an auto-generate `__snapshots__ `folder. An example snapshot could be as simple as: 

![alt text](/img/picture4.png)
 
Snapshot testing must be complimented with in browser testing and looking at the snapshot created when creating the initial snapshots, to ensure that the snapshot reflects the intended outcome.

### Enzyme

Enzyme is a JavaScript Testing utility for React that makes it easier to assert, manipulate, and traverse your React Components’ output.

Enzyme, adds some great additional utility methods for **rendering a component** (or multiple components), **finding elements**, and **interacting with elements**.

It must be installed in addition to tools already bundled with CRA.

### Jest and Enzyme

*	Both Jest and Enzyme are specifically designed to test React applications, Jest can be used with any other Javascript app but Enzyme only works with React.
*	Jest can be used without Enzyme to render components and test with snapshots, Enzyme simply adds additional functionality.
*	Enzyme can be used without Jest, however Enzyme must be paired with another test runner if Jest is not used.

As described, we will use:

*	**Jest** as the test runner, assertion library, and mocking library
*	**Enzyme** to provide additional testing utilities to interact with elements.

### Creating a test file
*	Files with `.test.tsx` suffix.
*	It is convention to put each test file next to the code it is testing. This makes semantic sense, and also means relative paths are shorter ( .`/MyComponent` vs `../../MyComponent` etc).

An example of this could be this `PlanFeatureUnit.test.tsx` file:

![alt text](/img/picture5.png)

### Mount, Shallow, Render

`import { mount, shallow, render } from ‘enzyme';`

In order to have a component to test one of the above must be used, as in the example further above.

#### Mounting

*	Full DOM rendering including child components
*	Ideal for use cases where you have components that may interact with DOM API, or use React lifecycle methods in order to fully test the component
*	As it actually mounts the component in the DOM. unmount() should be called after each tests to stop tests affecting each other
*	Allows access to both props directly passed into the root component (including default props) and props passed into child components

#### Shallow

*	Renders only the single component, not including its children. This is useful to isolate the component for pure unit testing. It protects against changes or bugs in a child component altering the behaviour or output of the component under test
*	As of Enzyme 3 `shallow` components do have access to lifecycle methods by default
*	Cannot access props passed into the root component (therefore also not default props), but can those passed into child components, and can test the effect of props passed into the root component. This is as with `shallow(<MyComponent />)`, you're testing what `MyComponent` renders - not the element you passed into `shallow`

#### Render

*	Renders to static HTML, including children
*	Does not have access to React lifecycle methods
*	Less costly than `mount` but provides less functionality

#### Events

The Enzyme API has several ways to simulate events or user interactions. If you are wanting to test interacting with a child component then the `mount` method can be used.

#### Mock functions

You may simply want to check that a function passed as props is successfully called.

### Jest and Enzyme: How Are They Similar?
Both Jest and Enzyme provide powerful tools for testing React UIs. Each is a unit testing tool that empowers you to ensure that the user interface of your web application looks and behaves as expected. Both are actively developed and easily installed using Node Package Manager. Each has a thriving community of developers who can help out someone new to the library if they find themselves in a tight spot.


### Jest and Enzyme: How Are They Different?
To get the most obvious difference out of the way, Jest and Enzyme serve slightly different purposes. Jest is a fully featured testing framework. That means that it doesn’t just help you test React components.

Jest provides a test-running script that will run all your tests, as well as an entire assertion library. Jest works great with React, but it’s not limited just to React. If you’re building your web application entirely in JavaScript, for instance using NodeJS to build your server, Jest allows you test your whole application with one test library.

Enzyme serves a different purpose. Instead of serving as a full testing library, Enzyme is a library that makes testing React components specifically easier. It integrates with many full testing libraries, including Jest. If you’re using React in your application, it might make sense to use Enzyme and Jest together to automatically test your UI.

### Jest and Enzyme: How Can They Work Together?
Like we noted before, Enzyme needs a testing library to provide a foundation for the tests it generates. Many people choose to use Jest and Enzyme together to test their React web applications. They use Jest as a test runner and assertion library, then use Enzyme to build the tests for their UI.

This results in slimmer, cleaner testing code that’s also easier to debug when a test breaks. Developers which use these tools together find them to be a powerful combination that makes testing UIs simple. Experienced developers then hook these tests into an automated testing framework that runs these tests on each commit to source code.

Using all of these tools in concert means developers find bugs faster. This is a significant step toward software maturity for teams writing complicated applications. Developers have confidence their code works the way it should. They’re confident it doesn’t introduce bugs.

QA engineers are able to focus on testing more complicated cases, instead of looking for regressions in the UI. Customers are happier because software comes faster and works the way it’s supposed to when it launches.

In the end, using tools like Jest and Enzyme for what they’re best at makes all of your software better. Even though the software we write grows more complex by the day, that doesn’t mean it needs to be harder to write. We just need to use the right tools to manage that complexity.
