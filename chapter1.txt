Introduction to JSX and Babel

- What is JSX
    - JSX stands for JavaScript XML. (***Extensible Markup Language*** )
    - JSX allows us to write HTML in React.
    - JSX makes it easier to write and add HTML in React.
- XML
    - XML stands for eXtensible Markup Language
    - XML is a markup language much like HTML
    - XML was designed to store and transport data
    - XML was designed to be self-descriptive
    - XML is a W3C Recommendation
    - https://www.w3schools.com/xml/xml_whatis.asp
- What is Babel
    - Babel is a very famous **transpiler** that basically allows us to use future JavaScript in today’s browsers. In simple words, it can convert the latest version of JavaScript code into the one that the browser understands
    - JavaScript compiler
    - What is transpiler
        - Transpiler is a tool that is used to convert source code into another source code that is of the same level.


------------------------ Complete lecture Code ----------------------
var React = require("react");
var ReactDom = require("react-dom");

ReactDom.render(<h1>Hello React!</h1>, document.getElementById("root"));
// What to show, where to show
import React from "react";
import ReactDom from "react-dom";

ReactDom.render(
  <div>
    <h1>Hello React!</h1>
    <p>This is a paragraph</p>
  </div>,
  document.getElementById("root")
);