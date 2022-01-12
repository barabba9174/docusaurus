---
id: doc9
title: Front-End Handbook
sidebar_label: Front-End Handbook
---

![](/img/fe-handbook/Aspose.Words.5c5312d5-ece8-4713-b1e0-a1d4939ed601.001.png)


This is a handbook that anyone could use to learn about the practice of front-end development. It broadly outlines and discusses the practice of front-end engineering: how to learn it and what tools are used when practicing it.

The content of the handbook favors web technologies (HTML, CSS, DOM, and JavaScript, Web Accessibilty, JSON, ES6, React JS, Tool Component Library) and those solutions that are directly built on top of these open technologies. 

The intention is to release an update to the content understandable. The handbook is divided into three parts.

<!-- ## **Part I. The Front-End Practices**

## **Part II: Learning Front-End Development**

## **Part III: Front-End Development Tools**

## **Part IV: BT Tool Component Library** -->

## **Intro**
### **What Is a Front-End Developer?**
Front-end web development, also known as client-side development is the practice of producing HTML, CSS and JavaScript for a website or Web Application so that a user can see and interact with them directly. The challenge associated with front end development is that the tools and techniques used to create the front end of a website change constantly and so the developer needs to constantly be aware of how the field is developing.

The objective of designing a site is to ensure that when the users open up the site they see the information in a format that is easy to read and relevant. This is further complicated by the fact that users now use a large variety of devices with varying screen sizes and resolutions thus forcing the designer to take into consideration these aspects when designing the site. They need to ensure that their site comes up correctly in different browsers (cross-browser), different operating systems (cross-platform) and different devices (cross-device), which requires careful planning on the side of the developer.

[*https://en.wikipedia.org/wiki/Front-end_web_development*](https://en.wikipedia.org/wiki/Front-end_web_development)

### **HTML, CSS, & JavaScript:**

![](/img/fe-handbook/Aspose.Words.5c5312d5-ece8-4713-b1e0-a1d4939ed601.008.jpeg)A front-end developer architects and develops websites and applications using web technologies (i.e., HTML, CSS, DOM, and JavaScript), which run on the [web platform ](https://en.wikipedia.org/wiki/Open_Web_Platform)or act as compilation input for non-web platform environments (i.e., [NativeScript](https://www.nativescript.org/)).


Typically, a person enters into the field of front-end development by learning to develop HTML, CSS, and JS code, which runs in a [web browser](https://en.wikipedia.org/wiki/Web_browser), [headless browser](https://en.wikipedia.org/wiki/Headless_browser), [WebView](http://developer.telerik.com/featured/what-is-a-webview/), or as compilation input for a native runtime environment. These four run times scenarios are

explained below.



### **Web Browsers**

A web browser is software used to retrieve, present, and traverse information on the [WWW](https://en.wikipedia.org/wiki/World_Wide_Web). Typically, browsers run on a desktop or laptop computer, tablet, or phone, but as of late a browser can be found on just about anything (i.e, on a fridge, in cars, etc.).

The most common web browsers are (shown in order of most used first):

* [Chrome](http://www.google.com/chrome/)
* [Internet Explorer ](https://en.wikipedia.org/wiki/Internet_Explorer)(Note: not [Edge](http://dev.modern.ie/), referring to IE 9 to IE 11)
* [Firefox](https://www.mozilla.org/firefox/)
* [Safari](http://www.apple.com/safari/)

### **Headless Browsers**

Headless browsers are a web browser without a graphical user interface that can be controlled from a command line interface programmatically for the purpose of web page automation (e.g., functional testing, scraping, unit testing, etc.). Think of headless browsers as a browser that you can run from the command line that can retrieve and traverse web pages.

The most common headless browsers are:

* [PhantomJS](http://phantomjs.org/)
* [slimerjs](http://slimerjs.org/)
* [trifleJS](http://triflejs.org/)

### **Webviews**

[Webviews ](http://developer.telerik.com/featured/what-is-a-webview/)are used by a native OS, in a native application, to run web pages. Think of a [webview ](http://developer.telerik.com/featured/what-is-a-webview/)like an iframe or a single tab from a web browser that is embedded in a native application running on a device (e.g., [iOS](https://developer.apple.com/library/ios/documentation/UIKit/Reference/UIWebView_Class/), [android](http://developer.android.com/reference/android/webkit/WebView.html), [windows](https://msdn.microsoft.com/library/windows/apps/windows.ui.xaml.controls.webview.aspx)).

The most common solutions for [webview ](http://developer.telerik.com/featured/what-is-a-webview/)development are:

* [Cordova ](https://cordova.apache.org/)(typically for native phone/tablet apps)
* [NW.js ](https://github.com/nwjs/nw.js)(typically used for desktop apps)
* [Electron ](http://electron.atom.io/)(typically used for desktop apps)
* The days of [battling ](https://kangax.github.io/compat-table/es6/)[inconsistent browser API's](https://html5test.com/results/desktop.html) are almost behind us due to a massive decline in usage and development for [older versions of IE](https://www.netmarketshare.com/browser-market-share.aspx?qprid=2&qpcustomd=0).
* Most everyone realized they will have to have a [multi-device strategy ](http://www.intel.com/content/dam/www/public/us/en/images/iot/guide-to-iot-infographic.png)plan when developing for the web
* More developers, from other languages, continue to flood the JavaScript space bringing[ with them things like type checking and an obsession with class syntax and OOP concepts.](https://www.typescriptlang.org/)
* [Front-end devs are introduced to Hot Module replacement techniques and time travel debugging.](https://code-cartoons.com/hot-reloading-and-time-travel-debugging-what-are-they-3c8ed2812f35#.ezlpqez1i)
* More waiting for a native [JavaScript browser module loader](https://whatwg.github.io/loader/).
* [Enforcing CSS ](https://css-tricks.com/stylelint/)and [JavaScript style conventions ](https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb)becomes more important (considering ES3 to ES6 code and CSS pre-processors syntactical variations)
* [A small but noticeable number of developers are starting to choose Elm over JavaScript.](https://www.brianthicks.com/post/2016/04/22/state-of-elm-2016-results/)
* [TypeScript ](https://www.typescriptlang.org/)gets some serious use and fanboys.
* [http://aurelia.io/ ](http://aurelia.io/)becomes the [smart choice for enterprise developers ](https://www.youtube.com/watch?v=6I_GwgoGm1w&t=3315s)(i.e. support!). 
* [Webpack ](https://webpack.js.org/configuration/)gets its act [together ](https://opencollective.com/webpack)and solidifies is position over the superior 
* [JSPM ](https://www.pluralsight.com/courses/javascript-systemjs-jspm)solution. 
* [HTTPS, yeah, we're serious about that.](https://developers.google.com/web/updates/2016/10/avoid-not-secure-warn)
* [BASH ](https://msdn.microsoft.com/en-us/commandline/wsl/about) on windows happens.
* [notifications API ](https://developer.mozilla.org/en-US/docs/Web/API/Notifications_API/Using_the_Notifications_API)gets used and abused for chrome users, but only after you give it permission.
* [Firebug officially dead](https://github.com/firebug/firebug).
* CSS [20 years young ](https://www.w3.org/Style/CSS20/)in 2016. 
* [Immutability ](https://facebook.github.io/immutable-js/)concepts run rapid.

### **In future expect...**

* [Web Assembly](http://webassembly.org/), might just peak.
* `import` might just be [usable ](https://github.com/tc39/proposal-dynamic-import#example)in `<script></script>`
* Universal JavaScript solutions will continue to rise that pay homage/respect to the days of [server delivered front-ends (i.e. html to the client)](https://github.com/zeit/next.js).
* Reactive programming continues to thrive in the JavaScript scene. (see MobX and RxJS).
* React, more so the concept, will dominate. React itself will be completely re-written (see [React Fiber](https://github.com/acdlite/react-fiber-architecture)) or evolve (see [Inferno](https://github.com/infernojs/inferno)).
* Angular found SEMVER so Angular 4 (even 5) is on the [roadmap ](https://www.youtube.com/watch?v=aJIMoLgqU_o&feature=youtu.be&t=6m12s)for 2017.
* A return to simple websites may happen, web 1.0 retro, but with the help of 2017 tools (i.e. [static site generation](https://github.com/vigetlabs/gulp-starter/tree/blendid))
* RESTful JSON APIs will get more competition (see [GraphQL](http://graphql.org/)) Could be a banner year for [Vue.js](https://vuejs.org/).
* [More devs will abandon traditional CMS solutions for static site generators & API CMS tools.](https://www.google.com/webhp?sourceid=chrome-instant&rlz=1C5CHFA_enUS712US713&ion=1&espv=2&ie=UTF-8&q=api%20cms)
* More people will move from Sass to [PostCSS ](http://postcss.org/)+ cssnext. Lots more HTTP2 and HTTPS.
* Web components will continue to lurk and wait for significant traction by developers that might never come to be.
* The no framework, framework, faction will gain momentum (see [Svelte](https://svelte.technology/blog/frameworks-without-the-framework/)).
* JavaScript will settle, and hopefully, CSS will erupt and everyone will cry fatigue until it settles.
* Hatred for apps store will grow, while the open web has no memory of wrong doing. Redux will continue to get stiff competition (see [mobx](https://mobx.js.org/)).
* YARN will win more users.

According to a[ State Of Frontend](https://tsh.io/state-of-frontend/#frameworks) survey, 77.2% of developers already used TypeScript and valued it over JavaScript. No matter whether they are working on old frameworks (i.e., Angular or React) or emerging ones (i.e., Dojo or Stencil), TypeScript improves their coding process and helps develop complex web applications seamlessly. 


## **Part I. The Front-End Practice**

### **Web Technologies Employed by Front-End Developers**
![](/img/fe-handbook/Aspose.Words.5c5312d5-ece8-4713-b1e0-a1d4939ed601.057.jpeg)

The following core web technologies are employed by front-end developers (consider learning them in this order):

1. Uniform Resource Locators (aka URLs)
1. Hypertext Transfer Protocol (aka HTTP)
1. Hyper Text Markup Language (aka HTML)
1. Cascading Style Sheets (aka CSS)
1. JavaScript Programming Language (aka ECMAScript 262)
1. JavaScript Object Notation (aka JSON)
1. Document Object Model (aka DOM)
1. Web APIs (aka HTML5 and friends or Browser APIs)
1. Web Content Accessibility Guidelines (aka WCAG) & Accessible Rich Internet Applications (aka ARIA)

These technologies are defined below with the relevant documentation and specifications. For a comprehensive list of all web related specifications have a look at [platform.html5.org](https://platform.html5.org/).



### **Hyper Text Markup Language (aka HTML)**

HyperText Markup Language, commonly referred to as HTML, is the standard markup language used to create web pages. Web browsers can read HTML files and render them into visible or audible web pages. HTML describes the structure of a website semantically along with cues for presentation, making it a markup language, rather than a programming language.

*— [Wikipedia*](https://en.wikipedia.org/wiki/HTML)*

Most relevant specifications / documentation:

* [All W3C HTML Spec](http://www.w3.org/standards/techs/html#w3c_all)
* [The elements of HTML from the Living Standard](https://html.spec.whatwg.org/multipage) [Global attributes](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes)
* [HTML 5.2 from W3C](http://w3c.github.io/html/)
* [HTML attribute reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes) [HTML element reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)

### **Cascading Style Sheets (aka CSS)**

Cascading Style Sheets (CSS) is a style sheet language used for describing the look and formatting of a document written in a markup language. Although most often used to change the style of web pages and user interfaces written in HTML and XHTML, the language can be applied to any kind of XML document, including plain XML, SVG and XUL. Along with HTML and JavaScript, CSS is a cornerstone technology used by most websites to create visually engaging webpages, user interfaces for web applications, and user interfaces for many mobile applications.

*— [Wikipedia*](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)*


### **Document Object Model (aka DOM)**
The Document Object Model (DOM) is a cross-platform and language-independent convention for representing and interacting with objects in HTML, XHTML, and XML documents. The nodes of every document are organized in a tree structure, called the DOM tree. Objects in the DOM tree may be addressed and manipulated by using methods on the objects. The public interface of a DOM is specified in its application programming interface (API).

*— [Wikipedia*](https://en.wikipedia.org/wiki/Document_Object_Model)*




### **JavaScript Programming Language (aka ECMAScript 262)**

JavaScript is a high level, dynamic, untyped, and interpreted programming language. It has been standardized in the ECMAScript language specification. Alongside HTML and CSS, it is one of the three essential technologies of World Wide Web content production; the majority of websites employ it and it is supported by all modern web browsers without plug-ins. JavaScript is prototype-based with first-class functions, making it a multi-paradigm language, supporting object-oriented, imperative, and functional programming styles. It has an API for working with text, arrays, dates and regular expressions, but does not include any I/O, such as networking, storage or graphics facilities, relying for these upon the host environment in which it is embedded.

*— [Wikipedia*](https://en.wikipedia.org/wiki/JavaScript)*


### **JavaScript Object Notation (aka JSON)**
c It is the primary data format used for asynchronous browser/server communication (AJAJ), largely replacing XML (used by AJAX). Although originally derived from the JavaScript scripting language, JSON is a language-independent data format. Code for parsing and generating JSON data is readily available in many programming languages. The JSON format was originally specified by Douglas Crockford. It is currently described by two competing standards, RFC 7159 and ECMA-404. The ECMA standard is minimal, describing only the allowed grammar syntax, whereas the RFC also provides some semantic and security considerations. The official Internet media type for JSON is application/json. The JSON filename extension is .json.

*— [Wikipedia*](https://en.wikipedia.org/wiki/JSON)*

Most relevant specifications:

* [Introducing JSON](http://json.org/) [JSON API](http://jsonapi.org/)

* [The JSON Data Interchange Format](http://www.ecma-international.org/publications/files/ECMA-ST/ECMA-404.pdf)

### **Web Content Accessibility Guidelines (aka WCAG) & Accessible Rich Internet Applications (aka ARIA)**
Accessibility refers to the design of products, devices, services, or environments for people with disabilities. The concept of accessible design ensures both “direct access” (i.e., unassisted) and "indirect access" meaning compatibility with a person's assistive technology (for example, computer screen readers).

*— [Wikipedia*](https://en.wikipedia.org/wiki/Accessibility)*

* [Accessible Rich Internet Applications (WAI-ARIA) Current Status](http://www.w3.org/standards/techs/aria#w3c_all) [Web Accessibility Initiative (WAI)](http://www.w3.org/WAI/)
* [Web Content Accessibility Guidelines (WCAG) Current Status](http://www.w3.org/standards/techs/wcag#w3c_all)


### **Front-End Dev Skills**

![](/img/fe-handbook/Aspose.Words.5c5312d5-ece8-4713-b1e0-a1d4939ed601.076.jpeg)

*Image source: [http://blog.naustud.io/2015/06/baseline-for-modern-front-end-developers.html*](http://blog.naustud.io/2015/06/baseline-for-modern-front-end-developers.html)*

Basic to advanced HTML, CSS, DOM, JavaScript, HTTP/URL, and browser skills are assumed for any type of front-end developer.

Beyond HTML, CSS, DOM, JavaScript, HTTP/URL, and browser development know-how, a front-end developer could be skilled in one or more of the following:

* Content Management Systems (aka CMS) Node.js
* Cross-Browser Testing Cross-Platform Testing Unit Testing
* Cross-DeviceTesting Accessibility / WAI-ARIA
* Search Engine Optimization (aka SEO) Interaction or User Interface Design User Experience
* Usability
* E-commerce Systems Portal Systems Wireframing
* CSS Layout / Grids
* DOM Manipulation
* Mobile Web Performance Load Testing Performance Testing
* Progressive Enhancement / Graceful Degradation Version Control (e.g., GIT)
* MVC / MVVM / MV\*
* Data Formats (e.g., JSON, XML) Data APIs (e.g Restful API)
* Web Font Embedding
* Scalable Vector Graphics (aka SVG) Regular Expressions
* Content Strategy Microdata / Microformats
* Task Runners, Build Tools, Process Automation Tools Responsive Web Design
* Object-Oriented Programming Application Architecture Modules JavaScript 
* Charts / Graphs
* UI Widgets
* Browser Developer Tools

![](/img/fe-handbook/Aspose.Words.5c5312d5-ece8-4713-b1e0-a1d4939ed601.116.jpeg)


### **Front-End on a Team**
A front-end developer is typically only one player on a team that designs and develops web sites, web applications, or native applications running from web technologies.

A bare bones development team for building ***professional*** web sites or software application for the web platform will typically, minimally, contain the following roles.

* Visual Designer (i.e., fonts, colors, spacing, emotion, visuals concepts & themes) UI/Interaction Designer/Information Architect (i.e., wireframes, specifying all user interactions and UI functionality, structuring information)
* ront-End Developer (i.e., writes code that runs in client/on device) Back-End Developer (i.e., writes code that runs on server)

The roles are ordered according to overlapping skills. A front-end developer will typically have a good handle on UI/Interaction design as well as back-end development. It is not uncommon for team members to fill more than one role by taking on the responsibilities of an over-lapping role.

It is assumed that the team mentioned above is being directed by a project lead or some kind of product owner (i.e., stakeholder, project manager, project lead, etc.)

A larger web team might include the following roles not shown above:

* SEO Strategists DevOps Engineers API Developers
* Database Administrators QA Engineers / Testers



### **Front-End Salaries**


![](/img/fe-handbook/Aspose.Words.5c5312d5-ece8-4713-b1e0-a1d4939ed601.130.jpeg)


## **Part II: Learning**


### **Web Browsers**
A web browser (commonly referred to as a browser) is a software application for retrieving, presenting, and traversing information resources on the World Wide Web. An information resource is identified by a Uniform Resource Identifier (URI/URL) and may be a web page, image, video or other piece of content. Hyperlinks present in resources enable users easily to navigate their browsers to related resources. Although browsers are primarily intended to use the World Wide Web, they can also be used to access information provided by web servers in private networks or files in file systems.

*— [Wikipedia*](https://en.wikipedia.org/wiki/Web_browser)*

### **The [most commonly used browsers ](https://www.sitepoint.com/browser-trends-september-2016-browser-wars/)(on any device) are:**

1. [Chrome ](http://www.google.com/chrome/)(engine: [Blink ](https://en.wikipedia.org/wiki/Blink_%28layout_engine%29)+ [V8](https://en.wikipedia.org/wiki/V8_%28JavaScript_engine%29))
1. [Firefox ](https://www.mozilla.org/en-US/firefox/new/)(engine: [Gecko ](https://en.wikipedia.org/wiki/Gecko_%28software%29)+ [SpiderMonkey](https://en.wikipedia.org/wiki/SpiderMonkey_%28software%29))
1. [Internet Explorer ](http://windows.microsoft.com/en-us/internet-explorer/download-ie)(engine: [Trident ](https://en.wikipedia.org/wiki/Trident_%28layout_engine%29)+ [Chakra](https://en.wikipedia.org/wiki/Chakra_%28JScript_engine%29))
1. [Safari ](https://www.apple.com/safari/)(engine: [Webkit ](https://en.wikipedia.org/wiki/WebKit)+ [SquirrelFish](https://trac.webkit.org/wiki/SquirrelFish))

![](/img/fe-handbook/Aspose.Words.5c5312d5-ece8-4713-b1e0-a1d4939ed601.133.jpeg)





### **How Browsers Work**

![](/img/fe-handbook/Aspose.Words.5c5312d5-ece8-4713-b1e0-a1d4939ed601.134.png)

*Image source: [http://www.html5rocks.com/en/tutorials/internals/howbrowserswork/*](http://www.html5rocks.com/en/tutorials/internals/howbrowserswork/)*

### **Optimizing for Browsers:**

* [Browser Rendering Optimization ](https://www.udacity.com/course/browser-rendering-optimization--ud860)[watch] 
* [Website Performance Optimization ](https://www.udacity.com/course/website-performance-optimization--ud884)[watch]


### **Learn HTTP/Networks (Including CORS & WebSockets)**
**HTTP** - The Hypertext Transfer Protocol (HTTP) is an application protocol for distributed, collaborative, hypermedia information systems. HTTP is the foundation of data communication for the World Wide Web.

- [*Wikipedia*](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol)

**CORS** - Cross-origin resource sharing (CORS) is a mechanism that allows restricted resources (e.g., fonts) on a web page to be requested from another domain outside the domain from which the resource originated.

- [*Wikipedia*](https://en.wikipedia.org/wiki/Cross-origin_resource_sharing)






**WebSockets** - WebSocket is a protocol providing full-duplex communication channels over a single TCP connection. The WebSocket protocol was standardized by the IETF as RFC 6455 in 2011, and the WebSocket API in Web IDL is being standardized by the W3C.

- [*Wikipedia*](https://en.wikipedia.org/wiki/WebSocket)

### **HTTP Specifications**

* [HTTP/2](https://http2.github.io/)
* [Hypertext Transfer Protocol -- HTTP/1.1](https://tools.ietf.org/html/rfc2616)

### **HTTP Status Codes**

* [HTTP Status Codes](https://httpstatuses.com/)

### **CORS Specifications**

* [Cross-Origin Resource Sharing](https://www.w3.org/TR/cors/)

### **CORS**

* [CORS in Action ](https://www.amazon.com/CORS-Action-Creating-consuming-cross-origin/dp/161729182X/?&_encoding=UTF8&tag=frontend-handbook-20&linkCode=ur2&linkId=47ebd885d688a4ed69f77a1bd8273f8a&camp=1789&creative=9325)[read][$]
* [HTTP Access Control (CORS) ](https://developer.mozilla.org/en-US/docs/Web/HTTP/Access_control_CORS)[read]

### **WebSockets**

* [Connect the Web With WebSockets ](https://code.tutsplus.com/courses/connect-the-web-with-websockets)[watch]
* [WebSocket: Lightweight Client-Server Communications ](https://www.amazon.com/WebSocket-Client-Server-Communications-Andrew-Lombardi/dp/1449369278/?&_encoding=UTF8&tag=frontend-handbook-20&linkCode=ur2&linkId=dd39395cf3d2ab4fc7c820d7c19db39a&camp=1789&creative=9325)[read][$] [The WebSocket Protocol ](https://tools.ietf.org/html/rfc6455)[read]


### **Learn HTML & CSS**
**HTML** - HyperText Markup Language, commonly referred to as HTML, is the standard markup language used to create web pages. Web browsers can read HTML files and render them into visible or audible web pages. HTML describes the structure of a website semantically along with cues for presentation, making it a markup language, rather than a programming language.

- [*Wikipedia*](https://en.wikipedia.org/wiki/HTML)

**CSS** - Cascading Style Sheets (CSS) is a style sheet language used for describing the look and formatting of a document written in a markup language. Although most often used to change the style of web pages and user interfaces written in HTML and XHTML, the language can be applied to any kind of XML document, including plain XML, SVG and XUL. Along with HTML and JavaScript, CSS is a cornerstone technology used by most websites to create visually engaging webpages, user interfaces for web applications, and user interfaces for many mobile applications.

- [*Wikipedia*](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)

### **Mastering CSS:**

* [A Complete Guide to Flexbox ](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)[read] [CSS Diner ](http://flukeout.github.io/)[interact]
* [CSS Selectors from CSS4 till CSS1 ](http://css4-selectors.com/selectors/)[read]
* [CSS Secrets: Better Solutions to Everyday Web Design Problems ](https://www.amazon.com/CSS-Secrets-Solutions-Everyday-Problems/dp/1449372635/?&_encoding=UTF8&tag=frontend-handbook-20&linkCode=ur2&linkId=40a9480c18839b4b2ea798aa2afafd0e&camp=1789&creative=9325)[read][$] [CSS3 ](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS3)[read]
* [CSS3 In-Depth ](https://frontendmasters.com/courses/css3-in-depth/)[watch][$]
* [What the Flexbox?! A Simple, Free 20 Video Course That Will Help You Master CSS Flexbox \[watch\]](http://flexbox.io/) 


### **Learn JavaScript**
JavaScript is a high level, dynamic, untyped, and interpreted programming language. It has been standardized in the ECMAScript language specification. Alongside HTML and CSS, it is one of the three essential technologies of World Wide Web content production; the majority of websites employ it and it is supported by all modern web browsers without plug-ins. JavaScript is prototype-based with first-class functions, making it a multi-paradigm language, supporting object-oriented, imperative, and functional programming styles. It has an API for working with text, arrays, dates and regular expressions, but does not include any I/O, such as networking, storage or graphics facilities, relying for these upon the host environment in which it is embedded.

- [*Wikipedia*](https://en.wikipedia.org/wiki/JavaScript)

### **Getting Started:**

* [codecademy.com JavaScript ](https://www.codecademy.com/en/tracks/javascript)[interact] 
* [JavaScript first steps ](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps)[read]
* [JavaScript building blocks ](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks)[read] 
* [JavaScript Enlightenment ](http://www.javascriptenlightenment.com/)[read] 
* [JavaScript object basics ](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics)[read] 
* [Eloquent JavaScript ](http://eloquentjavascript.net/)[read]

### **Functional JavaScript:**

* [Functional Programming Jargon](https://github.com/hemanth/functional-programming-jargon#functional-programming-jargon)
* [funfunfunction: Functional programming in JavaScript ](https://www.youtube.com/watch?v=BMUiFMZr7vk&list=PL0zVEGEvSaeEd9hlmCXrk5yUyqUag-n84)[watch] 
* [Functional-Light-JS ](https://github.com/getify/Functional-Light-JS)[read]
* [Functional Programming in JavaScript: How to improve your JavaScript programs using functional techniques \[read\]](https://www.amazon.com/Functional-Programming-JavaScript-functional-techniques/dp/1617292826/ref%3Dsr_1_1?&_encoding=UTF8&tag=fronenddevejo-20&linkCode=ur2&linkId=dcc6b0cb7de57fa841f1b178d2d54b9d&camp=1789&creative=9325)
* [Mostly adequate guide to FP (in javascript) ](https://drboolean.gitbooks.io/mostly-adequate-guide/content/)[read] 
* [JavaScript Allongé ](https://leanpub.com/javascriptallongesix)[read][$]
* [Hardcore Functional Programming in JavaScript ](https://frontendmasters.com/courses/functional-javascript/)[watch][$] 
* [Functional-Lite JavaScript ](https://frontendmasters.com/courses/functional-js-lite/)[watch][$]



### **Learn DOM, BOM, & jQuery**
**DOM** - The Document Object Model (DOM) is a cross-platform and language- independent convention for representing and interacting with objects in HTML, XHTML, and XML documents. The nodes of every document are organized in a tree structure, called the DOM tree. Objects in the DOM tree may be addressed and manipulated by using methods on the objects. The public interface of a DOM is specified in its application programming interface (API).

- [*Wikipedia*](https://en.wikipedia.org/wiki/Document_Object_Model)

**BOM** - The Browser Object Model (BOM) is a browser-specific convention referring to all the objects exposed by the web browser. Unlike the Document Object Model, there is no standard for implementation and no strict definition, so browser vendors are free to implement the BOM in any way they wish.

- [*Wikipedia*](https://en.wikipedia.org/wiki/Browser_Object_Model)

**jQuery** - jQuery is a cross-platform JavaScript library designed to simplify the client- side scripting of HTML. jQuery is the most popular JavaScript library in use today, with installation on 65% of the top 10 million highest-trafficked sites on the Web. jQuery is free, open-source software licensed under the MIT License.

- [*Wikipedia*](https://en.wikipedia.org/wiki/JQuery)

### **Learn Web Fonts & Icons**
Web typography refers to the use of fonts on the World Wide Web. When HTML was first created, font faces and styles were controlled exclusively by the settings of each Web browser. There was no mechanism for individual Web pages to control font display until Netscape introduced the `<font>` tag in 1995, which was then standardized in the HTML 3.2 specification. However, the font specified by the tag had to be installed on the user's computer or a fallback font, such as a browser's default sans-serif or monospace font, would be used. The first Cascading Style Sheets specification was published in 1996 and provided the same capabilities.

These techniques did not gain much use, and were removed in the CSS2.1 specification. However, Internet Explorer added support for the font downloading feature in version 4.0, released in 1997. Font downloading was later included in the CSS3 fonts module, and has since been implemented in Safari 3.1, Opera 10 and Mozilla Firefox 3.5. This has subsequently increased interest in Web typography, as well as the usage of font downloading.

- [*Wikipedia*](https://en.wikipedia.org/wiki/Web_typography)

### **Learn Accessibility**
Accessibility refers to the design of products, devices, services, or environments for people with disabilities. The concept of accessible design ensures both “direct access” (i.e., unassisted) and "indirect access" meaning compatibility with a person's assistive technology (for example, computer screen readers).

Accessibility can be viewed as the "ability to access" and benefit from some system or entity. The concept focuses on enabling access for people with disabilities, or special needs, or enabling access through the use of assistive technology; however, research and development in accessibility brings benefits to everyone.

Accessibility is not to be confused with usability, which is the extent to which a product (such as a device, service, or environment) can be used by specified users to achieve specified goals with effectiveness, efficiency and satisfaction in a specified context of use.

Accessibility is strongly related to universal design which is the process of creating products that are usable by people with the widest possible range of abilities, operating within the widest possible range of situations. This is about making things accessible to all people (whether they have a disability or not).

- [*Wikipedia*](https://en.wikipedia.org/wiki/Accessibility)

### **Learn JSON (JavaScript Object Notation)**
JSON, (canonically pronounced sometimes JavaScript Object Notation), is an open standard format that uses human-readable text to transmit data objects consisting of attribute–value pairs. It is the primary data format used for asynchronous browser/server communication (AJAJ), largely replacing XML (used by AJAX).

Although originally derived from the JavaScript scripting language, JSON is a language- independent data format. Code for parsing and generating JSON data is readily available in many programming languages.

The JSON format was originally specified by Douglas Crockford. It is currently described by two competing standards, RFC 7159 and ECMA-404. The ECMA standard is minimal, describing only the allowed grammar syntax, whereas the RFC also provides some semantic and security considerations. The official Internet media type for JSON is application/json. The JSON filename extension is .json.

- [*Wikipedia*](https://en.wikipedia.org/wiki/JSON)

![](/img/fe-handbook/Aspose.Words.5c5312d5-ece8-4713-b1e0-a1d4939ed601.177.jpeg)



### **Learn Data (i.e. JSON) API Design**

* [API Design in Node.js (using Express & Mongo) ](https://frontendmasters.com/courses/api-design-nodejs/)[watch][$] 
* [Build APIs You Won't Hate ](http://apisyouwonthate.com/)[$][read]
* [JSON API ](http://jsonapi.org/)[read]
* [RESTful Web API Design with Node.JS - Second Edition ](https://www.amazon.com/RESTful-Web-API-Design-Node-JS/dp/1786469138?&_encoding=UTF8&tag=frontend-handbook-20&linkCode=ur2&linkId=65822660966bb9c5339b4b411ef25d73&camp=1789&creative=9325)[$][read]


### **Learn React & Redux**
#### **React:**

* [React.js Introduction For People Who Know Just Enough jQuery To Get By ](http://reactfordesigners.com/labs/reactjs-introduction-for-people-who-know-just-enough-jquery-to-get-by/)[read] 
* [React.js Fundamentals ](https://online.reacttraining.com/courses/enrolled/reactjsfundamentals)[watch]
* [13 things you need to know about React ](http://aimforsimplicity.com/post/13-things-you-need-to-know-about-react/)[read][ Tutorial: Intro To React ](https://facebook.github.io/react/tutorial/tutorial.html)[read]
* [React Enlightenment ](https://www.reactenlightenment.com/)[read] [ReactJS For Stupid People ](http://blog.andrewray.me/reactjs-for-stupid-people/)[read] 
* [REACT FOR BEGINNERS ](https://reactforbeginners.com/)[watch]
* [Complete Introduction to React (feat. Redux and React Router) ](https://frontendmasters.com/courses/react-intro/)[watch] 
* [React In-depth: An exploration of UI development ](https://www.gitbook.com/book/developmentarc/react-indepth/details)[read]
* [Complete Intro to React v2 (feat. Router v4 and Redux) ](https://frontendmasters.com/courses/complete-intro-react/)[watch][$] 
* [Welcome to A Complete Intro to React ](https://btholt.github.io/complete-intro-to-react/all.html)[read]
* [Build Your First Production Quality React App ](https://egghead.io/courses/build-your-first-production-quality-react-app)[watch][$]

#### **Redux:**

* [You Might Not Need Redux](https://medium.com/%40dan_abramov/you-might-not-need-redux-be46360cf367#.eaeglfaed)
* [A Dummy’s Guide to Redux and Thunk in React ](https://medium.com/%40stowball/a-dummys-guide-to-redux-and-thunk-in-react-d8904a7005d3#.mudzrmx8p)[read] 
* [Redux Tutorials ](https://www.youtube.com/playlist?list=PLoYCgNOIyGADILc3iUJzygCqC8Tt3bRXt)[watch]
* [Getting Started with Redux ](https://egghead.io/courses/getting-started-with-redux)[watch] [https://github.com/dwyl/learn- redux/blob/master/egghead.io_video_tutorial_notes.md](https://github.com/dwyl/learn-redux/blob/master/egghead.io_video_tutorial_notes.md)
* [Learn Redux ](https://learnredux.com/)[watch]
* [10 Tips for Better Redux Architecture ](https://medium.com/javascript-scene/10-tips-for-better-redux-architecture-69250425af44#.9s67j3efq)[watch]
* [Building React Applications with Idiomatic Redux ](https://egghead.io/courses/building-react-applications-with-idiomatic-redux)[watch][$]


### **Learn Node.js**
Node.js is an open-source, cross-platform runtime environment for developing server- side web applications. Node.js applications are written in JavaScript and can be run within the Node.js runtime on OS X, Microsoft Windows, Linux, FreeBSD, NonStop, IBM AIX, IBM System z and IBM i. Its work is hosted and supported by the Node.js Foundation, a collaborative project at Linux Foundation.

Node.js provides an event-driven architecture and a non-blocking I/O API designed to optimize an application's throughput and scalability for real-time web applications. It uses Google V8 JavaScript engine to execute code, and a large percentage of the basic modules are written in JavaScript. Node.js contains a built-in library to allow applications to act as a web server without software such as Apache HTTP Server, Nginx or IIS.

*— [Wikipedia*](https://en.wikipedia.org/wiki/Node.js)*

### **Learn Module loaders/bundlers**
#### **Webpack:**

* [Webpack](https://webpack.js.org/)
* [Webpack Deep Dive ](https://frontendmasters.com/courses/webpack/)[read] 
* [Webpack Fundamentals ](http://www.pluralsight.com/courses/webpack-fundamentals)[watch][$] 
* [Survivejs.com Webpack Book ](https://survivejs.com/webpack/introduction/)[read]

### **Learn Site Performance Optimization**
Web performance optimization, WPO, or website optimization is the field of knowledge about increasing the speed in which web pages are downloaded and displayed on the user's web browser. With the average internet speed increasing globally, it is fitting for website administrators and webmasters to consider the time it takes for websites to render for the visitor.

*— [Wikipedia*](https://en.wikipedia.org/wiki/Web_performance_optimization)*

### **General Learning:**

* [Browser Rendering Optimization ](https://www.udacity.com/course/browser-rendering-optimization--ud860)[watch]
* [Even Faster Web Sites: Performance Best Practices for Web Developers ](https://www.amazon.com/Even-Faster-Web-Sites-Performance/dp/0596522304?&_encoding=UTF8&tag=frontend-handbook-20&linkCode=ur2&linkId=4fe6a82bbf727209ba337ecaa0e516bc&camp=1789&creative=9325)[read][$] 
* [High Performance Web Sites: Essential Knowledge for Front-End Engineers ](https://www.amazon.com/High-Performance-Web-Sites-Essential/dp/0596529309/?&_encoding=UTF8&tag=frontend-handbook-20&linkCode=ur2&linkId=e93ab3ea06b7e3e93ee0d868249d0e3f&camp=1789&creative=9325)[read][$] 
* [JavaScript Performance Rocks ](http://javascriptrocks.com/)[read]
* [PageSpeed Insights Rules ](https://developers.google.com/speed/docs/insights/rules)[read] [perf-tooling.today ](http://www.perf-tooling.today/)[read] 
* [Performance Calendar ](http://calendar.perfplanet.com/)[read] 
* [perf.rocks ](http://perf.rocks/)[read]
* [Using WebPageTest ](https://www.amazon.com/Using-WebPageTest-Rick-Viscomi/dp/1491902590/ref%3Dsr_1_1?&_encoding=UTF8&tag=frontend-handbook-20&linkCode=ur2&linkId=91a76d5d4b4f47cf4e0d1392cc9cea30&camp=1789&creative=9325)[read][$]
* [Web Performance Daybook Volume 2 ](https://www.amazon.com/Web-Performance-Daybook-Techniques-Optimizing/dp/1449332919/?&_encoding=UTF8&tag=frontend-handbook-20&linkCode=ur2&linkId=59e32c394c2377bb17af1d801b924d1d&camp=1789&creative=9325)[read][$] 
* [Web Performance: The Definitive Guide ](http://shop.oreilly.com/product/0636920032427.do)[read] 
* [Website Performance ](https://frontendmasters.com/courses/website-performance/)[watch][$]
* [Website Performance Optimization ](https://www.udacity.com/course/website-performance-optimization--ud884)[watch]


### **Learn Testing**
**Unit Testing** - In computer programming, unit testing is a software testing method by which individual units of source code, sets of one or more computer program modules together with associated control data, usage procedures, and operating procedures, are tested to determine whether they are fit for use. Intuitively, one can view a unit as the smallest testable part of an application.

- [*Wikipedia*](https://en.wikipedia.org/wiki/Unit_testing)

**Functional Testing** - Functional testing is a quality assurance (QA) process and a type of black box testing that bases its test cases on the specifications of the software component under test. Functions are tested by feeding them input and examining the output, and internal program structure is rarely considered (not like in white-box testing). Functional testing usually describes what the system does.

- [*Wikipedia*](https://en.wikipedia.org/wiki/Functional_testing)

**Integration Testing** - Integration testing (sometimes called integration and testing, abbreviated I&T) is the phase in software testing in which individual software modules are combined and tested as a group. It occurs after unit testing and before validation testing. Integration testing takes as its input modules that have been unit tested, groups them in larger aggregates, applies tests defined in an integration test plan to those aggregates, and delivers as its output the integrated system ready for system testing.

- [*Wikipedia*](https://en.wikipedia.org/wiki/Integration_testing)

### **Learn Web/Browser/App Security**
* [Browser Security Handbook ](https://code.google.com/p/browsersec/wiki/Main)[read] 
* [Frontend Security ](https://mikewest.org/2013/09/frontend-security-frontendconf-2013)[watch] 
* [Hacksplaining ](https://www.hacksplaining.com/)[read]
* [HTML5 Security Cheatsheet ](https://html5sec.org/)[read] 
* [HTTP Security Best Practice ](https://httpsecurityreport.com/best_practice.html)[read]
* [Identity and Data Security for Web Development: Best Practices ](https://www.amazon.com/Identity-Data-Security-Web-Development/dp/1491937017?&_encoding=UTF8&tag=frontend-handbook-20&linkCode=ur2&linkId=f5f2aaa4d5f944a3ccc316a16e3673f4&camp=1789&creative=9325)read 
* [Security for Web Developers: Using JavaScript, HTML, and CSS ](https://www.amazon.com/Security-Web-Developers-Using-JavaScript/dp/1491928646/?&_encoding=UTF8&tag=frontend-handbook-20&linkCode=ur2&linkId=df49be399d7d1a12acebe5a85637a7a8&camp=1789&creative=9325)[read][$] 
* [The Basics of Web Application Security ](http://martinfowler.com/articles/web-security-basics.html)[read]
* [The Internet: Encryption & Public Keys ](https://www.youtube.com/watch?v=ZghMPWGXexs&list=PLzdnOPI1iJNfMRZm5DDxco3UdsFegvuB7&index=6)[watch] 
* [The Internet: Cybersecurity & Crime ](https://www.youtube.com/watch?v=AuYNXgO_f3Y&list=PLzdnOPI1iJNfMRZm5DDxco3UdsFegvuB7&index=7)[watch]
* [The Tangled Web: A Guide to Securing Modern Web Applications ](http://lcamtuf.coredump.cx/tangled/)[read][$] [Web Security Basics ](https://github.com/vasanthk/web-security-basics)[read]
* [Web security ](https://developer.mozilla.org/en-US/docs/Web/Security)[read]


### **Learn Multi-Device Development**

![](/img/fe-handbook/Aspose.Words.5c5312d5-ece8-4713-b1e0-a1d4939ed601.241.jpeg)

A website or web application can run on a wide range of computers, laptops, tablets and phones, as well as a handful of new devices (watches, thermostats, fridges, etc.). How you determine what devices you'll support and how you will develop to support those devices is

called, "multi-device development strategy". Below, I list the most common multi-device development strategies.

* Build a [responsive (RWD) ](https://en.wikipedia.org/wiki/Responsive_web_design)web site/app for all devices.
* Build an [adaptive/progressively ](https://en.wikipedia.org/wiki/Adaptive_web_design)enhanced web site/app for all devices.
* Build a website, web app, native app, or hybrid-native app for each individual device or a grouping of devices.
* Attempt to retrofit something you have already built using bits and parts from strategies 1, 2 or 3.


## **Part III: Front-end Developer Tools**

![](/img/fe-handbook/Aspose.Words.5c5312d5-ece8-4713-b1e0-a1d4939ed601.250.jpeg)


### **Doc/API Browsing Tools**
Tools to browser common developer documents and developer API references.

* [Dash ](https://kapeli.com/dash)[OS X, iOS][$] [DevDocs](http://devdocs.io/)
* [Velocity ](https://velocity.silverlakesoftware.com/)[Windows][$] 
* [Zeal ](https://zealdocs.org/)[Windows, Linux]

### **HTTP/Network Tools**

* [Charles ](http://www.charlesproxy.com/)[$]
* [Chrome DevTools Network Panel](https://developers.google.com/web/tools/chrome-devtools/profile/network-performance/resource-loading) 
* [Insomnia ](https://insomnia.rest/)[free - $]
* [Paw ](https://paw.cloud/)[$]
* [Postman ](https://www.getpostman.com/)[free - $]


### **Code Editing Tools**
A source code editor is a text editor program designed specifically for editing source code of computer programs by programmers. It may be a standalone application or it may be built into an integrated development environment (IDE) or web browser. Source code editors are the most fundamental programming tool, as the fundamental job of programmers is to write and edit source code.

- [*Wikipedia*](https://en.wikipedia.org/wiki/Source_code_editor)

Front-end code can minimally be edited with a simple text editing application like Notepad or TextEdit. But, most front-end practitioners use a code editor specifically design for editing a programming language.

Code editors come in all sorts of types and size, so to speak. Selecting one is a rather subjective engagement. Choose one, learn it inside and out, then get on to learning HTML, CSS, DOM, and JavaScript.

However, I do strongly believe, minimally, a code editor should have the following qualities (by default or by way of plugins):

1. Good documentation on how to use the editor
1. Report (i.e., hinting/linting/errors) on the code quality of HTML, CSS, and JavaScript.
1. Offer syntax highlighting for HTML, CSS, and JavaScript.
1. Offer code completion for HTML, CSS, and JavaScript.
1. Be customizable by way of a plug-in architecture
1. Have available a large repository of third-party/community plug-ins that can be used to customize the editor to your liking
1. Be small, simple, and not coupled to the code (i.e., not required to edit the code)

### **Code Editors:**

* [Atom](https://atom.io/) 
* [Brackets](http://brackets.io/)
* [Sublime Text ](http://www.sublimetext.com/)[$] 
* [WebStorm ](https://www.jetbrains.com/webstorm/whatsnew/)[$] 
* [Visual Studio Code](https://code.visualstudio.com/)

### **Online Code Editors:**

* [Cloud9 ](https://c9.io/)[free to $] 
* [Codeanywhere ](https://codeanywhere.com/)[free to $]


### **Shareable & Runnable Code Editors:**

Used to share limited amounts of immediately runnable code. Not a true code editor but a tool that can be used to small amounts of immediately runnable code in a web browser.

* [CodePen ](http://codepen.io/)[free to $] 
* [jsbin.com ](http://jsbin.com/)[free to $] 
* [jsfiddle.net](http://jsfiddle.net/) 
* [liveweave.com](http://liveweave.com/) 
* [Plunker](http://plnkr.co/)

# **Browser Tools**
### **JS Browser Coding Utilities:**

* [History.js](https://github.com/browserstate/history.js) 
* [html2canvas](https://github.com/niklasvh/html2canvas) 
* [Platform.js](https://github.com/bestiejs/platform.js) 
* [URI.js](http://medialize.github.io/URI.js/)

### **General Reference Tools to Determine If X Browser Supports X:**

* [Browser support for broken/missing images](http://codepen.io/bartveneman/full/qzCte/) 
* [Browserscope](http://www.browserscope.org/)
* [caniuse.com](http://caniuse.com/)
* [Firefox Platform Status - Implementation & standardization roadmap for web platform features](https://platform-status.mozilla.org/)
* [HTML5 Please](http://html5please.com/) 
* [HTML5 Test](https://html5test.com/) 
* [iwanttouse.com](http://www.iwanttouse.com/) 
* [jscc.info](http://jscc.info/) 
* [Platform Status](https://dev.modern.ie/platform/status/)
* [whatwebcando.today](https://whatwebcando.today/)

### **Browser Development/Debug Tools:**

* [Chrome Developer Tools (aka DevTools)](https://developers.google.com/web/tools/?hl=en) 
* [Per-Panel Documentation](https://developers.google.com/web/tools/chrome-devtools/#docs) 
* [Command Line API Reference](https://developers.google.com/web/tools/javascript/command-line/command-line-reference?hl=en) 
* [Keyboard & UI Shortcuts Reference](https://developers.google.com/web/tools/iterate/inspect-styles/shortcuts) 
* [Settings](https://developer.chrome.com/devtools/docs/settings)
* [Firefox Developer Tools](https://developer.mozilla.org/en-US/docs/Tools)
* [IE Developer tools (aka F12 tools)](https://dev.modern.ie/platform/documentation/f12-devtools-guide/) 
* [Safari Web Inspector](https://developer.apple.com/safari/tools/)
* [Vorlon.js](http://vorlonjs.com/)

### **Browser Automation:**

Used for functional testing and monkey testing.

* )[CasperJS](http://casperjs.org/) 
* [Nightmare](https://github.com/segmentio/nightmare) 
* [TestCafe](https://github.com/DevExpress/testcafe)

# **HTML Tools**
### **HTML Templates/Boilerplates/Starter Kits:**

* [dCodes](http://www.dcodes.net/2/docs/index.html)
* [Email-Boilerplate](https://github.com/seanpowell/Email-Boilerplate) 
* [HTML5 Boilerplate](https://html5boilerplate.com/) 
* [HTML5 Bones](http://html5bones.com/) 
* [Mobile boilerplate](https://html5boilerplate.com/mobile/)
* [Web Starter Kit Boilerplate & Tooling for Multi-Device Development](https://developers.google.com/web/tools/starter-kit)

### **HTML Polyfill:**

* [html5shiv](https://github.com/aFarkas/html5shiv)

### **Transpiling:**

* [HAML](http://haml.info/)
* [Pug](https://pugjs.org/api/getting-started.html) 
* [Markdown](http://daringfireball.net/projects/markdown/)

### **Linting/Hinting:**

* [HTMLHint](http://htmlhint.com/) 
* [html-inspector](https://github.com/philipwalton/html-inspector)

### **Optimizer:**

* [HTML Minifier](http://kangax.github.io/html-minifier/)


### **CSS Tools**
#### **Desktop & Mobile CSS Frameworks:**

* [Base](http://getbase.org/) 
* [Basscss](http://basscss.com/) 
* [Bulma](http://bulma.io/)
* [Bootstrap 3 ](http://getbootstrap.com/components/)or [Bootstrap 4](https://v4-alpha.getbootstrap.com/) 
* [Concise](http://concisecss.com/)
* [Foundation](http://foundation.zurb.com/)
* [Material Design Lite (MDL)](http://www.getmdl.io/index.html) 
* [Metro UI](http://metroui.org.ua/)
* [Picnic](http://picnicss.com/) 
* [Pure.css](http://purecss.io/) 
* [Semantic UI](http://semantic-ui.com/) 
* [Skeleton](http://getskeleton.com/) 
* [Spectre.css](https://picturepan2.github.io/spectre/) 
* [tachyons](https://github.com/tachyons-css/tachyons/)

#### **Mobile Only CSS Frameworks:**

* [Ratchet](http://goratchet.com/)

#### **CSS Reset:**

A CSS Reset (or “Reset CSS”) is a short, often compressed (minified) set of CSS rules that resets the styling of all HTML elements to a consistent baseline.

*— [cssreset.com*](http://cssreset.com/what-is-a-css-reset/)*

* [Eric Meyer's “Reset CSS” 2.0](http://meyerweb.com/eric/tools/css/reset/) 
* [Normalize](https://necolas.github.io/normalize.css/)

#### **Transpiling:**

* [pleeease.io](http://pleeease.io/) 
* [PostCSS ](https://github.com/postcss/postcss)& 
* [cssnext](http://cssnext.io/) 
* [rework ](https://github.com/reworkcss/rework)& 
* [myth](http://www.myth.io/) 
* [Sass/SCSS](http://sass-lang.com/)
* [Stylus](https://github.com/stylus/stylus)

#### **References:**

* [CSS Cursors](http://csscursor.info/) 
* [css3test.com](http://css3test.com/) 
* [css3clickchart.com](http://css3clickchart.com/) 
* [cssreference.io](http://cssreference.io/)
* [CSS Indexes - A listing of every term defined by CSS specs](https://drafts.csswg.org/indexes/) 
* [css4-selectors.com](http://css4-selectors.com/)
* [css4 Rocks](http://css4.rocks/)
* [CSS TRIGGERS...A GAME OF LAYOUT, PAINT, AND COMPOSITE](http://csstriggers.com/)
* [CSS Tricks Almanac](https://css-tricks.com/almanac/) 
* [cssvalues.com](http://cssvalues.com/)
* [MDN CSS Reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)

### **Linting/Hinting:**

* [CSS Lint](http://csslint.net/) 
* [stylelint](http://stylelint.io/)

### **Code Formatter/Beautifier:**

* [CSScomb](https://github.com/csscomb/csscomb.js) 
* [CSSfmt](https://github.com/morishitter/cssfmt)

### **Optimizer:**

* [clear-css](https://github.com/jakubpawlowicz/clean-css) 
* [cssnano](http://cssnano.co/) 
* [CSSO](http://css.github.io/csso/)

### **Online Creation/Generation/Experimentation Tools:**

* [CSS Arrow Please](http://cssarrowplease.com/) 
* [CSS Matic](http://www.cssmatic.com/)
* [Enjoy CSS](http://enjoycss.com/)
* [Flexbox Playground](https://scotch.io/demos/visual-guide-to-css3-flexbox-flexbox-playground) 
* [flexplorer](http://bennettfeely.com/flexplorer/) 
* [patternify.com](http://patternify.com/) 
* [patternizer.com](http://patternizer.com/)
* [Ultimate CSS Gradient Generator](http://www.colorzilla.com/gradient-editor/)


### **DOM Tools**
#### **DOM Libraries/Frameworks:**

* [Bliss](http://blissfuljs.com/docs.html) 
* [jQuery](http://jquery.com/)
* [You Don't Need jQuery](https://github.com/oneuijs/You-Dont-Need-jQuery) 
* [Zepto](http://zeptojs.com/)
* [cash](https://github.com/kenwheeler/cash/) 
* [Umbrella JS](http://umbrellajs.com/)

#### **DOM Utilities:**

* [Keypress](http://dmauro.github.io/Keypress/) 
* [Tether](http://tether.io/docs/welcome/) 
* [clipboard.js](http://zenorocha.github.io/clipboard.js/)

#### **DOM Event Tools:**

* [Keyboard Event Viewer](http://w3c.github.io/uievents/tools/key-event-viewer.html)

#### **DOM Performance Tools:**

* [Chrome DevTools Timeline](https://developers.google.com/web/tools/chrome-devtools/evaluate-performance/timeline-tool) 
* [DOM Monster](http://mir.aculo.us/dom-monster/)

#### **Virtual DOM:**

* [jsdom](https://github.com/tmpvar/jsdom) 
* [virtual-dom](https://github.com/Matt-Esch/virtual-dom)


### **JavaScript Tools**
#### **JS Utilities:**

* [accounting.js](http://openexchangerates.github.io/accounting.js/) 
* [async](http://caolan.github.io/async/)
* [axios](https://github.com/mzabriskie/axios) 
* [chance](http://chancejs.com/) 
* [date-fns](https://date-fns.org/) 
* [format.js](http://formatjs.io/) 
* [immutable](https://facebook.github.io/immutable-js/) 
* [is.js](http://arasatasaygin.github.io/is.js/) 
* [lodash](https://lodash.com/)
* [You-Dont-Need-Lodash-Underscore](https://github.com/you-dont-need/You-Dont-Need-Lodash-Underscore) 
* [Math.js](http://mathjs.org/)
* [Moment.js](http://momentjs.com/) 
* [Numeral.js](http://numeraljs.com/) 
* [string.js](http://stringjs.com/) 
* [underscore.js](http://underscorejs.org/)
* [You-Dont-Need-Lodash-Underscore](https://github.com/you-dont-need/You-Dont-Need-Lodash-Underscore) 
* [voca](https://vocajs.com/)
* [wait](https://github.com/elving/wait) 
* [xregexp.com](http://xregexp.com/)

#### **Transpiling / Type Checking (ES *to ES*):**

* [Babel](https://babeljs.io/) 
* [TypeScript](https://www.typescriptlang.org/) 
* [Flow](https://flowtype.org/)

#### **Code-analysis Engine:**

* [Tern](https://ternjs.net/)

#### **JavaScript Compatibility Checker:**

* [jscc.info/](http://jscc.info/)

#### **Linting/Hinting & Style Linter:**

* [eslint](http://eslint.org/)

#### **Unit Testing:**

* [AVA](https://github.com/avajs/ava)
* [Jasmine](http://jasmine.github.io/) 
* [Mocha](http://mochajs.org/) 
* [Tape](https://github.com/substack/tape)


#### **Code Formater/Beautifier:**

* [esformatter](https://github.com/millermedeiros/esformatter#esformatterformatstr-optsstring) 
* [js-beautify](http://jsbeautifier.org/) 
* [jsfmt](http://rdio.github.io/jsfmt/) 
* [prettier](https://github.com/jlongster/prettier)

#### **Performance Testing:**
* [benchmark.js](http://benchmarkjs.com/) 
* [jsperf.co](https://jsperf.co/)

#### **Sharable/Runnable Code Editors:**

* [es6fiddle.net](http://www.es6fiddle.net/) 
* [jsbin.com ](http://jsbin.com/)[free to $] 
* [jsfiddle.net](http://jsfiddle.net/)

### **Static Site Generators Tools**
#### **Site Generator Listings:**

* [staticgen.com](https://www.staticgen.com/) 
* [staticsitegenerators.net](https://staticsitegenerators.net/) 
* [Metalsmith](http://www.metalsmith.io/)


### **Accessibility Tools**

#### **Guides**

* [Accessibility Guidelines Checklist](http://accessibility.voxmedia.com/) 
* [Interactive WCAG 2.0](http://code.viget.com/interactive-wcag/)
* [18F Accessibility Guide](https://pages.18f.gov/accessibility/checklist/)


#### **Screen Readers**

* [VoiceOver ](http://www.apple.com/accessibility/)(Mac) 
* [JAWS ](http://www.freedomscientific.com/Products/Blindness/JAWS)(Win) 
* [NVDA ](https://www.nvaccess.org/)(Win)
* [Window-Eyes ](https://www.aisquared.com/products/window-eyes/)(Win)
* [ChromeVox ](http://www.chromevox.com/)(Chrome extension)
* [Basic screen reader commands](https://www.paciellogroup.com/blog/2015/01/basic-screen-reader-commands-for-accessibility-testing/)


#### **Readability Testers**

* [Expresso App](http://www.expresso-app.org/) 
* [Hemingway App](http://www.hemingwayapp.com/) 
* [Grammarly](https://www.grammarly.com/) 
* [Readability Score](https://readability-score.com/text/) 
* [MS Office](https://support.office.com/en-us/article/Test-your-document-s-readability-0adc0e9a-b3fb-4bde-85f4-c9e88926c6aa)

### **App Frameworks (Desktop, Mobile, Tablet, etc.) Tools**

* [AngularJS ](https://github.com/angular/angular.js)(i.e Angular 1.x.x) + 
* [Batarang](https://github.com/angular/angularjs-batarang) 
* [Angular ](https://github.com/angular/angular)(i.e. Angular 2.0.0 +) + 
* [angular-cli](https://github.com/angular/angular-cli) 
* [Aurelia ](http://aurelia.io/)+ 
* [Aurelia CLI](https://github.com/aurelia/cli)
* [Ember ](http://emberjs.com/)+ 
* [embercli ](https://ember-cli.com/)+ 
* [Ember Inspector](https://chrome.google.com/webstore/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi?hl=en) 
* [Polymer](https://www.polymer-project.org/1.0/)
* [React ](http://facebook.github.io/react/)+ 
* [create-react-app ](https://github.com/facebookincubator/create-react-app)+ 
* [React Developer Tools](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi) ![](/img/fe-handbook/Aspose.Words.5c5312d5-ece8-4713-b1e0-a1d4939ed601.437.png)
* [Vue.js ](http://vuejs.org/)+ 
* [vue-cli ](https://github.com/vuejs/vue-cli)& 
* [Vue.js devtools](https://chrome.google.com/webstore/detail/vuejs-devtools/nhdogjmejiglipccpnnnanhbledajbpd?hl=en)
* [Riot](http://riotjs.com/)

### **Native Hybrid Mobile WebView (i.e., Browser Engine Driven) Frameworks:**

These solutions typically use [Cordova](https://cordova.apache.org/), [crosswalk](https://crosswalk-project.org/), or a custom WebView as a bridge to native APIs.

* [ionic](http://ionicframework.com/) 
* [onsen.io](http://onsen.io/)

### **Native Hybrid Mobile Development Webview (i.e., Browser Engine Driven) Environments/Platforms/Tools:**
These solutions typically use [Cordova](https://cordova.apache.org/), [crosswalk](https://crosswalk-project.org/), or a custom WebView as a bridge to native APIs.

* [Adobe PhoneGap ](http://phonegap.com/)[$] 
* [AppBuilder ](http://www.telerik.com/appbuilder)[$] 
* [cocoon.io ](https://cocoon.io/)[free to $] 
* [ionic hub ](http://ionic.io/)[free to $] 
* [kony ](http://www.kony.com/products/mobility-platform)[$]
* [Monaca ](https://monaca.io/)[$] 
* [Taco](http://taco.tools/)

### **Native Desktop WebView (i.e., Browser Engine Driven) App Frameworks:**
* [Electron](http://electron.atom.io/) 
* [NW.js](https://github.com/nwjs/nw.js)


### **General Front-End Development Tools**
#### **Development Tools:**

* [Browsersync](http://www.browsersync.io/) 
* [CodeKit](http://incident57.com/codekit/) 
* [Prepros](https://prepros.io/)


### **Templating/Data Binding Tools**
#### **Just Templating:**

* [doT.js](http://olado.github.io/doT/) 
* [Handlebars](http://handlebarsjs.com/)
* [htmlbars](https://github.com/tildeio/htmlbars) 
* [Nunjuncks](http://mozilla.github.io/nunjucks/)

#### **Templating and Reactive Data Binding:**

* [Deku](https://github.com/anthonyshort/deku) 
* [jquerymy.js](http://jquerymy.com/) [ractive.js](http://www.ractivejs.org/) 
* [react.js](https://facebook.github.io/react/index.html)
* [riot](http://riotjs.com/) 
* [Rivets.js](http://rivetsjs.com/) 
* [vue.js](http://vuejs.org/)

### **Data Visualization (e.g., Charts) Tools**
#### **JS Libraries:**
* [d3](http://d3js.org/) 
* [sigmajs](http://sigmajs.org/)

#### **Widgets & Components:**

* [amCharts ](http://www.amcharts.com/)[free to $]
* [AnyChart ](http://www.anychart.com/)[Non-commercial free to $] 
* [C3.js](http://c3js.org/)
* [Chartist-jsj](https://github.com/gionkunz/chartist-js) 
* [Chart.js](http://www.chartjs.org/) 
* [Epoch](http://epochjs.github.io/epoch/)
* [FusionCharts ](http://www.fusioncharts.com/)[$] 
* [Google Charts](https://developers.google.com/chart/interactive/docs/)
* [Highcharts ](http://www.highcharts.com/)[Non-commercial free to $] 
* [ZingChart ](http://www.zingchart.com/)[free to $]




### **Graphics (e.g., SVG, canvas, webgl) Tools**
#### **General:**

* [Fabric.js](http://fabricjs.com/) 
* [Two.js](http://jonobr1.github.io/two.js/#introduction)

#### **Canvas:**
* [EaselJS](https://github.com/CreateJS/EaselJS) 
* [Paper.js](http://paperjs.org/)

#### **SVG:**

* [d3](http://d3js.org/) 
* [GraphicsJS](http://www.graphicsjs.org/) 
* [Raphaël](http://raphaeljs.com/) 
* [Snap.svg](http://snapsvg.io/) 
* [svg.js](http://svgjs.com/)

#### **WebGL:**

* [pixi.js](https://github.com/pixijs/pixi.js) 
* [three.js](http://threejs.org/)


### **JSON Tools**
#### **Online Editors:**

* [JSONmate](http://jsonmate.com/) 
* [json.browse()](https://jamstack.org/)

#### **Formatter & Validator:**

* [jsonformatter.org](http://jsonformatter.org/)
* [JSON Formatter & Validator](https://jsonformatter.curiousconcept.com/)

#### **Query Tools:**

* [DefiantJS](http://www.defiantjs.com/) 
* [JSON Mask](https://github.com/nemtsov/json-mask) 
* [ObjectPath](http://objectpath.org/)

#### **Generating Mock JSON Tools:**

* [JSON Generator](http://www.json-generator.com/) 
* [Mockaroo ](https://www.mockaroo.com/)[free to $]

#### **Online JSON Mocking API Tools:**

* [FillText.com](http://www.filltext.com/) 
* [Jam API](https://www.jamapi.xyz/)
* [JSONPlaceholder](http://jsonplaceholder.typicode.com/) 
* [jsonbin.org](https://jsonbin.org/) 
* [mockable.io](https://www.mockable.io/) 
* [mockapi.io](http://www.mockapi.io/)
* [Mocky](http://www.mocky.io/)
* [RANDOM USER GENERATOR](https://randomuser.me/)

#### **List of public JSON API's:**

* [A collective list of JSON APIs for use in web development](https://github.com/toddmotto/public-apis)

#### **Local JSON Mocking API Tools:**

* [json-server](https://github.com/typicode/json-server)

#### **JSON Specifications/Schemas:**
* [json-schema.org ](http://json-schema.org/)& 
* [jsonschema.net](http://jsonschema.net/)
* [{json:api}](http://jsonapi.org/)


### **Testing Tools**
#### **Software Testing Frameworks:**

* )[Intern](https://theintern.github.io/) 
* [Karma](http://karma-runner.github.io/1.0/index.html) 
* [Jest](http://facebook.github.io/jest/)

#### **Unit Testing:**

* [AVA](https://github.com/avajs/ava)
* [Jasmine](http://jasmine.github.io/) 
* [Mocha](http://mochajs.org/) 
* [Tape](https://github.com/substack/tape)

#### **Testing Assertions for Unit Testing:**

* [Chai](http://chaijs.com/) 
* [expect.js](https://github.com/Automattic/expect.js) 
* [should.js](http://shouldjs.github.io/)

#### **Hosted Testing/Automation for Browsers:**

* [Browserling ](https://www.browserling.com/)[$] 
* [BrowserStack ](https://www.browserstack.com/)[$] 
* [CrossBrowserTesting.com ](http://crossbrowsertesting.com/)[$] 

#### **Browser Automation:**

* [CasperJS](http://casperjs.org/) 
* [Nightmare](https://github.com/segmentio/nightmare) 
* [TestCafe](https://github.com/DevExpress/testcafe)

#### **Automated dead link and error detectors:**

* [Monkey Test It](https://monkeytest.it/)


**NOTES:**

Testing frameworks typically offer more tools than just unit testing. If you are looking for JavaScript unit testing solutions look at [JavaScript Tools](https://frontendmasters.gitbooks.io/front-end-handbook-2017/content/tools/js.html).



**SURVEY RESULTS:**

[The images below are from the 2016 Frontend Tooling Survey (4715 developers) and 2016 State of JS Survey (9307 developers)](http://stateofjs.com/)

![](/img/fe-handbook/Aspose.Words.5c5312d5-ece8-4713-b1e0-a1d4939ed601.528.jpeg)

![](/img/fe-handbook/Aspose.Words.5c5312d5-ece8-4713-b1e0-a1d4939ed601.530.jpeg)


![](/img/fe-handbook/Aspose.Words.5c5312d5-ece8-4713-b1e0-a1d4939ed601.531.jpeg)



### **Module Loading/Bundling Tools**

* [Browserify](http://browserify.org/) 
* [Rollup](http://rollupjs.org/) 
* [SystemJS](https://github.com/systemjs/systemjs) 
* [webpack](https://webpack.js.org/)
* [webpackbin](http://www.webpackbin.com/)


**SURVEY RESULTS:**

[The images below are from the 2016 Frontend Tooling Survey (4715 developers) and 2016 State of JS Survey (9307 developers)](http://stateofjs.com/)

![](/img/fe-handbook/Aspose.Words.5c5312d5-ece8-4713-b1e0-a1d4939ed601.537.jpeg)


*Image source: [https://ashleynolan.co.uk/blog/frontend-tooling-survey-2016-results*](https://ashleynolan.co.uk/blog/frontend-tooling-survey-2016-results)*


![](/img/fe-handbook/Aspose.Words.5c5312d5-ece8-4713-b1e0-a1d4939ed601.540.jpeg)

![](/img/fe-handbook/Aspose.Words.5c5312d5-ece8-4713-b1e0-a1d4939ed601.541.jpeg)



### **Module/Package Repository Tools**

* [NPM](https://www.npmjs.com/)
* [yarn](https://yarnpkg.com/)


### **Hosting Tools**
#### **General**

* [AWS ](https://aws.amazon.com/websites/)[$]
* [DigitalOcean ](https://digitalocean.com/)[$] 
* [Heroku ](https://heroku.com/)[free to $]


### **Project Management & Code Hosting Tools**

* [Assembla ](https://www.assembla.com/)[free to $] 
* [Bitbucket ](https://bitbucket.org/)[free to $] 
* [Codebase ](https://www.codebasehq.com/)[$] 
* [Github ](https://github.com/)[free to $] 
* [GitLab ](https://about.gitlab.com/)[free to $] 
* [Unfuddle ](https://unfuddle.com/)[$]


### **Collaboration & Communication Tools**

* [Slack ](https://slack.com/)& 
* [screenhero ](https://screenhero.com/)[free to $] 
* [appear.in](https://appear.in/)
* [Mattermost ](https://mattermost.org/)[free to $] 
* [TeamViewer ](https://www.teamviewer.com/)[free to $]

### **Content Management Hosted/API Tools**
#### **API CMS (i.e., Content Delivery CMS) Tools:**

* [Contentful ](https://www.contentful.com/)[$] 
* [Cosmic JS ](https://cosmicjs.com/)[free to $] 
* [prismic.io ](https://prismic.io/)[free to $] 
* [elemeno ](https://elemeno.io/)[free to $]

#### **Hosted CMS Tools:**

* [Cushy CMS ](https://www.cushycms.com/)[free to $] 
* [LightCMS ](https://www.lightcms.com/)[$]
* [Page Lime ](http://www.pagelime.com/)[$] 
* [Surreal CMS ](http://www.surrealcms.com/)[$]

#### **Static CMS Tools:**

* [webhook.com](http://www.webhook.com/) 
* [Dato CMS](https://www.datocms.com/) 
* [siteleaf](https://www.siteleaf.com/) 
* [forestry.io](https://forestry.io/)


### **Security Tools**
#### **Coding Tool:**

* [DOMPurify](https://github.com/cure53/DOMPurify) 
* [XSS](http://jsxss.com/en/index.html)

#### **Security Scanners/Evaluators/Testers:**

* [Netsparker](https://www.netsparker.com/) 
* [Websecurify](http://www.websecurify.com/) 
* [OWASP ZAP](https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project)

#### **References:**

* [HTML5 Security Cheatsheet](https://html5sec.org/)



![](/img/fe-handbook/Aspose.Words.5c5312d5-ece8-4713-b1e0-a1d4939ed601.540.jpeg)


![](/img/fe-handbook/Aspose.Words.5c5312d5-ece8-4713-b1e0-a1d4939ed601.541.jpeg)




### **JavaScript Error Reporting/Monitoring**

* [bugsnag ](https://bugsnag.com/)[$] 
* [errorception ](https://errorception.com/)[$] 
* [Honeybadger ](https://www.honeybadger.io/)[$] 
* [Raygun ](https://raygun.io/)[$] 
* [Rollbar ](https://rollbar.com/)[free to $] 
* [Sentry ](https://getsentry.com/welcome/)[free to $] [TrackJS ](https://trackjs.com/)[$]


### **Performance Tools**
#### **Reporting:**

* [GTmetrix](https://gtmetrix.com/) 
* [sitespeed.io](https://www.sitespeed.io/) 
* [Speed Curve ](https://speedcurve.com/)[$] 
* [Web Page Test](http://www.webpagetest.org/)

#### **JS Tools:**

* [imagemin](https://github.com/imagemin/imagemin) 
* [ImageOptim-CLI](http://jamiemason.github.io/ImageOptim-CLI/)

#### **Checklist:**

* [Front-End Performance Checklist 2017](https://www.smashingmagazine.com/2016/12/front-end-performance-checklist-2017-pdf-pages/)


### **Tools for Finding Tools**

* [built with](http://builtwith.com/) 
* [javascripting.com](http://www.javascripting.com/) 
* [js.coach](https://js.coach/) 
* [microjs.com](http://microjs.com/) 
* [npms](https://npms.io/) 
* [stackshare.io](http://stackshare.io/) 
* [Unheap](http://www.unheap.com/)










## **BT Tool Component Library**

Storybook is a tool for UI development. It makes development faster and easier by isolating components. This allows you to work on one component at a time. You can develop entire UIs without needing to start up a complex dev stack, force certain data into your database, or navigate around your application.

Use Storybook to build small atomic components and complex pages in your web application. If it's a UI, you can build it with Storybook. Storybook helps you **document** components for reuse and automatically **visually test** your components to prevent bugs. Extend Storybook with an ecosystem of **addons** that help you do things like fine-tune responsive layouts or verify accessibility.

Storybook integrates with most popular JavaScript UI frameworks and (experimentally) supports server-rendered component frameworks such as [Ruby on Rails](https://rubyonrails.org/).
