# Usage

```js
import React from "react";
import ReactDOM from "react-dom";
import useAxios from "./useAxios";

const App = () => {
  const { loading, data, refetch } = useAxios({
    url: "https://yts.lt/api/v2/list_movies.json"
  });

  // console.log(`Loading: ${loading}\nError:${error}\nData:${JSON.stringify(data)}`)

  return (
    <div className="App" style={{ height: "1000vh" }}>
      <h1>{data && data.status}</h1>
      <h2>{loading && "Loading"}</h2>
      <button onClick={refetch}>Refetch</button>
    </div>
  );
};
```