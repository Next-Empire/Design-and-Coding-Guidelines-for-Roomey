# Roomey Guide and Best Practices

The following document contains a series of best practices and recommendations for building enterprise web applications 
with JavaScript libraries. 

Much of this advice is used internally at the team and certainly applies to building applications with the MERN and Apollo GraphQL
frameworks -- but this JavaScript style guide can also help teams building applications with any framework, or 
even just vanilla JavaScript.

## Mission Statement

Roomey team firmly believes that high quality JavaScript is above all else consistent, and addresses four main pillars:

  - **Readability:** JavaScript code should be clear and easy to understand at first glance
  - **Maintainability:** JavaScript code should be consistent and cohesive
  - **Error Prevention:** JavaScript code should strategically avoid common problems
  - **Performance:** JavaScript code should always consider faster implementations

This style guide will attempt to provide some ground rules for building enterprise web applications with JavaScript and its libraries

These recommendations are based on our own experiences, as well as direct interaction with our enterprise customers.

## Dogma vs Doctrine

Avoid obsessing about code style -- this document is merely a guide, not infallible dogma. It is not intended to be a 
comprehensive list of all "best practices", but rather a list of the most common areas on which people ask our 
opinions. Many others have created [similar documents](Resources.md) and clearly not everyone agrees on every point. 

The overall goal for this document is to help you evaluate what we consider to be the important aspects of "quality" 
code, and ultimately create your own readable, maintainable and scalable JavaScript projects. Our suggestions stand as 
a baseline from which your teams should implement your own strategy for building a high quality JavaScript codebase. 

# Outline

To best articulate Sencha's experience building both frameworks and enterprise applications, we will divide this 
discussion into four parts:

  1. [Readability](./Code-Style_manual/GeneralGuidelines/Readablity.md)
  2. [Maintainability](./Code-Style_manual/GeneralGuidelines/Maintainablity.md)
  3. [Preventing Errors](./Code-Style_manual/GeneralGuidelines/ErrorAndPrevention.md)
  4. [Performance](./Code-Style_manual/GeneralGuidelines/AppPerformance.md)

It is worth noting that many of the points we will cover might fit into more than one of these pillars. 