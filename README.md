<p align="center">
  <img src="https://www.popwebdesign.net/popart_blog/wp-content/uploads/2018/03/reactjs.jpg">
</p>

<h1 align="center">
    🔧Solutions for the 30 Days of React <br>
    (Challenges made by Asabeneh)
</h1>

# 🏁 [Day 1 - JavaScript Refresher](https://github.com/Asabeneh/30-Days-Of-React/blob/master/01_Day_JavaScript_Refresher/01_javascript_refresher.md)

> **`skip`**

# 🚩 [Day 2 - Getting Started React](https://github.com/Asabeneh/30-Days-Of-React/blob/master/02_Day_Introduction_to_React/02_introduction_to_react.md)

## 🛠️ **Exercises: What is React?**

1. What is React?

    > **React** is a **JavaScript library**, developed by Facebook, to make **Web UI Components**

2. What is a library?

    > Is a collection of pre-made functions that make development faster and organized

3. What is a single page application?

    > Single-page application stands for just one **`HTML`** file to work with

4. What is a component ?

    > A component is just a wrapped function logic or UI code (like a button)

5. What is the latest version of React?

    > right now (05/02/2021) 17.0.1

6. What is DOM?

    > **`DOM`** stands for **Document Object Model**. This Document connects web pages with scripts or programming languages.

7. What is React Virtual DOM?

    > **`Virtual DOM`** or **`VDOM`** is a technique to store a copy of the "Real DOM" in memory (like a virtual copy) that is **synchronized** with **ReactDOM**. This process is called **reconciliation**. **`VDOM`** is **faster** than traditional **`DOM`**.

8. What does a web application or a website(composed of) have?

    > In React, A **Web App**, or simply Website, is a collection of Components which, together, can do many tasks like a Blog, Store Documents, Games...

## 🛠️ **Exercises: Why React?**

1. Why did you chose to use react?

    > **`skip`**

2. What measures do you use to know popularity ?

    > **`skip`**

3. What is more popular, React or Vue ?

    > **`skip`**

## 🛠️ **Exercises: JSX**

1. What is an HTML element?

    > **`HTML attributes`**, as the name says, give attributes to **`HTML Elements`** for user interaction.

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

    > **JSX** is the **technique** to write **`HTML`** inside React JavaScript code making development easier and faster.

5. What is babel?

    > **`Babel`** is a **transcompiler** used in JavaScript.

6. What is a transpiler?

    > **`Babel`**, in this case, understands **ECMAScript** (JavaScript standard) and **converts** it to older JavaScript, thus, keep **compatibility** between engines and web browsers.

## 🛠️ **Exercises: JSX Elements**

1. What is a JSX element?

    > It the **`HTML`** element inside the React/JavaScript

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

## 🛠️ **Exercises: Inline Style**

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

## 🛠️ **Exercises: Internal Styles**

1. Apply different styles to your JSX elements

    > **`skip`**

## 🛠️ **Exercise: Inject data to JSX**

1. Practice how to make JSX element and injecting dynamic data(string, number, boolean, array, object)

    > **`skip`**

# 🚩 [Day 3 - Setting Up](https://github.com/Asabeneh/30-Days-Of-React/blob/master/03_Day_Setting_Up/03_setting_up.md)

## **Exercises: Level 1**

1. What is a module?

    > In React, a **`module`** enables **many or a single** function in your project by **importing or exporting** a new piece of code (a module) in your other JavaScript files

2. What is package?

    > A package is a single module (or multiples of them) **packed together** (see **`NPM`**) and **distributed** on the internet so others can install this package in their projects.

3. What is the difference between a module and a package.

    > A **`module`** is the piece of code which enables one or various functions. A package is just wrapped modules for easy distribution on the Internet.

4. What is NPM?

    > Is the package model of **`Node`**

5. What is Webpack?

    > It is a **`module bundler`** which store all of your **`dependencies`** in one place.

6. How do you create a new React project?

    > You can add React to your project linking React and **`ReactDOM`** via **CDN** link on your **`HTML`** file or by using the **automated `create-react-app`**.

7. What are the files and folders inside a project folder(**`package.json`**, **`package-lock.json`** or **`yarn.lock`**, **`.gitignore`**, **`node_modules`** and **`public`**)?

    > **`skip`**

8. What is your favorite code editor (I believe that it is Visual Studio Code)?

    > **`skip`**

9. Add different Visual Studio Code extensions to improve your productivity(eg. prettier, ESLint etc).

    > **`skip`**

10. Try to make a different custom module in a different file and import it to index.js.

    > **`skip`**

## 🛠️ **Exercises: Level 2**

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

    > 🛰️ **`LIVE DEMO`** **[day 3 - level 2.1](https://codesandbox.io/s/day-3-dcfhb?file=/src/App.js)**

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

    > 🛰️ **`LIVE DEMO`** **[day 3 - level 2.2](https://codesandbox.io/s/day-3-5dsrf)**

## 🛠️ **Exercises: Level 3**

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

    > **[Live demo: Day 3 LEVEL 3](https://codesandbox.io/s/shy-surf-8xbd8?file=/src/App.js)** 🛰️

# 🚩 [Day 4 - Components](https://github.com/Asabeneh/30-Days-Of-React/blob/master/04_Day_Components/04_components.md)

> skip (similar projects already done)

# 🚩 [Day 5 - Props](https://github.com/Asabeneh/30-Days-Of-React/blob/master/05_Day_Props/05_props.md)

## **Exercises: Level 1**

1. What is props in a React component ?

    > In React, **props** are relative to the same concept of **parameters** in JavaScript function. It's useful to **pass functions** and **data** from **parent** to **children Components**

2. How do you access props in a React component ?

    > You can access **props** by calling it directly or by **object destructuring**.

3. What data types can we pass as props to components ?

    > We can pass many types of data in props like functions, strings, arrays, objects...

4. What is a propTypes?

    > In React, **propTypes** is a technique to **force** a **variable** to be the same data type as you specified it.

5. What is a default propTypes?

    > Default propTypes is the **default** data type that we set for a given props

## Exercises: Level 3

> skip (similar projects already done)

# 🚩 [Day 6 - List, Map and Keys](https://github.com/Asabeneh/30-Days-Of-React/blob/master/06_Day_Map_List_Keys/06_map_list_keys.md)

## **Exercises: Level 1**

1. Why you need to map an array ?

    > **Array map() method** is used to modify an array to a **list of JSX.** We can do this by adding HTML elements to each element of an array

2. Why we need keys during mapping an array ?

    > Keys help React to **identify** which **specific** items have **changed**, **added**, or **removed**

3. What is the importance of destructuring your code ?

    > By destructuring you can **avoid repeating yourself**, thus, you will be **efficient** in development

4. Does destructuring make your code clean and easy to read ?

    > Yes, not only you're gaining efficiency with destructuring, but also you have less code written. So it's easier to read and clean (less cluttering)

## **Exercises: Level 2**

1. In the following design, evens are green, odds are yellow and prime numbers are red. Build the following colors using React component

    ![https://github.com/Asabeneh/30-Days-Of-React/raw/master/images/day_6_number_generater_exercise.png](https://github.com/Asabeneh/30-Days-Of-React/raw/master/images/day_6_number_generater_exercise.png)

    ```jsx
    import "./styles.css";

    let number = [];
    for (let i = 0; i < 32; i++) {
      number.push(i);
    }

    const isPrime = (num) => {
      if (num <= 1) return false;
      if (num == 2) return true;

      for (let i = 2; i <= num / 2; i++) {
        if (num % i == 0) {
          return false;
        }
      }
      return num;
    };

    const NumberGenerator = ({ number }) => {
      const list = number.map((num) => <big key={num}>{num}</big>);

      const bigElement = document.querySelectorAll("big");
      bigElement.forEach((num) => {
        if (num.textContent % 2 === 0) {
          num.style.backgroundColor = "#21bf73";
        }

        if (num.textContent % 2 > 0) {
          num.style.backgroundColor = "#fddb3a";
        }

        if (isPrime(num.textContent)) {
          // console.log(num.textContent)
          num.style.backgroundColor = "#fd5e53";
        }
      });

      return <div className="number-container">{list}</div>;
    };

    const Header = () => (
      <div className="app-header">
        <h2>NUMBER GENERATOR</h2>
        <NumberGenerator number={number} />
      </div>
    );

    export default function App() {
      return (
        <div className="App">
          <Header />
        </div>
      );
    }
    ```

    > 🛰️ **`LIVE DEMO`** **[day - 6 level 2.1](https://codesandbox.io/s/day-6-level-21-2y0ub?file=/src/App.js:0-1094)**

2. Create the following hexadecimal colors using React component

    ![https://github.com/Asabeneh/30-Days-Of-React/raw/master/images/day_6_hexadecimal_colors_exercise.png](https://github.com/Asabeneh/30-Days-Of-React/raw/master/images/day_6_hexadecimal_colors_exercise.png)

    ```jsx
    import "./styles.css";

    let number = [];
    for (let i = 0; i < 32; i++) {
      number.push(i);
    }

    const hexColors = () => {
      const hexString = "0123456789abcdef";
      let color = "";
      for (let i = 0; i < 6; i++) {
        let index = Math.floor(Math.random() * hexString.length);
        color += hexString[index];
      }
      return "#" + color;
    };

    const NumberGenerator = ({ number }) => {
      const list = number.map((num) => <big key={num}>{}</big>);

      const bigElement = document.querySelectorAll("big");
      bigElement.forEach((num) => {
        num.style.backgroundColor = hexColors();
        num.textContent = hexColors();
      });

      return <div className="number-container">{list}</div>;
    };

    const Header = () => (
      <div className="App-header">
        <h2>HEXADECIMAL COLORS</h2>
        <NumberGenerator number={number} />
      </div>
    );

    export default function App() {
      return (
        <div className="App">
          <Header />
        </div>
      );
    }
    ```

    > 🛰️ **`LIVE DEMO`** **[day - 6 level 2.2](https://codesandbox.io/s/day-6-level-22-tooek?file=/src/App.js)**

## **Exercises: Level 3**

1.Make the following bar group using the given [data](https://github.com/Asabeneh/30-Days-Of-React/blob/master/06_Day_Map_List_Keys/06_map_list_keys_boilerplate/src/data/ten_most_highest_populations.js)

![https://github.com/Asabeneh/30-Days-Of-React/raw/master/images/day_6_ten_highest_populations_exercise.png](https://github.com/Asabeneh/30-Days-Of-React/raw/master/images/day_6_ten_highest_populations_exercise.png)

```jsx
import "./App.css";
import { countries } from "./data/countries";

countries.sort((a, b) => b.population - a.population).splice(10);

const worldPopulation = countries
  .map((country) => country.population)
  .reduce((curr, sum) => curr + sum);

const CountryName = ({ country: { name } }) => {
  return (
    <div className="country-name">
      <strong>{name}</strong>
    </div>
  );
};

const CountryPopulation = ({ country: { population } }) => {
  return (
    <div className="country-population">
      <strong>{population}</strong>
    </div>
  );
};

const WorldPopulation = () => {
  return (
    <div className="world-container">
      <big>WORLD</big>
      <progress
        value={worldPopulation}
        max={worldPopulation}
        className="graph-bar"
      ></progress>
      <div className="world-population">{worldPopulation}</div>
    </div>
  );
};

const Top10Population = ({ countries }) => {
  const countriesList = countries.map((country) => (
    <div className="graph-container">
      <CountryName country={country} />
      <progress
        value={country.population}
        max={worldPopulation}
        className="graph-bar"
      ></progress>
      <CountryPopulation country={country} />
    </div>
  ));

  return (
    <div>
      <WorldPopulation />
      {countriesList}
    </div>
  );
};

const Header = () => (
  <div className="App-header">
    <h1>WORLD POPULATION</h1>
    <sub>Ten most populated countries</sub>
    <Top10Population countries={countries} />
  </div>
);

const App = () => (
  <>
    <Header />
  </>
);

export default App;
```

> 🛰️ **`LIVE DEMO`** **[day - 6 level 3.1](https://codesandbox.io/s/day-6-level-3-k6zo7?file=/src/App.js:0-1592)**

# 🚩 [Day 7 - Class Components](https://github.com/Asabeneh/30-Days-Of-React/blob/master/07_Day_Class_Components/07_class_components.md)

## **Exercises: Level 1**

1. How do you write a pure JavaScript function
2. What is inheritance and how do you make a child from a parent class?
3. What is class based React component ?
4. What is the difference between functional React component and class based React component ?
5. When do we need to use class based components instead of functional components
6. What is the use cases of class based component ?
7. Which type of component do use most frequently ? functional or class-based component
8. What is React life cycle ? (not covered yet) ?
9. What is state in React ? (not covered yet)

## **Exercises: Level 2**

Learn more about class based component by changing previous days exercises to class based components

> skip

# 🚩 [Day 8 - States](https://github.com/Asabeneh/30-Days-Of-React/blob/master/08_Day_States/08_states.md)

### **Exercises: Level 1**

1. What was your state today? Are you happy? I hope so. If you manage to make it this far you should be happy.

    > skip

2. What is state in React ?

    > In React, **state** is a **object** which store the **state changes** in Components and **update** (re-render) them when necessary.

3. What is the difference between props and state in React ?

    > In React props are relative to Component Properties and have the same functionally as JavaScript **paramenters** to pass data from a Component to Another like a **data carrier**. Thus, it has a **different function** than state which just store React State changes

4. How do you access state in a React component ?

    > You can access React State by using the keyword ***this***

    ```jsx
    // LIKE SO
    accessState: this.state
    ```

5. How do you set a state in a React component ?

    > You can set a state in React by using this.setState

    ```jsx
    // LIKE SO
    stateSetter = this.setState()
    ```

### **Exercises: Level 2**

1. Use React state to change the background of the page. You can use this technique to apply a dark mode for your portfolio.

    ![https://github.com/Asabeneh/30-Days-Of-React/raw/master/images/08_day_changing_background_exercise.gif](https://github.com/Asabeneh/30-Days-Of-React/raw/master/images/08_day_changing_background_exercise.gif)

    ```jsx
    import React from "react";
    import asabenehImage from "./images/asabeneh.jpg";

    // Fuction to show month date year

    // User Card Component
    const UserCard = ({ user: { firstName, lastName, image } }) => (
      <div className="user-card">
        <img src={image} alt={firstName} />
        <h2>
          {firstName}
          {lastName}
        </h2>
      </div>
    );

    // A button component
    const Button = ({ text, onClick, style }) => (
      <button style={style} onClick={onClick}>
        {text}
      </button>
    );

    // CSS styles in JavaScript Object
    const buttonStyles = {
      backgroundColor: "#61dbfb",
      padding: 10,
      border: "none",
      borderRadius: 5,
      margin: 3,
      cursor: "pointer",
      fontSize: 18,
      color: "white"
    };

    // class based component
    class Header extends React.Component {
      render() {
        console.log(this.props.data);
        const {
          welcome,
          title,
          subtitle,
          author: { firstName, lastName },
          date
        } = this.props.data;

        return (
          <header style={this.props.styles}>
            <div className="header-wrapper">
              <h1>{welcome}</h1>
              <h2>{title}</h2>
              <h3>{subtitle}</h3>
              <p>
                {firstName} {lastName}
              </p>
              <small>{date}</small>
            </div>
          </header>
        );
      }
    }

    const Count = ({ count, addOne, minusOne }) => (
      <div>
        <h1>{count} </h1>
        <div>
          <Button text="+1" onClick={addOne} style={buttonStyles} />
          <Button text="-1" onClick={minusOne} style={buttonStyles} />
        </div>
      </div>
    );

    // TechList Component
    // class base component
    class TechList extends React.Component {
      render() {
        const { techs } = this.props;
        const techsFormatted = techs.map((tech) => <li key={tech}>{tech}</li>);
        return techsFormatted;
      }
    }

    // Main Component
    // Class Component
    class Main extends React.Component {
      render() {
        const {
          techs,
          user,
          greetPeople,
          handleTime,
          changeBackground,
          count,
          addOne,
          minusOne
        } = this.props;
        return (
          <main>
            <div className="main-wrapper">
              <p>Prerequisite to get started react.js:</p>
              <ul>
                <TechList techs={techs} />
              </ul>
              <UserCard user={user} />
              <Button
                text="Greet People"
                onClick={greetPeople}
                style={buttonStyles}
              />
              <Button text="Show Time" onClick={handleTime} style={buttonStyles} />
              <Button
                text="Change Background"
                onClick={changeBackground}
                style={buttonStyles}
              />
              <Count count={count} addOne={addOne} minusOne={minusOne} />
            </div>
          </main>
        );
      }
    }

    // Footer Component
    // Class component
    class Footer extends React.Component {
      render() {
        return (
          <footer>
            <div className="footer-wrapper">
              <p>Copyright {this.props.date.getFullYear()}</p>
            </div>
          </footer>
        );
      }
    }

    class App extends React.Component {
      state = {
        count: 0,
        styles: {
          backgroundColor: "white",
          color: "black"
        }
      };
      showDate = (time) => {
        const months = [
          "January",
          "February",
          "March",
          "April",
          "May",
          "June",
          "July",
          "August",
          "September",
          "October",
          "November",
          "December"
        ];

        const month = months[time.getMonth()].slice(0, 3);
        const year = time.getFullYear();
        const date = time.getDate();
        return ` ${month} ${date}, ${year}`;
      };
      addOne = () => {
        this.setState({ count: this.state.count + 1 });
      };

      // method which subtract one to the state
      minusOne = () => {
        this.setState({ count: this.state.count - 1 });
      };
      handleTime = () => {
        alert(this.showDate(new Date()));
      };
      greetPeople = () => {
        alert("Welcome to 30 Days Of React Challenge, 2020");
      };
      changeBackground = () => {
        const colorChange =
          this.state.styles.backgroundColor === "white"
            ? this.setState({
                styles: { backgroundColor: "black", color: "white" }
              })
            : this.setState({
                styles: { backgroundColor: "white", color: "black" }
              });

        this.setState({ colorChange });
      };

      render() {
        const data = {
          welcome: "Welcome to 30 Days Of React",
          title: "Getting Started React",
          subtitle: "JavaScript Library",
          author: {
            firstName: "Asabeneh",
            lastName: "Yetayeh"
          },
          date: "Oct 7, 2020"
        };
        const techs = ["HTML", "CSS", "JavaScript"];
        const date = new Date();
        // copying the author from data object to user variable using spread operator
        const user = { ...data.author, image: asabenehImage };

        return (
          <div className="app" style={this.state.styles}>
            <Header data={data} />
            <Main
              user={user}
              techs={techs}
              handleTime={this.handleTime}
              greetPeople={this.greetPeople}
              changeBackground={this.changeBackground}
              addOne={this.addOne}
              minusOne={this.minusOne}
              count={this.state.count}
            />
            <Footer date={new Date()} />
          </div>
        );
      }
    }

    export default App;
    ```

    > 🛰️ **`LIVE DEMO`** **[day - 8 level 2.1](https://codesandbox.io/s/day-8-level-21-q605x)**

2. After long time of lock down, you may think of travelling and you do not know where to go. You may be interested to develop a random country selector that selects your holiday destination.

    ![https://github.com/Asabeneh/30-Days-Of-React/raw/master/images/08_day_select_country_exercise.gif](https://github.com/Asabeneh/30-Days-Of-React/raw/master/images/08_day_select_country_exercise.gif)

    ```jsx
    import React from "react";
    import "./App.css";
    import { countriesData } from "./data/countries";

    class Header extends React.Component {
      constructor(props) {
        super(props);
      }

      render() {
        const {
          flag,
          name,
          capital,
          language,
          population,
          currency
        } = this.props.country;

        const {
          welcome,
          title,
          subtitle,
          author: { firstName, lastName },
          date
        } = this.props.data;

        return (
          <>
            <header align="center" style={this.props.styles}>
              <div className="header-wrapper">
                <h1>{welcome}</h1>
                <h2>{title}</h2>
                <h3>{subtitle}</h3>
                <p>
                  {firstName} {lastName}
                </p>
                <small>{date}</small>
              </div>
            </header>

            <main align="center">
              <div
                style={{
                  padding: "2vw",
                  boxShadow: "3px 3px 3px rgba(0,0,0,0.3)",
                  backgroundColor: "#f2fac2",
                  borderRadius: "1vw",
                  width: "70%"
                }}
                className="header-wrapper"
              >
                <img
                  style={{
                    width: "30vw",
                    boxShadow: "3px 3px 3px rgba(0,0,0,0.3)"
                  }}
                  src={flag}
                  alt="flag"
                />
                <h1>{name}</h1>
                <ul align="left" className="details">
                  <strong>Capital: </strong> <span>{capital}</span>
                  <br />
                  <strong>Language: </strong> <span>{language}</span>
                  <br />
                  <strong>Population: </strong> <span>{population}</span>
                  <br />
                  <strong>Currency: </strong> <span>{currency}</span>
                </ul>
              </div>
            </main>
          </>
        );
      }
    }

    const buttonStyles = {
      cursor: "pointer",
      backgroundColor: "#61dbfb",
      border: "none",
      padding: "1vw",
      borderRadius: "1vw",
      color: "white",
      textShadow: "1px 1px 1px rgba(0, 0, 0,0.3)",
      fontSize: "calc(1.5vw + 1vmin)"
    };

    const ButtonRandom = ({ onClick, text }) => (
      <button style={buttonStyles} onClick={onClick}>
        {text}
      </button>
    );

    class App extends React.Component {
      state = {
        countryState: Math.floor(Math.random() * countriesData.length)
      };

      render() {
        const data = {
          welcome: "Welcome to 30 Days Of React",
          title: "Getting Started React",
          subtitle: "JavaScript Library",
          author: {
            firstName: "Asabeneh",
            lastName: "Yetayeh"
          },
          date: "Oct 7, 2020"
        };

        function random() {
          return Math.floor(Math.random() * countriesData.length);
        }

        const country = {
          flag: countriesData[this.state.countryState].flag,
          name: countriesData[this.state.countryState].name,
          capital: countriesData[this.state.countryState].capital,
          language: countriesData[this.state.countryState].languages
            .toString()
            .split(",")
            .join(", "),
          population: countriesData[this.state.countryState].population,
          currency: countriesData[this.state.countryState].currency
        };

        return (
          <div style={{ height: "1500px" }} align="center">
            <Header data={data} country={country} />
            <ButtonRandom
              onClick={() => this.setState({ countryState: random() })}
              text="Random Country"
            />
          </div>
        );
      }
    }

    export default App;
    ```

    > 🛰️ **`LIVE DEMO`** **[day - 8 level 2.2](https://codesandbox.io/s/eager-breeze-moue4?file=/src/App.js:0-3436)**
