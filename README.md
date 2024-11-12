# *REACT JS*

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

*Source: https://www.freecodecamp.org/news/how-to-install-react-a-step-by-step-guide/?fbclid=IwY2xjawGf_alleHRuA2FlbQIxMAABHVeUVZmGFqzHW4k3AYiQa-hQlvki-oq0TDPlOQ4sBfWU4V3FGG2vCJagzA_aem_pZy6iUslQ5-dFkYukL0WUA*

*Node.js web page interface*

After you have downloaded the version of your choice, install it on your computer.

To verify that Node has been installed correctly, open your command prompt when the installation is finished. In your command prompt, type `node -v`, and then press Enter. The version of Node that is currently installed on your computer should be shown by this command.

Here is what it looks like:

![Command Prompt](https://www.freecodecamp.org/news/content/images/2024/01/node-version-1.png)

*Source: https://www.freecodecamp.org/news/how-to-install-react-a-step-by-step-guide/?fbclid=IwY2xjawGf_alleHRuA2FlbQIxMAABHVeUVZmGFqzHW4k3AYiQa-hQlvki-oq0TDPlOQ4sBfWU4V3FGG2vCJagzA_aem_pZy6iUslQ5-dFkYukL0WUA*

*Node version displayed in the command prompt*

If your Node version appears as seen above, congratulations! Node.js has been successfully installed on your PC.

## Step 2. Install React
Now you can go ahead and install React into your project. Let's go through steps together.

To get you familiar with procedure, we'll start by examining the "traditional" method of installing React using create-react-app (CPA).

### Using CPA
Select the directory you wish to use to create your React project while you are still in your command prompt window. Type `cd [directory name]` and then press Enter.

![cd documents](https://www.freecodecamp.org/news/content/images/2024/01/Screenshot-1_30_2024-9_53_23-AM.png)

*Source: https://www.freecodecamp.org/news/how-to-install-react-a-step-by-step-guide/?fbclid=IwY2xjawGf_alleHRuA2FlbQIxMAABHVeUVZmGFqzHW4k3AYiQa-hQlvki-oq0TDPlOQ4sBfWU4V3FGG2vCJagzA_aem_pZy6iUslQ5-dFkYukL0WUA*

*`cd documents` command to go to `documents` directory*

In the image above, you can see that I am navigating to the `documents` directory, where I want to create my React project.

Make a folder in the `documents` directory (or wherever you're creating your project) for your React app. Type `mkdir [folder name]`, then use `cd [newly created folder name]` to navigate to the newly created directory.

Type `npx create-react-app [project name of your choice]` in the newly created folder directory, then wait as your React project is successfully created. The final section should have the text in the image below displayed:

![Complete Installation](https://www.freecodecamp.org/news/content/images/2024/01/React-project-2-1.png)

*Source: https://www.freecodecamp.org/news/how-to-install-react-a-step-by-step-guide/?fbclid=IwY2xjawGf_alleHRuA2FlbQIxMAABHVeUVZmGFqzHW4k3AYiQa-hQlvki-oq0TDPlOQ4sBfWU4V3FGG2vCJagzA_aem_pZy6iUslQ5-dFkYukL0WUA*

*React complete installation in the terminal*

Finally, type `code .` to launch the React project in your code editor. If you are using Visual Studio Code, your code editor should look like this:

![Display](https://www.freecodecamp.org/news/content/images/2024/01/Welcome---reactproject---Visual-Studio-Code-1_30_2024-8_39_40-PM.png)

*Source: https://www.freecodecamp.org/news/how-to-install-react-a-step-by-step-guide/?fbclid=IwY2xjawGf_alleHRuA2FlbQIxMAABHVeUVZmGFqzHW4k3AYiQa-hQlvki-oq0TDPlOQ4sBfWU4V3FGG2vCJagzA_aem_pZy6iUslQ5-dFkYukL0WUA*

*React Complete Installation Display Using CRA*

In the above image, let's go over some of the elements you'll see there.

- Your React package and any additional packages you may install while working on your React project are stored in the `node module` folder. Your React project's design system can be configured with the help of the `node module`.
- As can be seen in the above image, the `src` folder constains all of the files and components used in your react application, including `App.js`, `index.js`, and `App.css`.
- To assist you manage dependencies in your React project, the `package-lock.json` file locks the versions of dependencies that your project uses.

## What us the purpose of React JS?

React JS is designed to help developers build fast, interactive user interfaces with a focus on modularity and efficiency. Key purpose include:
- **Efficient UI Rendering**: The virtual DOM minimizes direct updates, enhancing speed and performance.
- **Reusable Components**: Components make code modular, maintainable, and scalable.
- **Declarative Programming**: The declarative syntax allows developers to focus on what the UI should look like, simplifying coding and debugging.

## Where is React JS used?

React is commonly used in:
- **Web Applications**: For SPAs that need fast, dynamic interfaces without full page reloads.
- **Mobile Applications**: With React Native, developers can build native mobile apps using React principles.
- **Enterprise Applications**: Many large-scale applications benefit from React's modular, efficient architecture.
- **Interactive UIs**: Ideal for dashboards, e-commerce sites, and social media feeds that require frequent updates and interactivity.

## References:
- https://www.freecodecamp.org/news/how-to-install-react-a-step-by-step-guide/?fbclid=IwY2xjawGf_alleHRuA2FlbQIxMAABHVeUVZmGFqzHW4k3AYiQa-hQlvki-oq0TDPlOQ4sBfWU4V3FGG2vCJagzA_aem_pZy6iUslQ5-dFkYukL0WUA
- https://www.geeksforgeeks.org/what-are-the-features-of-reactjs/
- https://jaydevs.com/what-is-react-used-for/
