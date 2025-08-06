# Divine-food-hub
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
  "scripts": {
    "start": "react-scripts start",
    "build": "react-scripts build",
    "test": "react-scripts test",
    "eject": "react-scripts eject"
  }
}
