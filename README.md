Disclaimer: This video is the property of its original creator and is shared here for educational/informational purposes only. All rights belong to the original content owner,


If you are the copyright owner and would like this content removed, please contact me directly. rhidzkhan.ahmad99@gmail.com

Other Sources: https://www.typescriptlang.org/docs/


#Building blocks

User Interface - how users will consume and interact with your application.
Routing - how users navigate between different parts of your application.
Data Fetching - where your data lives and how to get it.
Rendering - when and where you render static or dynamic content.
Integrations - what third-party services you use (for CMS, auth, payments, etc.) and how you connect to them.
Infrastructure - where you deploy, store, and run your application code (serverless, CDN, edge, etc.).
Performance - how to optimize your application for end-users.
Scalability - how your application adapts as your team, data, and traffic grow.
Developer Experience - your team's experience building and maintaining your application.

#What is React
- js library for building interactive UI

#What is Next
- its a react framework# nextjs_documentation

#HTML vs DOM
- if you look at the DOM elements inside you browser. you will notice the DOM includes h1 element. the DOM on the page is different from the source code
. or in other words. the original HTML file you created

- this is because the HTML represents the initial page content, whereas the DOM represents the updated page content which
was changed by the JavaScript code you wrote

- updating the DOM with plain JS is very powerful but verbose. imaging if you write like this the code grows and its bye bye

#Imperative vs. declarative
- writing with pure JS to target dom is imperative. imperative programming is giving chef step by step instruction
while declarative is like ordering pizza without being concerned
- react is cosidered declarative

#What is JSX
- JSX is a syntax extension for JS that allows you to desribe your UI in a familiar HTML-like syntax.

#JSX rules
    #Return a single root element
    - return multiple elements from a component wrap them with single parent tag
    #Close all the tags
    - requires tags to be explicitly closed tags like img must be img and wrapping tags like <li>
    #calemCase all of the things
    - JS has limitations on variable names. their names cant contain dashes or be reserved words like class.
    - many of react and html svg are written in camel case 
    - browser dont understand JSX out of the box so you'll need a javascript compiler such as babel
    to transform JSX to JS

#How react updates the UI
    #Understanding YOU UI as a Tree
    - continue reading https://react.dev/learn/understanding-your-ui-as-a-tree