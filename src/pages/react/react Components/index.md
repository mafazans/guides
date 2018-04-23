---
title: React Component
---

React Component

Building a React app is all about components. An individual React component can be thought of as a
UI component in an app.

We have a hierarchy of one parent component and many child components. We’ll call these
ProductList and Product , respectively:

    1. ProductList : Contains a list of product components
    
    2. Product : Displays a given product
    
Not only do React components map cleanly to UI components, but they are self-contained. The
markup, view logic, and often component-specific style is all housed in one place. This feature makes
React components reusable.

Furthermore, as we’ll see in this chapter and throughout this book, React’s paradigm for component
data flow and interactivity is rigidly defined. In React, when the inputs for a component change, the
framework simply re-renders that component. This gives us a robust UI consistency guarantee:

With a given set of inputs, the output (how the component looks on the page) will always be
the same.
