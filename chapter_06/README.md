# Chapter 6
## Routing in Angular 2

**Warning:** Our *Angular 2 Essentials* book, encompassing the code examples available here, is still in Alpha state and therefore the samples provided herein may be subject to change without prior notice.

## Installation

Clone the repository, move to the folder containing the source file for this chapter and install the NPM dependencies by executing the following:

```bash
$ git clone https://github.com/deeleman/angular2-essentials.git
$ cd angular2-essentials/chapter_06
$ npm install
```
A TypeScript project settings file has been made available to ease the project files transpilation into ECMAScript 5.  If you don't have the TypeScript compiler installed, you can [get it here](http://www.typescriptlang.org/). Once installed, you can compile the project by simply executing the `tsc`command in your console. Please refer to the chapter 1 of the book for further instructions.

## Description

Web applications rarely rely on a single piece of content or view, but a myriad of them that compose altogether a complex, multi-faceted browsing experience that traditionally was browser page by page. The Single Page Application introduced a new browsing paradigm and therefore requires a different approach. In this chapter we will learn how to implement advanced browsing functionalities in our application, so we can deliver different pages and create n-tier navigational hierarchies.

### Topics covered

The new RouteConfig decorator along with the RouterOutlet directive provides an easy and convenient tool for creating routes and redirections linked to the full range of components hydrated from our root component, leveraging the HTML5 History API.

### Skills learned

* The RouterConfig decorator.
* The RouterOutlet directive.
* Switching routes and components through routing directives.
* Switching routes and components imperatively.
* Taking advantage of the routing cycle: Filtering requests, triggering actions and protecting content.
* Bootstrapping router bindings in our root component.