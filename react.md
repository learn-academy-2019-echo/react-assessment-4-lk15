# ASSESSMENT 4: REACT ASSESSMENT
## Interview Practice Questions

Answer the following questions. First, without external resources. Challenge yourself to answer from memory. Then, research the question to expand on your answer. Even if you feel you have answered the question completely on your own, there is always something more to learn.  

1a. Indicate which of the following statements about React are false:

- React is a modern, efficient answer to complex UI applications (true)
- React will only render on the server using Node.js (false)
- React is a full stack framework for modern web applications (false)
- React is a flexible library that plays the role of V in an MVC framework (true)
- You should always update a component's state directly using this.state (false)
- React is made up of encapsulated components that manage their own state (true)
- React components render HTML (true)

1b. Add an interesting TRUE fact about React to the list.
- React uses unidirectional data flow and Flux architecture.

2. What are "smart" and "dumb" components? Explain the difference and also add why we bother to make the distinction between them.

  Your answer: Smart components are components that hold state. Dumb components do not hold state. 

  Researched answer: Smart components focus on how things work, while dumb components focus on how things look. 
  
  Features of smart components:
  -can fetch, capture changes and pass down application data.
  -can call Redux, Lifecycle methods, APIs, Libraries, etc 
  -manage state 

  Features of dumb components:
  -Focus on the UI 
  -Accept props 
  -Require no app dependencies Other than UI packages, like Reactstrap, dumb components do not require dependencies.
  -Rarely include state The only instance where a dumb component has state is for manipulating the UI itself, not application data. Some examples of where a dumb component might have state would be button groups, tabs, switches and other UI elements that do not impact the data, only the UI.
  
  Benefits of distinguishing between smart and dumb components:
  -Creating reusable dumb components that can accept props saves time and effort
  -Improved flexibility to make changes
  -Improve code readability by reducing the amount of code and making code more organized

  
  Reference: https://alligator.io/react/smart-dumb-components/



3. When we use "yarn add ..." in the terminal - what is yarn doing? And what file will always be automatically updated after we add a package with yarn?

  Your answer: Yarn is installing packages

  Researched answer: Yarn installs a package and any packages that it depends on. It will update the package.json and the yarn.lock
  
  Reference: https://yarnpkg.com/lang/en/docs/cli/add/



4. What is the difference between component state and props? Your answer should include a short explanation of both.

  Your answer: State is maintained in a smart component. Props are parts of state that are passed to dumb components to be used in a dumb component (such as displaying a part of state to the user)

  Researched answer: 
  -State is referred to the local state of the component which cannot be accessed and modified outside of the component and only can be used & modified inside the component. 
  -Props make components reusable by giving components the ability to receive data from the parent component in the form of props.
  
  Reference: https://codeburst.io/react-state-vs-props-explained-51beebd73b21

5. How would you explain state to a friend who doesn't know code?

  Your answer: State is a container to hold data about a feature. This data can be changed and then the feature can be updated based on the changed data to be displayed to the user.
