---
id: doc7
title: React
sidebar_label: React
---

## Introduction to DOM

- DOM is a programming interface or API
- DOM stands for Document Object Model
- DOM represents the contents of XML or HTML document as tree structure internally in the memory and be used with programming languages like JavaScript
- Using DOM we can easily access, read and update the contents of a document

![alt text](/img/DOM.png)

## Analogy

A library is like going to Ikea. You already have a home, but you need a bit of help with furniture. You don’t feel like making your own table from scratch. Ikea allows you to pick and choose different things to go in your home. You are in control.

A framework, on the other hand, is like building a model home. You have a set of blueprints and a few limited choices when it comes to architecture and design. Ultimately, the contractor and blueprint are in control. And they will let you know when and where you can provide your input.

## React basics

- React is a JavaScript library for building user interfaces.
- React is not a framework.
- React was first designed by Jorden Walke, a software engineer at Facebook.
- It was first deployed for Facebook News Feed around 2011. And in 2013 React was open sourced at JS conference.
- React has component based approach. We can say that every application you will develop in React will be made up of pieces called components.

## Hooks

React Hooks was introduced in React 16.8 which let you use State and other React features without using Class component.

Hooks rules:

- Always write it inside the component or function.
- Component name must be PascalCase (first letter should be uppercase)
- We can directly import or we can directly write it using React.hookName .
- Do not call hooks inside loop, condition, or nested functions.

## Example code

### Form submit:

![alt text](/img/form-submit1.png)

![alt text](/img/form-submit2.png)

### useEffect Cleanup function

![alt text](/img/useeffect-cleanup.png)

### Get data using useEffect

![alt text](/img/get-data.png)

### Uncontrolled form, ref and useRef

It is like useState only and it preserve the value and no re-render.

![alt text](/img/uncontrolled.png)

## UseReducer Hook

![alt text](/img/usereducer.png)

The **useReducer** Hook is the better alternative to the **useState** hook and is generally more preferred over the **useState** hook when you have complex state-building logic or when the next state value depends upon its previous value or when the components are needed to be optimized.

**reducer()** above is always a pure function (i.e. Given a set of inputs, it should always return the same output. No surprises, side effects, API calls, mutations.) and should always **return** something.

## UseContext Hook

This hook makes it easy to pass data throughout your app without manually passing props down the tree. Here we do not do props drilling.

![alt text](/img/usecontext1.png)

![alt text](/img/usecontext2.png)

![alt text](/img/usecontext3.png)
