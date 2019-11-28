# Usage

```js
import useNotification from "@nooks/use-notification";
import React from "react";
import ReactDOM from "react-dom";

const App = () => {
  const triggerNotif = useNotification("Can I take your bread?", {body: "I love spinach bread, don't you?"});

  return (
    <div className="App">
      <button onClick={triggerNotif}>Hello</button>
    </div>
  );
};
```