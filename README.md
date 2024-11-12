# REACT JS

## What is React JS? 

React is an open-source Javascript library that helps you build dynamic user interfaces (UIs). You can use it to build components that represent logically reusable parts of the UI.

### Key Features:
- **Simplicity**: React applications are made up of components, which are independent, reusable pieces of the interface. This modularity helps developers manage complex UIs and makes updating or reusing code easier.
- **Virtual DOM**: DOM stands for Document Object Model. Because it separates into modules and runs the code, it is the most crucial component of the web. JavaScript Frameworks typically update the entire document object model (DOM) at once, which slows down web applications. However, React makes use of virtual DOM, which is an exact copy of real DOM. Every time a web application is modified, the entire virtual DOM is updated first in order to distinguish between the virtual and real DOMs.
- **JSX (JavaScript Syntax Extension)**: JSX is a combination of JavaScript and HTML. It makes your code easy and understand since you can embed Javascript objects inside the HTML elements. Because browsers do not support JSX, the code is transcompiled into JavaScript by the Babel compiler.
- **One-way Data Binding**: As implied by the name, one-way data binding is a one-way flow. React only allows data to flow in one direction: from parent components to child components, or from top to bottom. The child component's properties (props) can communicate with the parent components to change the states based on the inputs supplied, but they are unable to return the data to the parent component.
- **Extension**: We can construct whole UI applications with React's various extensions. It offers server-side rendering and facilitates the development of mobile apps. Flux, Redux, React Native, and other extensions for React allow us design visually appealing user interfaces.

## How to set-up React JS?

### Step 1: Install Node.js
Node.js must be installed on your computer before you can begin the React installation procedure. You can read more about Node.js [here](https://www.freecodecamp.org/news/what-is-node-js/) if you're unfamiliar with it.

Go to the [Node.js website](https://nodejs.org/en/) to install Node. You can choose to download the current version or the suggested version from their website, as seen in the picture below.

![Download Node.js](https://www.freecodecamp.org/news/content/images/2024/01/Node.js.png)

*Source: https://www.freecodecamp.org/news/content/images/2024/01/Node.js.png*

*Node.js web page interface*

After you have downloaded the version of your choice, install it on your computer.

To verify that Node has been installed correctly, open your command prompt when the installation is finished. In your command prompt, type `node -v`, and then press Enter. The version of Node that is currently installed on your computer should be shown by this command.

Here is what it looks like:

![Command Prompt](https://www.freecodecamp.org/news/content/images/2024/01/node-version-1.png)

*Source: https://www.freecodecamp.org/news/content/images/2024/01/node-version-1.png*

*Node version displayed in the command prompt*

If your Node version appears as seen above, congratulations! Node.js has been successfully installed on your PC.

## Step 2. Install React
Now you can go ahead and install React into your project. Let's go through steps together.

To get you familiar with procedure, we'll start by examining the "traditional" method of installing React using create-react-app (CPA).

