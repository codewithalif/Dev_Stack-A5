# Dev Stack

## 📝 Description
Dev Stack is a modern and responsive web platform designed for developers to manage tasks, track progress, and organize tech stack resources efficiently in one place.

## 🚀 Live Demo
[View Live Project](https://dev-stack-a-05.netlify.app/#)

## 🛠️ Technologies Used
- **React.js**
- **JavaScript (ES6+)**
- **Tailwind CSS**
- **TypeScript**
- **Vite**
- **HTML5 & CSS3**

## ✨ Key Features
1. **Interactive Dashboard:** Easy-to-use interface for managing active tasks and developer tools seamlessly.
2. **Dynamic Filtering:** Filter and search items quickly based on categories and tech stacks.
3. **Fully Responsive Design:** Optimized layouts providing a smooth experience on desktop, tablet, and mobile devices.

## 💡 Frequently Asked Questions (FAQ)

### 1. What is JSX, and why is it used in React?
JSX stands for JavaScript XML. It lets you write HTML code directly inside JavaScript files. It is used in React because it makes building and reading UI components much faster and easier.

---

### 2. What is the difference between props and state?
* **Props (Properties):** Data passed down from a parent component to a child component. They are read-only and cannot be changed by the child.
* **State:** Internal data managed within the component itself. It can change over time based on user interactions.

---

### 3. What does the useState hook do, and where did you use it in this project?
The `useState` hook allows a component to create and manage its own internal state. In this project, it was used to keep track of tasks, manage selected stack categories, and update dynamic content when the user interacts with the page.

---

### 4. What does the useEffect hook do, and why did you need it to load the JSON data?
`useEffect` handles side effects in React, such as fetching data or setting timers. It was used here to load the JSON data once when the component first renders (mounts) onto the screen.

---

### 5. Why does every item in a .map() list need a unique key prop?
React needs a unique `key` to track each list item. When items are added, updated, or deleted, the `key` helps React quickly identify which specific element changed, making rendering faster and preventing UI bugs.

---

### 6. What is conditional rendering? Show one place you used it.
Conditional rendering means showing or hiding UI elements based on a specific condition.
* **Example from this project:** Showing an "Empty Stack" message or icon when no matching items exist in the filtered list.

---

### 7. How do you pass data between parent and child components?
* **Parent to Child:** Pass data directly using standard **props**.
* **Child to Parent:** Pass a **callback function** from the parent to the child as a prop, which the child calls to send updated data back.