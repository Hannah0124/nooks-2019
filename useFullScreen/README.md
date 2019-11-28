# Usage

```js
import React, { useRef } from "react";
import ReactDOM from "react-dom";

const App = () => {
 const onFullS = (isFull) => {
   console.log(isFull ? "We are full" : "We are small")
 }
 const { element, triggerFull, exitFull } = useFullscreen(onFullS);
 
 return (
   <div className="App">
     <div ref={element}>
       <img
         src="https://www.dogbreedslist.info/uploads/allimg/dog-pictures/Shiba-Inu-2.jpg"
         alt="shiba inu"
       />
       <button onClick={exitFull}>Exit fullscreen</button>
     </div>
     <button onClick={triggerFull}>Make fullscreen</button>
   </div>
 );
};
```