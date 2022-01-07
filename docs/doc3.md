---
id: doc3
title: Redux
sidebar_label: Redux
---

## Axios

- Axios is **promise-based**, which gives you the ability to take advantage of JavaScript’s **async and await** for more readable asynchronous code.
- Axios is a **library** that **helps us make http requests to external resources**.
- In our React applications we often need to retrieve data from external APIs so it can be displayed in our web pages. Axios uses methods like **get()** and **post()** that perform http GET and POST requests for retrieving or creating resources. e.g.:

```javascript
export const getData = (data1, dat2) => {
  return axios
    .get(`https://localhost:30001/v1/${data1}/${dat2}.workingData`)
    .then((response) => response)
    .catch((error) => error.response);
};
```

To install redux give command **npm install redux react-redux**

## Working of Redux

![alt text](/img/redux/1.png)

a) If `<Component>` want to get data from central data store then it need to subscribe it.
E.g.
![alt text](/img/redux/2.png)

Here component will dispatch an action which will describe the type and payload.
b) Below is an example of action class.
![alt text](/img/redux/3.png)

```javascript
import axios from "axios";
```

![alt text](/img/redux/4.png)

Axios is a library that helps us make http requests to external resources.

In our React applications we often need to retrieve data from external APIs so it can be displayed in our web pages.

Axios uses methods like get() and post() that perform http GET and POST requests for retrieving or creating resources.

c) Then we will pass that action to reducer. Eg. **const reducer = (state,action) => {}**

**Reducer** will then update central data store and no one else can do it.
![alt text](/img/redux/5.png)

**Remember**: According to convention type: “” should be all in caps. It won’t give any error if we don’t give it in caps (all capital).

d) Now we will fetch store data in `<Component />` from reducer by using **useSelector** in our `<Component />`
![alt text](/img/redux/6.png)

Here **reducerName** is reducer name given by the user.

e) Changes needs to be done in index.js inside src folder.
![alt text](/img/redux/7.png)
![alt text](/img/redux/8.png)
