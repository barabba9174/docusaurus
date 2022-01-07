---
id: doc5
title: NextJs 
sidebar_label: NextJs
---

## Next.js is a React Framework.

Next.js aims to have best-in-class developer experience and many built-in features, such as:

*	Page-based routing system (with support for dynamic routes)
*	Pre-rendering, both static generation (SSG) and server-side rendering (SSR) are supported on a per-page basis
*	Automatic code splitting for faster page loads
*	Client-side routing with optimized prefetching
*	Built-in CSS and Sass support, and support for any CSS-in-JS library
*	Development environment with Fast Refresh support (means when you make changes to files, Next.js automatically applies the changes in the browser almost instantly. No refresh needed. This will help you iterate on your app quickly.)
*	API routes to build API endpoints with Serverless Functions
*	Fully extendable

Next.js is used in tens of thousands of production-facing websites and web applications, including many of the world's largest brands.

## Software needed to start working on Next JS:

*	**Node.js** version **10.13** or later
*	Text Editor **(VS Code)** and terminal app (if you are on Windows, we recommend downloading **Git** for Windows and use **Git Bash** that comes with it)

Once you clone **btplc** repositories you will get a template where you have to select Next JS

![alt text](/img/picture1.png)
 
## Working with Next JS:

*	**pages/index.js** is the main index file in Next JS
*	In Next.js, a **page is a React Component** exported from a file in the **pages directory**.
Pages are associated with a route based on their file name. 

For example, in development:

* **pages/index.js** is associated with the **/ route**.
*	**pages/feeds/first-feeds.js** is associated with the **/feeds/first-feeds** route.

This is how you can create different pages in Next.js.
Simply create a JS file under the pages directory, and the path to the file becomes the URL path.

*	In Next.js, when linking between pages on websites we use the **Link Component** from **next/link** to wrap the `<a>` tag. 
`<Link>` allows you to do client-side navigation to a different page in the application.
Just import the Link component from next/link by adding this line at the top:
import Link from 'next/link'

![alt text](/img/picture2.png)

As we can see, the Link component is similar to using `<a>` tags, but instead of  -->
`<a href="…">`, we use `<Link href="…">` and put an `<a>` tag inside.

*	Next.js has built-in support for CSS and Sass.
To use CSS Modules, the CSS file name must end with **.module.css**.
Import the CSS file into the component you want to style and assign a name to it, like styles
use styles.container as the className

![alt text](/img/picture3.png)
 
In Next.js, you can add global CSS files by importing them from pages/_app.js. You cannot import global CSS anywhere else.
The reason that global CSS can't be imported outside of pages/_app.js is that global CSS affects all elements on the page.

*	For learnings on Pre-rendering and Data Fetching, please go to [link](https://nextjs.org/learn/basics/data-fetching)
*	For learnings on API Routes, please go to [link](https://nextjs.org/learn/basics/api-routes)