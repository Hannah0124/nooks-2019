# Usage

```js
import React from "react";
import ReactDOM from "react-dom";
const App = () => {
  const deleteWorld = () => console.log("Deleting the world.");
  const abort = () => console.log("Aborted.")
  const confirmDelete = useConfirm("Are you sure?", deleteWorld, abort);
  return (
    <div className="App">
      <button onClick={confirmDelete}>Delete the wolrd</button>
    </div>
  );
};
```