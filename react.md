# presentation

### hello everyone!

In my presentation, I would like to give you an overview of React.

React is a Javascript library for building frontend web application or user interface. It is currently one of the most popular JavaScript front-end libraries which has a strong foundation and a large community supporting it.

React was created by Jordan Walke, a software engineer at Facebook.

React is a library, not a framework. It focuses on the view layer of the MVC (Model-View-Controller) framework, so it is a part of creating a framework. That said, many people find that it has some features that enable it to help build or support larger frameworks. This is especially true when factoring in the wider ecosystem.

### Component

In React, everything is a component. they are independent pieces of functionality that you can reuse in your code, and are the building blocks of all applications built on the React framework. Often, they can be simple JavaScript functions and classes, but you use them as if they were customized HTML elements. Buttons, menus, and any other front-end page content can all be created as components.

When creating a React component, the component's name must start with an upper case letter.
The component has to include the extends React.Component statement, this statement creates an inheritance to React.Component, and gives your component access to React.Component's functions.
The component also requires a render() method, this method returns HTML.

Now your React application has a component called Car, which returns a h2 element.
To use this component in your application, use similar syntax as normal HTML: Car

Here is the same example as above, but created using a Function component instead.
A Function component also returns HTML, and behaves pretty much the same way as a Class component

The biggest advantage of using components is that you can change any component at any point in time without affecting the rest of the applications.

### jsx

As we have already seen that, all of the React components have a render function. The render function specifies the HTML output of a React component. JSX(JavaScript Extension), is a React extension which allows writing JavaScript code that looks like HTML. In other words, JSX is an HTML-like syntax used by React that extends ECMAScript so that HTML-like syntax can co-exist with JavaScript/React code.

JSX allows us to write HTML elements in JavaScript and place them in the DOM without any createElement()  and/or appendChild() methods.
You are not required to use JSX, but JSX makes it easier to write React applications.

Note that JSX does not use quotes around the HTML text string.

Why use JSX:

* It is faster than regular JavaScript because it performs optimization while translating the code to JavaScript.
* It is type-safe, and most of the errors can be found at compilation time.
* It makes easier to create templates.

### Virtual DOM

The virtual DOM is a concept implemented by libraries in JavaScript on top of browser APIs.

For every DOM object, there is a corresponding virtual DOM object(copy), which has the same properties.
The main difference between the real DOM object and the virtual DOM object is that any changes in the virtual DOM object will not reflect on the screen directly.

React uses two virtual DOMs to render the user interface. One of them is used to store the current state of the objects and the other to store the previous state of the objects.
Whenever the virtual DOM gets updated, react compares the two virtual DOMs and gets to know about which virtual DOM objects were updated.
After knowing which objects were updated, react renders only those objects inside the real DOM instead of rendering the complete real DOM.
This way, with the use of virtual DOM, react solves the problem of inefficient updating.


### benefits

* Easy to Learn and USe: ReactJS is much easier to learn and use. It comes with a good supply of documentation, tutorials, and training resources. Any developer who comes from a JavaScript background can easily understand and start creating web apps using React in a few days.

* Easy to Create Dynamic Web Applications: Before ReactJS, creating dynamic web application was cost and complicated affair. Developers had to go through complex coding while ReactJS has simplified this by offering rich quality and quantity of features and functionalities in less coding -thanks to the JSX

* Reusable Components

* Performance Enhancement: ReactJS improves performance due to virtual DOM.

* Scope for Testing the Codes: ReactJS applications are extremely easy to test. It offers a scope where the developer can test and debug their codes with the help of native tools.

* Native Approach: React can be used to create mobile applications (React Native).

* SEO Friendly: The ability to react to handle common search engine issues such as its failure to read JavaScript high volume apps is another benefit of using React JS framework o develop your software today.

### downsides

* The high pace of development: The high pace of development has an advantage and disadvantage both. In case of disadvantage, since the environment continually changes so fast, some of the developers not feeling comfortable to relearn the new ways of doing things regularly. They need to be always updated with their skills and learn new ways of doing things.

* Poor Documentation: Due to fast-moving nature and the library receiving constant updates, documentation, which is the most crucial part, remains poor.
For example, there is not enough time to make proper documentation and help developers carrying out fast development.

* View Part: ReactJS Covers only the UI Layers of the app and nothing else. So you still need to choose some other technologies to get a complete tooling set for development in the project.

* JSX: Yes, JSX is a barrier as it is complex for new developers to understand its complexity correctly and work on the projects like a pro.

### conclusion

React is a lightweight, powerful, battle-tested library for building user interfaces with JavaScript. It's not a full framework, but rather a powerful tool that may well change the way you approach front-end development.
