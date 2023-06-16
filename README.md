# React

**Why do Front-end frameworks exist ?**

## **_The rise of single-page applications_**

![1](https://github.com/Nikhil235/Learn_React/assets/38100361/f3bce77a-3432-4382-b0ef-e9b4c55584fd)

---

### **_Single-Page Application with vanilla JavaScript ?_**

---

- Front-end Web Application are all about single-page applications

  - **(Handling Data + displaying data in a user interface)**
  - **(User Interface needs to stay in sync with Data)**
  - **(Very hard problem to solve)**

  - ![2](https://github.com/Nikhil235/Learn_React/assets/38100361/5f82893b-afad-45f4-bdff-583fe21466dc)

![3](https://github.com/Nikhil235/Learn_React/assets/38100361/11b5f2a1-6338-4db4-b5bd-b316957fd1c2)

---

---

**_(Problem with JS (jquery))_**

1. Requires lots of direct DOM manipulation and traversing (imperative) -> "Spaghetti code".

2. Data (state) is usually **stored in the DOM**, shared across entire app -> Hard to reason + bugs

### **Why do front-end framework exist**

1. JavaScript Front-end framework exist because ...

   - Keeping a user interface in sync with data is really hard and a lot of work is
   - (Front-end frameworks solve this problem and take hard work away from developers)
   - e.g. Angular | React | Veu | Laveral (Different Approaches, same goal)

2. They enforce a **"Correct"** way of structuring and writing code (Therefore contributing to solving the problem of "speghetti code".)

3. They give developers and teams a consistent way of building front-end applications.

---

## React vs Vanilla JavaScript

**React** => JavaScript library

**Vanilla JavaScript** =>

- Plain js, without any additional libraries and frameworks.
- Directly manipulating the DOM (Document Object Model)
- need to structure your code manually.

---

## What is React ?

**_JS library for building user interface_**

Or

**Extremely popular, declarative, component-based state driven javascript library for building user interface, created by facebook**

---

### React is based on components

- Break down your UI into reusable components.
- Better organization | reusability | maintainability of code.
- Components are the building blocks of user interface in react
  (Buttons, input fields, search bar etc...)

![4](https://github.com/Nikhil235/Learn_React/assets/38100361/8347f863-715d-4e28-bddf-9551203a43cb)

- Build complex UIs by building and combining multiple components.

---

### Virtual DOM

Virtual Representation of DOM (efficiently update only the necessary parts of UI) => (State or props changes)

- Improved performance (rather manually manipulating the real DOM)

---

### React is Declarative

- Describe how components look like and how they work using a **declarative syntax called JSX**

- **Declarative** -> telling React what a component should look like based on current data / state.

- React is abstraction away from DOM : **never touch the DOM**

- JSX : Syntax that combines HTML, CSS, JS as well as referencing other components

---

### State Driven

REACT reacts to state changes by re-rendering the UIs.

![5](https://github.com/Nikhil235/Learn_React/assets/38100361/02beb8cb-a03b-4741-9fc6-e3e61a79df33)

---

### JavaScript **Library** (is react a library or a framework)

- **library** -> Because React is only the "view" layer. We need to pick multiple external libraries to build a complete applications.

- **NEXT.js / Remix** -> Complete frameworks built on top of React

---

### Summary

1. Rendring components on a webpage (UI) based on their current state.

2. Keeping the UI in sync with state, by re-rendering (reacting) when state changes.
