# Usage

```js
import React, { useEffect, useRef } from "react";
import ReactDOM from "react-dom";

const App = () => {
  const fadeInH1 = useFadeIn(1, 2);
  const fadeInp = useFadeIn(5, 10);

  return (
    <div className="App">
      <h1 {...fadeInH1}>Hello</h1>
      <p {...fadeInp}>lorem ipsum lalalala</p>
    </div>
  );
};
```