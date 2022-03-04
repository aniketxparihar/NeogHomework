# NeogHomework
## [Async Await Exercises](https://codepen.io/aniketxparihar/pen/WNXLexr?editors=0012)
## [Intro To React](https://codesandbox.io/s/inspiring-resonance-o7rnfz?file=/src/App.js)
` import "./styles.css";
import React,{useState} from "react";

export default function App() {
  // let [passwordOne,setPasswordOne]=useState(null);
  // let [passwordTwo,setPasswordTwo]=useState(null);
  // let [showPassword,setShowPassword]=useState("password");
  // const error="Password Doesn't Match";
  return (
    <div className="App">
      <h1>Thinking in React</h1>

      {/* <h2>Character Counter</h2>
      <input onChange={(e)=>{setCounter(60-e.target.value.length)}}/>
      <div>{counter}</div> */}

       {/* <h2>Password Matcher</h2>
      <input onChange={(e)=>{setPasswordOne(e.target.value)}}/>
      <input onChange={(e)=>{setPasswordTwo(e.target.value)}}/>
      <div>{passwordOne!==passwordTwo?error:""}</div> */}

      {/* <h2>Alphanumeric Password</h2>
      <input onChange={(e)=>{setPasswordOne(e.target.value)}}/>
      <div>{passwordOne.match(/((^[0-9]+[a-z]+)|(^[a-z]+[0-9]+))+[0-9a-z]+$/i)?"":error}</div>
       */}

      {/* <h2>Button Disabled on Mismatch Password</h2>
      <input onChange={(e)=>{setPasswordOne(e.target.value)}}/>
      <input onChange={(e)=>{setPasswordTwo(e.target.value)}}/>
      <button onClick={()=>passwordOne!=null&&passwordTwo!=null?console.log(passwordOne):null} disabled={passwordOne!==passwordTwo}>Submit Password</button>
      <div>{passwordOne!==passwordTwo?error:""}</div> */}

      {/* <h2>Show Password</h2>
      <input type={showPassword} onChange={(e)=>{setPasswordOne(e.target.value)}}/>
      <button onClick={()=>showPassword==="password"?setShowPassword("text"):setShowPassword("password")}>{showPassword==="password"?"Show Password":"Hide Password"}</button> */}
    </div>
  );
} `

