# Usage

```js
import usePreventLeave from "@nooks/use-prevent-leave";
import React from "react";
import ReactDOM from "react-dom";
const App = () => {
  const {enablePrevent, disablePrevent} = usePreventLeave();
  return (
    <div className="App">
      <button onClick={enablePrevent}>Protect</button>
      <button onClick={disablePrevent}>Unprotect</button>
    </div>
  );
};
```