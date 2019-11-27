# Usage

```js

const App = () => {
  // The default title will be "Loading..."
  const titleUpdater = useTitle("Loading...");
  setTimeout(() => titleUpdater("Home"), 3000);
  
  return (
    <div className="App">
      <div>Hi</div>
    </div>
  );
};
```