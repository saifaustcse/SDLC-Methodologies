## SDLC Methodologies Catagories and sub Catagories

![](https://github.com/saifaustcse/SDLC_Methodologies/blob/master/images/backend.png)


# Find me

> If you think that these can be improved in anyway, please do suggest. Pull Request are highly appreciated. Follow me [@Saif(https://www.linkedin.com/in/saif-aust-cse/) for technical updates.


### Table of Contents

| No. | Topic |
| --- | --------- |
|1  | [What are the major features of React?](#what-are-the-major-features-of-react) |
|2  | [How to create components in React?](#how-to-create-components-in-react) |


## Core React

  
1. ### What are the major features of React?

    The major features of React are:

    * It uses **VirtualDOM** instead of RealDOM considering that RealDOM manipulations are expensive.
    * Supports **server-side rendering**.
    * Follows **Unidirectional** data flow or data binding.
    * Uses **reusable/composable** UI components to develop the view.


   **[⬆ Back to Top](#table-of-contents)**
    

    
2. ### How to create components in React?

    There are two possible ways to create a component.

    1. **Function Components:** This is the simplest way to create a component. Those are pure JavaScript functions that accept props object as first parameter and return React elements:

        ```jsx harmony
        function Greeting({ message }) {
          return <h1>{`Hello, ${message}`}</h1>

        }
        ```

    2. **Class Components:** You can also use ES6 class to define a component. The above function component can be written as:

        ```jsx harmony
        class Greeting extends React.Component {
          render() {
            return <h1>{`Hello, ${this.props.message}`}</h1>
          }
        }
        ```


   **[⬆ Back to Top](#table-of-contents)**
  


