# React Router DOM Installation and Setup

![React](https://img.shields.io/badge/-React-20232A?logo=react&logoColor=61DAFB&style=for-the-badge)
![React Router](https://img.shields.io/badge/-React%20Router-CA4245?logo=react-router&logoColor=white&style=for-the-badge)

## 📋 Step 1: Install React Router DOM

React Router DOM is a library that allows you to manage routing in your React application easily. To install it, use the following command:

```bash
npm install react-router-dom
```

## 📂 Step 2: Basic Setup

1. Open your App.js file and import the necessary components from react-router-dom.

```js
import React from 'react';
import { BrowserRouter as Router, Routes,Route } from 'react-router-dom';
```

```js
function App() {
    return (
        <Router>
            <div>
                <Routes>
                    <Route path="/" element={<Home />} />
                    <Route path="/about" element={<About />} />
                    <Route path="/contact" element={<Contact />} />
                </Routes>
            </div>
        </Router>
    );
}

const Home = () => <h2>Home Page</h2>;
const About = () => <h2>About Page</h2>;
const Contact = () => <h2>Contact Page</h2>;

export default App;
```
