# Usage

```js
import React, { useEffect, useRef } from "react";
import ReactDOM from "react-dom";

const App = () => {
  const sayHover = () => console.log("Somebody hovered!");
  const markedRef = useHover(sayHover);
  return (
    <div className="App">
      <h1 ref={markedRef}>Hello Nooks</h1>;
    </div>
  )
};
```
