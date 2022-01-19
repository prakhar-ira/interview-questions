# interview-questions

### what is output of following:
```
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
```

### Given a component, find the output for console.log

```
export default function App() {
  return (
    <div className="App">
      <Wrapper>
        <h2 style={{ color: "red", margin: 0 }}>Red</h2>
        <h2 style={{ color: "blue" }}>Blue</h2>
        <h2 style={{ color: "green" }}>Green</h2>
      </Wrapper>
      <Wrapper>hello</Wrapper>
    </div>
  );
}

const Wrapper = ({ children }) => {
  console.log(Length of children) ??
  console.log(typeof children(object, string, array) ??
}
```

### Find the output

```
typeof new String(37) 

typeof String(37)

"37" === "37" 

"37" === new String(37) 

"37" === String(37) 

```

### Difference between require and import


