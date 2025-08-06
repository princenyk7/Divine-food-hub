Divine-food-hub
import { Card, CardContent } from "@/components/ui/card"; import { Button } from "@/components/ui/button"; import { Input } from "@/components/ui/input"; import { useState } from "react";

export default function DivineFoodHub() { const [order, setOrder] = useState({ item: "", quantity: 1 }); const handleOrder = () => { alert(Order placed: ${order.quantity} x ${order.item}); };

return ( <div className="min-h-screen bg-gradient-to-br from-blue-900 to-black text-white font-sans p-4"> <header className="text-center py-6"> <h1 className="text-4xl font-bold text-yellow-400">Divine Food Hub</h1> <p className="text-lg mt-2">Lalganj Ajhara, Near Saraswati Inter College</p> <p className="text-sm">Open Daily:
`public/`, `src/`, `package.json`, `README:
{
  "name": "divine-food-hub",
  "version": "1.0.0",
  "private": true,
  "dependencies": {
    "react": "^18.2.0",
    "react-dom": "^18.2.0",
    "react-scripts": "5.0.1"
  },
  "scripts# Divine Food Hub Website

This is the official website for Divine Food Hub, Lalganj Ajhara.import React from 'react';
import ReactDOM from 'react-dom/client';
import App from './App';

const root = ReactDOM.createRoot(document.getElementById('root'));
root.render(
  <React.StrictMode>
    <App />
  </React.StrictMode>
);import React from 'react';
import './index.css';

function App() {
  return (
    <div className="app">
      <h1>Divine Food Hub</h1>
      <h2>Lalganj Ajhara, near Saraswati Inter College</h2>
      <p>Opening Hours: 8 AM - 10 PM</p>
      <p>Contact: 7054107714</p>
      <h3>Menu (Veg Only)</h3>
      <ul>
        <li>Burger - ₹40</li>
        <li>Sandwich - ₹30</li>
        <li>Normal Tea - ₹15</li>
      </ul>
      <p>Scenery of cups of coffee and plants on wall</p>
      <p><em>Online ordering available soon...</em></p>
    </div>
  );
}

export default App;body {
  margin: 0;
  font-family: 'Arial', sans-serif;
  background-color: #0b0c10;
  color: #ffffff;
}

.app {
  text-align: center;
  padding: 20px;
}

h1 {
  color: royalblue;
}

h2, h3 {
  color: #ddd;
}

ul {
  list-style: none;
  padding: 0;
}