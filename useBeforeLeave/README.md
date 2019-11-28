# Usage

```js
import React, { useEffect } from "react";
import ReactDOM from "react-dom";
const App = () => {
  const begForLife = () => console.log("Please don't leave.")
  useBeforeLeave(begForLife)
  return (
    <div className="App">
      <h1>Hello</h1>
    </div>
  );
};
```