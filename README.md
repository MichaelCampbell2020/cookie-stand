# cookie-stand

##Synopsis:

This project is called salmon-cookies and the idea is that my friend owns a business that sells salmon-flavored cookies and I am helping him.
At the top of the file there should be a short introduction and/ or overview that explains what the project is. This description should match descriptions added for package managers (Gemspec, package.json, etc.)

##Code Example
Show what the library does as concisely as possible, developers should be able to figure out how your project solves their problem by looking at the code example. Make sure the API you are showing off is obvious, and that your code is short and concise.

##Motivation

This is lab 6 from code 201. It is to show that I can set up a front facing site and a client facing website.

##Installation
Provide code examples and explanations of how to get the project.

API Reference
Depending on the size of the project, if it is small and simple enough the reference docs can be added to the README. For medium size to larger projects it is important to at least provide a link to where the API reference docs live.

Tests
Describe and show how to run the tests with code examples.

Contributors
Let people know how they can dive into the project, include important links to things like issue trackers, irc, twitter accounts if applicable.

License
A short snippet describing the license (MIT, Apache, etc.)//

##Random Number Generator
// I got this from https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random/
function getRandomIntInclusive(min, max) {
  min = Math.ceil(min);
  max = Math.floor(max);
  return Math.floor(Math.random() * (max - min + 1)) + min; //The maximum is inclusive and the minimum is inclusive 
}//