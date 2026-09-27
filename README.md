# 🛍️ Elegant Context (Shopping Cart) - React Project

This e-commerce shopping cart application was built as part of the *"React - The Complete Guide"* course by Maximilian Schwarzmüller. 

The primary goal of this repository is to demonstrate how to manage complex, app-wide state efficiently. It transitions from passing multiple props down deeply nested component trees to using React's built-in Context API and Reducer functions.

## ✨ Features
*   **Product Browsing:** Displays a list of available clothing items with their details and prices.
*   **Interactive Shopping Cart:** Users can add items to their cart, which updates dynamically.
*   **Quantity Management:** Users can increase, decrease, or completely remove item quantities directly from the cart modal.
*   **Dynamic Totals:** Automatically calculates and displays the total price of the items currently in the cart.

## 🚀 Advanced React Concepts Practiced
This project focuses on solving state management bottlenecks in medium-to-large React applications:
*   **The "Prop Drilling" Problem:** Understanding the limitations of passing props through multiple intermediary components that don't actually need the data.
*   **Context API:** Creating a centralized data store using `createContext()` and wrapping the application with a `Context.Provider` to make data globally accessible.
*   **`useContext` Hook:** Consuming the context data and functions directly in the components that need them (like the Product components and the Cart modal) without relying on props.
*   **`useReducer` Hook:** Outsourcing complex state update logic (adding items, updating quantities) into a separate, predictable reducer function. This provides a cleaner alternative to `useState` when multiple state transitions depend on the previous state.
*   **Action Dispatching:** Triggering state changes by dispatching actions (with types and payloads) to the reducer.

## 🛠️ Built With
*   **React.js** (initialized via Vite)
*   **JavaScript (ES6+)**
*   **HTML5 & CSS3**

## ⚙️ Getting Started (Local Setup)

To run this project locally, follow these steps:

1. Clone this repository:
   ```bash
   git clone [https://github.com/BardoczDaniel/ContextAPI.git](https://github.com/BardoczDaniel/ContextAPI.git)
