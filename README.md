# Solutions for the 30 Days of React - Challenges made by Asabeneh

## [Day 1 - JavaScript Refresher](https://github.com/Asabeneh/30-Days-Of-React/blob/master/01_Day_JavaScript_Refresher/01_javascript_refresher.md)

> skip

## [Day 2 - Getting Started React](https://github.com/Asabeneh/30-Days-Of-React/blob/master/02_Day_Introduction_to_React/02_introduction_to_react.md)

## **Exercises: What is React?**

1. What is React?

    > **React** is a **JavaScript library**, developed by Facebook, to make **Web UI Components**

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

    > **Virtual DOM** or **VDOM** is a technique to store a copy of the "Real DOM" in memory (like a virtual copy) that is **synchronized** with **ReactDOM**. This process is called **reconciliation**. VDOM is **faster** than traditional DOM.

8. What does a web application or a website(composed of) have?

    > In React, A **Web App**, or simply Website, is a collection of Components which, together, can do many tasks like a Blog, Store Documents, Games...

## **Exercises: Why React?**

1. Why did you chose to use react?

    > skip

2. What measures do you use to know popularity ?

    > skip

3. What is more popular, React or Vue ?

    > skip

## **Exercises: JSX**

1. What is an HTML element?

    > HTML attributes, as the name says, give attributes to HTML **Elements** for user interaction.

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

    > JSX is the **technique** to write HTML inside React JavaScript code making developtment easier and faster.

5. What is babel?

    > Babel is a **transcompiler** used in JavaScript.

6. What is a transpiler?

    > Babel, in this case, understands ECMAScript (JavaScript standard) and **converts** it to older JavaScript, thus, keep **compatibility** between engines and web browsers.

## **Exercises: JSX Elements**

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

## **Exercises: Inline Style**

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

---

## **Exercises: Internal Styles**

1. Apply different styles to your JSX elements

    > skip

## **Exercise: Inject data to JSX**

1. Practice how to make JSX element and injecting dynamic data(string, number, boolean, array, object)

    > skip

## [Day 3 - Setting Up](https://github.com/Asabeneh/30-Days-Of-React/blob/master/03_Day_Setting_Up/03_setting_up.md)

## **Exercises: Level 1**

1. What is a module?

    > In React, a **module** enables **many or a single** function in your project by **importing or exporting** a new piece of code (a module) in your other JavaScript files

2. What is package?

    > A package is a single module (or multiples of them) **packed together** (see **NPM**) and **distributed** on the internet so others can install this package in their projects.

3. What is the difference between a module and a package.

    > A module is the piece of code which enables one or various functions. A package is just wrapped modules for easy distribution on the Internet.

4. What is NPM?

    > Is the package model of Node

5. What is Webpack?

    > It is a module **bundler** which store all of your **dependencies** in one place.

6. How do you create a new React project?

    > You can add **React** to your project linking React and **ReactDOM** via **CDN** link on your HTML file or by using the **automated create-react-app**.

7. What are the files and folders inside a project folder(package.json, package-lock.json or yarn.lock, .gitignore,node_modules and public)?

    > skip

8. What is your favorite code editor (I believe that it is Visual Studio Code)?

    > skip

9. Add different Visual Studio Code extensions to improve your productivity(eg. prettier, ESLint etc).

    > skip

    > skip

10. Try to make a different custom module in a different file and import it to index.js.

## **Exercises: Level 2**

1. Import and render the following images

    ![https://github.com/Asabeneh/30-Days-Of-React/raw/master/images/frontend_technologies.png](https://github.com/Asabeneh/30-Days-Of-React/raw/master/images/frontend_technologies.png)

    ```jsx
    import userImg from './images/asabeneh.jpg';
    import cssImg from './images/css_logo.png';
    import htmlImg from './images/html_logo.png';
    import jsLogo from './images/js_logo.png';
    import reactImg from './images/react_logo.png';
    import "./styles.css";

    const styleImg = {
      display: 'flex',
      margin: '0 auto',
      width: '20vw'
    };

    const techs = (
      <>
        <h1 style={{ textAlign: 'center' }}>FRONT END TECHNOLOGIES</h1>
        <div
          style={{
            display: 'grid',
            gridTemplateColumns: '1fr 1fr 1fr 1fr',
            alignItems: 'center',
            justifyContent: 'center',
            margin: '0 auto'
          }}
        >
          <img style={styleImg} src={cssImg} alt="CSS logo" />
          <img style={styleImg} src={htmlImg} alt="HTML logo" />
          <img style={styleImg} src={jsLogo} alt="React logo" />
          <img style={styleImg} src={reactImg} alt="React logo" />
        </div>
      </>
    );
    ```

    **Live demo:** 

    [https://codesandbox.io/s/day-3-dcfhb?file=/src/App.js](https://codesandbox.io/s/day-3-dcfhb?file=/src/App.js)

2. Use h1, p, input and button HTML elements to create the following design using JSX

![https://github.com/Asabeneh/30-Days-Of-React/raw/master/images/news_letter_design.png](https://github.com/Asabeneh/30-Days-Of-React/raw/master/images/news_letter_design.png)

```jsx
const divStyling = {
  fontFamily: "Montserrat",
  backgroundColor: "#c2e6f4",
  display: "grid",
  borderRadius: "1vw",
  placeItems: "center",
  placeContent: "center",
  textAlign: "center",
  margin: "0 auto",
  height: "100vh"
};

const inputStyling = {
  border: "none",
  borderRadius: "4px",
  margin: "1vw",
  textAlign: "center",
  padding: "1vw"
};

const buttonStyling = {
  border: "none",
  borderRadius: "4px",
  backgroundColor: "#f37474",
  color: "white",
  padding: "1vw 6vw",
  margin: "1vw"
};

const main = (
  <div style={divStyling}>
    <h1>SUBSCRIBE</h1>
    <p>Sign up with your email to receive news and updates</p>
    <div>
      <input style={inputStyling} type="text" placeholder={"First Name"} />
      <input style={inputStyling} type="text" placeholder={"Last Name"} />
      <input style={inputStyling} type="email" placeholder={"email"} />
    </div>
    <button style={buttonStyling} type="submit">
      SUBSCRIBE
    </button>
  </div>
);

export default function App() {
  return <div className="App">{main}</div>;
}
```

**Live demo:** 

[https://codesandbox.io/s/day-3-5dsrf](https://codesandbox.io/s/day-3-5dsrf)

## **Exercises: Level 3**

1. Design the following user card.

![https://github.com/Asabeneh/30-Days-Of-React/raw/master/images/user_card_design_jsx.png](https://github.com/Asabeneh/30-Days-Of-React/raw/master/images/user_card_design_jsx.png)

```jsx
import userImg from "./images/asabeneh.jpg";

const headerStyling = {
  fontFamily: "Montserrat",
  display: "grid",
  alignItems: "left",
  justifyContent: "left",
  width: "100vw",
  textAlign: "center"
};

const imgStyling = {
  borderRadius: "50%",
  height: "25vw"
};

const header = (
  <>
    <div style={headerStyling} className="user-card">
      <img style={imgStyling} src={userImg} alt="user image" />
      <div
        style={{
          display: "inline-flex",
          alignItems: "center",
          justifyContent: "left",
          textAlign: "left",
          margin: "1vw"
        }}
        className="captions"
      >
        <h4 style={{ textAlign: "left" }}>ASABENEH YETAYEH</h4>
        <i
          style={{ color: "green", marginLeft: "1vw" }}
          class="fas fa-check-circle"
        ></i>
      </div>
      <div className="sub">
        <sub style={{ textAlign: "left" }}>Senior Developer Finland</sub>
      </div>
    </div>
  </>
);

const skillsArray = [
  "HTML",
  "CSS",
  "Sass",
  "JS",
  "React",
  "Node",
  "Python",
  "Flask",
  "Django",
  "NumPy",
  "Pandas",
  "Data",
  "Analysis",
  "MySQL",
  "GraphQL",
  "D3.js",
  "Gatsby",
  "Docker",
  "Heroku",
  "Git"
];

const skillsFormatted = skillsArray.map((item) => (
  <ul
    key={item}
    style={{
      display: "inline-flex",
      color: "whitesmoke",
      padding: ".75vw",
      margin: ".25vw",
      backgroundColor: "mediumseagreen",
      borderRadius: "4px"
    }}
  >
    {item}
  </ul>
));

const main = (
  <>
    <div
      style={{ textAlign: "left", margin: "4vw 1vw", fontFamily: "Montserrat" }}
      className="skills"
    >
      <h4>SKILLS</h4>
      <div className="skill-tag">
        <h5>{skillsFormatted}</h5>
      </div>
    </div>
  </>
);

const footer = (
  <>
    <small
      style={{ textAlign: "left", margin: "4vw 1vw", fontFamily: "Montserrat" }}
    >
      Joined on Aug 20, 2020
    </small>
  </>
);

export default function App() {
  return (
    <div className="App">
      {header}
      {main}
      {footer}
    </div>
  );
}
```

**Live demo:** 

[https://codesandbox.io/s/shy-surf-8xbd8?file=/src/App.js](https://codesandbox.io/s/shy-surf-8xbd8?file=/src/App.js)
