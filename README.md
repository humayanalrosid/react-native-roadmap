# Practical React Native Roadmap for Android App Development (Using Expo)

## Description
This roadmap is designed for individuals with basic JavaScript knowledge who want to build Android apps using React Native without Android Studio. Using Expo, you’ll focus on practical, hands-on topics for Android app development with limited resources. Each section includes essential JavaScript prerequisites for React Native topics, so you can build the necessary skills step-by-step without theories or interview-focused content.

---

### **1. Setup and Basics with Expo**
- **Goal:** Set up a lightweight environment for React Native development.
- **Steps:**
  - Install **Node.js** and **npm**.
  - Install the **Expo CLI**: `npm install -g expo-cli`
  - Create a new Expo project: `expo init MyFirstApp`
  - Install **Expo Go** on your Android device for testing.

- **JavaScript Topics to Know:**
  - Setting up Node.js and npm.
  - Basic understanding of command-line usage.

- **Practice Projects:**
  1. *Hello World App*: Display a simple "Hello World" text.
  2. *Styled Text*: Display styled text using inline styles.
  3. *Button Click App*: Display a button that shows an alert when clicked.

---

### **2. Core JavaScript Prerequisites**
   - **JavaScript Topics:**
     - Variables, Functions, and ES6+ syntax (let, const, arrow functions)
     - Array methods (`map`, `filter`, `reduce`)
     - Async/Await and Promises

   - **Practice Projects:**
     1. *Calculator Function*: Build a simple function-based calculator.
     2. *Promise Chain*: Practice promise chaining with dummy data.
     3. *Fetch API Data*: Practice async/await by fetching data from a public API.

---

### **3. React Basics Refresher**
   - **JS Prerequisite:** Basic understanding of React components and props.
   - **React Native Topics:**
      - Functional Components
      - State with `useState`
      - Passing Props
      - Basic styling with inline styles in components

   - **JavaScript Topics to Know:**
      - Arrow functions
      - Array methods like `map` and `filter`
      - ES6 modules and imports

   - **Practice Projects:**
     1. *Counter App*: Display a button to increase and display count.
     2. *Greeting App*: Use props to display a greeting message for different names.
     3. *Color Boxes*: Use state to toggle background colors.

---

### **4. Core React Native Components**
   - **JS Prerequisite:** ES6+ Destructuring.
   - **React Native Topics:**
      - View, Text, ScrollView
      - TextInput (for capturing user input)
      - Button and TouchableOpacity (for interactive elements)

   - **JavaScript Topics to Know:**
      - Object and array destructuring
      - Handling user input

   - **Practice Projects:**
     1. *Basic To-Do List*: Add, display, and delete tasks.
     2. *Text Formatter*: Enter text in TextInput and display formatted text.
     3. *Basic Calculator*: Enter numbers in TextInput to add and display result.

---

### **5. Navigation with React Navigation**
   - **JS Prerequisite:** Basic object destructuring and understanding of callback functions.
   - **React Native Topics:**
      - Setting up **React Navigation** in Expo: `expo install @react-navigation/native`
      - Stack Navigation and Bottom Tab Navigation

   - **JavaScript Topics to Know:**
      - Callback functions and function passing
      - Object destructuring

   - **Practice Projects:**
     1. *Profile Navigator*: Navigate between home and profile screens.
     2. *Recipe App with Stack Navigation*: Navigate between a list of recipes and recipe details.
     3. *Shopping App*: Use Bottom Tabs to navigate between categories and cart.

---

### **6. State Management with Context API**
   - **JS Prerequisite:** Object manipulation and understanding of nested functions.
   - **React Native Topics:**
      - Context API for global state
      - Creating and using providers and consumers

   - **JavaScript Topics to Know:**
      - Closures and nested functions
      - Object manipulation

   - **Practice Projects:**
     1. *User Auth App*: Implement login/logout functionality using Context.
     2. *Theme Switcher*: Toggle between light and dark modes across screens.
     3. *Simple Note Keeper*: Manage notes using global state.

---

### **7. Fetching Data with Axios**
   - **JS Prerequisite:** Familiarity with fetch and async/await.
   - **React Native Topics:**
      - Using Axios to fetch data from APIs
      - Displaying data with FlatList

   - **JavaScript Topics to Know:**
      - Using `fetch` and handling JSON data
      - Async/await with error handling

   - **Practice Projects:**
     1. *Movie List*: Fetch and display a list of movies.
     2. *User List*: Fetch a list of users and display it with FlatList.
     3. *GitHub Repo Search*: Search and display GitHub repositories by keyword.

---

### **8. React Native Forms with Formik**
   - **JS Prerequisite:** Knowledge of controlled components in forms.
   - **React Native Topics:**
      - Setting up **Formik** for form handling.
      - Basic form validation and submission.

   - **JavaScript Topics to Know:**
      - Form handling in vanilla JavaScript
      - Basic validation functions

   - **Practice Projects:**
     1. *Sign-up Form*: Collect username, email, and password.
     2. *Feedback Form*: Collect feedback and reset form on submission.
     3. *Simple Contact Form*: Capture name, email, and message.

---

### **9. Local Data Storage with AsyncStorage**
   - **JS Prerequisite:** Async/await understanding and error handling.
   - **React Native Topics:**
      - Storing data locally with **AsyncStorage**.
      - Retrieving and deleting data from AsyncStorage.

   - **JavaScript Topics to Know:**
      - Async functions and promises
      - Error handling with try/catch

   - **Practice Projects:**
     1. *Persistent To-Do List*: Store and retrieve tasks locally.
     2. *Notes Keeper*: Save and retrieve notes locally.
     3. *Basic Expense Tracker*: Track and store expenses with AsyncStorage.

---

### **10. Notifications with Expo Notifications**
   - **JS Prerequisite:** Basic understanding of events.
   - **React Native Topics:**
      - Setup and trigger local notifications.
      - Handling and customizing notification appearance.

   - **JavaScript Topics to Know:**
      - Event listeners and callback functions
      - Basic date and time functions

   - **Practice Projects:**
     1. *Reminder App*: Schedule notifications for daily reminders.
     2. *Birthday Reminder*: Set notifications for upcoming birthdays.
     3. *Event Tracker*: Track and notify for custom events.

---

## **Final Projects**

### **Project 1: Task Manager App**
   - **Requirements:**
      - Task list with add/edit/delete options.
      - Use AsyncStorage to persist tasks.
      - Basic form validation with Formik for task entries.

### **Project 2: Weather Info App**
   - **Requirements:**
      - Fetch current weather data from a public API.
      - Search by city name.
      - Display weather details on a separate screen.

### **Project 3: Simple Budget Tracker**
   - **Requirements:**
      - Add, edit, and delete income/expense entries.
      - Store data with AsyncStorage.
      - Calculate and display total balance.

### **Project 4: Movie Explorer App**
   - **Requirements:**
      - Fetch and display popular movies from a public API.
      - Search movies by title.
      - Use React Navigation for navigating to movie detail screens.

### **Project 5: Fitness Tracker**
   - **Requirements:**
      - Track daily steps and display history.
      - Use context API for managing steps data across screens.
      - Simple form validation with Formik for user profile.

---

### **Additional Tips**
   - Regularly test on **Expo Go** for Android to check app performance and responsiveness.
   - Utilize **React Native Documentation** for quick reference on components and APIs.
   - Make use of Expo’s resources, like their SDK for extra functionalities such as camera and sensors, without the need for Android Studio.

---

> ### **Resources**
> **1. Official React Native Documentation:** [React Native Docs](https://reactnative.dev/docs/getting-started)  
> This is the best place to get started, with detailed explanations on all components, APIs, and concepts.

> **2. Expo Documentation:** [Expo Docs](https://docs.expo.dev/)  
> Expo's documentation provides specific guidance on using React Native with Expo, including unique features like notifications and permissions.

> **3. React Native School:** [React Native School](https://reactnativeschool.com/)  
> Offers free and premium tutorials focusing on specific React Native topics like navigation, animations, and hooks.

> **4. FreeCodeCamp YouTube Channel:** [React Native for Beginners](https://www.youtube.com/watch?v=0-S5a0eXPoc)  
> This in-depth video series covers React Native basics, components, and Expo setup, making it great for beginners.

> **5. "React Native in Action" by Nader Dabit:** [Amazon Link](https://www.amazon.com/React-Native-Action-Nader-Dabit/dp/1617294055)  
> This book takes you from the basics of React Native to more advanced app-building techniques with practical projects.
