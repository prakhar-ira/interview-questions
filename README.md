# interview-questions

### what is output of following:
import React, { useState } from "react";
import "./styles.css";

export default function App() {
  const [counter, setCounter] = useState(0);
  return (
    <div className="App">
      <h1>Counter: {counter}</h1>
      <button
        onClick={() => {
          setCounter(counter + 1);
          setCounter(counter + 1);
        }}
      >
        +
      </button>
    </div>
  );
}
