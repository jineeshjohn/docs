### What are the advantages/benefits and limitations of React?

Following are the advantages/benefits and limitations of React
##### *Advantages/benefits:*
* ReactJS can be used on client and server side too.
* ReactJS components are highly re-usable. 
* React comes with a small API. Beginners will find it easy to learn and start using it.
* ReactJS uses virtual DOM which is JavaScript object. This will improve apps performance since JavaScript virtual DOM is faster than the regular DOM.
* Component and Data patterns improve readability which helps to maintain larger apps.
* ReactJS can be used with other frameworks(Backbone.js, Angular.js) as it is only a view layer..
##### *React Limitations:*
* React only covers view layer of the app so you still need to choose other technologies to get a complete tooling set for development.
* React is using inline templating and JSX. This can seem awkward to some developers.
* React library is too large.

---
### What is the difference between ReactJS and AngularJS?

| NO  | Reactjs                 |	Angualrjs   |
|---  | ---                     |       ---        |
| 1   | Age-4 years             |	Age- 8 years|
| 2   | Facebook	            |   Google      |
| 3   | JSX	                    |   HTML/JS/CSS |
| 4   | View layer              |	Full MVC    |
| 5   | All about components    | 	View, Models, controllers |
| 6   | Less to code	        |   A lot to code |
| 7   | The Library	            |   The Framework |
| 8   | Small	                |   Big |
| 9   | Easy to learn	        |   Not easy as React |
| 9   | Speed-1.34 Seconds	    |   Speed-310 Milliseconds |
| 10  | Virtual DOM	            |   Regular DOM |
| 11  | Rendering Server Side   |	Rendering - Client Side |
| 12  | Abstraction- Weak	    |   Abstraction- Strong |
| 13  | Fails Compile Time	    |   Fails When? - Runtime |
| 14  | Packaging - Strong	    |   Packaging - Weak |

---

### What do you understand by JSX? Explain it.

JSX stands for JavaScript XML. JSX is a preprocessor step that adds XML syntax to JavaScript. 
A JSX expression must have exactly one outermost element. Every JSX element is secretly a call to React.createElement(). JSX just allows you to have XML-like syntax for tags, representing components and elements in React. It's transpiled into pure JavaScript

*An example of a nested JSX expression being saved as a variable:*
```
var theFacebook = (
    <a href="https://www.facebook.com">
        <h1> Click me </h1>
    </a>
);
```

*If a JSX expression takes up more than one line, then you should wrap the multi-line JSX expression in parentheses.*

---
### Why-would-I-use-React-over-AngularJS

|No                 |React|Angular 2|
|---                |---|---|
|Easily upgradeable |Yes|NO|
|Production ready   |Yes|Yes|
|Opinionated        |Less | More |
|Features           |Less | More|
|Reusabiltiy        |Yes|Yes|
|Debugging          |Easy|difficult|
|coding style       |Javascript focussed| html centric|
|Support            |huge community| Ok|

---

### What is virtual DOM(VD)

* A VD object is a lightweight copy of dom object. 
* Any update in VD creates a new tree. The new tree is compared against old tree(diffed) and only the changes are applied to the real dom.
* A VD can update faster then regular DOM
* Any change to jsx will update the VD

---

### What is a state? How to use state?

* State is a JavaScript object that lives inside a component. 
* Updating the state will cause re-rendering the component
* It can be used with expression `${}` or pass it down as `props`

---

### What is synthetic events
It is a wrapper around the browser native event system.

---
### What do you understand by Controlled vs. Uncontrolled Component? ReactJS Interview Question 
Controlled component does not have internal state. All states are get through `props`.
UnControlled component maintains its own internal state.

---
### How does the React Router work? ReactJS Interview Question 
It dictates which components should (or should not) render.

---
### How can you access the currently selected React component in the console?
`$r`

---
