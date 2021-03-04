# 30 Days of React

All about React Engineering: processes, best practices, setup guides, and more!

## [Day 1 - JavaScript Refresher](https://github.com/Asabeneh/30-Days-Of-React/blob/master/01_Day_JavaScript_Refresher/01_javascript_refresher.md)

> skip

---

---

## [Day 2 - Getting Started React](https://github.com/Asabeneh/30-Days-Of-React/blob/master/02_Day_Introduction_to_React/02_introduction_to_react.md)

### **Exercises**

---

### **Exercises: What is React?**

1. What is React?

    > React is a JavaScript library, developed by Facebook, to make Web UI Components

2. What is a library?

    > Is a collection of pre-made functions that make development faster and organized

3. What is a single page application?

    > Single-page application stands for just one HTML file to work with

4. What is a component ?

    > A component is just a wrapped function logic or UI code (like a button)

5. What is the latest version of React?

    > right now (05/02/2021) 17.0.1

6. What is DOM?

    > DOM stands for Document Object Model. This Document connects web pages with scripts or programming languages.

7. What is React Virtual DOM?

    > Virtual DOM or VDOM is a technique to store a copy of the "Real DOM" in memory (like a virtual copy) that is syncronized with ReactDOM. This process is called reconciliation. VDOM is faster than traditional DOM.

8. What does a web application or a website(composed of) have?

    > In React, A Web App, or simply Website, is a collection of Components which, together, can do many tasks like a Blog, Store Documents, Games...

### **Exercises: Why React?**

1. Why did you chose to use react?

    > skip

2. What measures do you use to know popularity ?

    > skip

3. What is more popular, React or Vue ?

    > skip

### **Exercises: JSX**

1. What is an HTML element?

    > HTML attributes, as the name says, give attributes to HTML Elements for user interaction.

    ```jsx
    <a href"#link to another place" ></a>
    ```

2. How to write a self closing HTML element?

    ```jsx
    <br />
    ```

3. What is an HTML attribute? Write some of them

    ```jsx
    <div align="center" onClick="doSomething" > code goes here... </div>
    ```

4. What is JSX?

    > JSX is the technique to write HTML inside React JavaScript code making developtment easier and faster.

5. What is babel?

    > Babel is a transcompiler used in JavaScript.

6. What is a transpiler?

    > Babel, in this case, understands ECMAScript (JavaScript standard) and converts it to older JavaScript, thus, keep compatibility between engines and web browsers.

### **Exercises: JSX Elements**

1. What is a JSX element?

    > It the HTML element inside the React/JavaScript

    ```jsx
    const name = (
      <>
        <h1>Breno Rocha</h1>
      </>
    )
    ```

2. Write your name in a JSX element and store it in a name variable

    ```jsx
    const myName = <h1>Breno Rocha</h1>;
    ```

3. Write a JSX element which displays your full name, country, title, gender, email, phone number. Use h1 for the name and p for the rest of the information and store it in a user variable

    ```jsx
    const myFullDetails = (
            <div className="details">
              <h1>Breno Rocha</h1>
              <p>Country: Brazil</p>
              <p>Title: Software Engineer</p>
              <p>Gender: Male</p>
              <p>email: bhrochamail@gmail.com</p>
              <p>+55 99 988775511</p>
            </div>
          );
    ```

4. Write a footer JSX element

    ```jsx
    const footer = (
            <footer>
              <h2>Footer Element</h2>
            </footer>
          );
    ```

### **Exercises: Inline Style**

1. Create a style object for the main JSX

    ```jsx
    const mainStyles = {
    	backgroundColor: 'black'
    }

    <Main style={mainStyles} />
    ```

2. Create a style object for the footer and app JSX

    ```jsx
    const footerStyles = {
    	backgroundColor: 'black'
    }

    <Footer style={mainStyles} />
    ```

3. Add more styles to the JSX elements

    > skip

### **Exercises: Internal Styles**

1. Apply different styles to your JSX elements

    > skip

### **Exercise: Inject data to JSX**

1. Practice how to make JSX element and injecting dynamic data(string, number, boolean, array, object)

    > skip

---

---

## Day 3 - Setting Up

---

### **Exercises: Level 1**

1. What is a module?
2. What is package?
3. What is the difference between a module and a package.
4. What is NPM?
5. What is Webpack?
6. How do you create a new React project?
7. What are the files and folders inside a project folder(package.json, package-lock.json or yarn.lock, .gitignore,node_modules and public)?
8. What is your favorite code editor (I believe that it is Visual Studio Code)?
9. Add different Visual Studio Code extensions to improve your productivity(eg. prettier, ESLint etc).
10. Try to make a different custom module in a different file and import it to index.js.