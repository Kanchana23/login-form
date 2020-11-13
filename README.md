# login-form
import React from "react";
import "./styles.css";

export default function App() {
  return (
    <div className="App">
      <h1>Login Form</h1>
      <p>Username: <input type="text" name="username" required></input></p>
      <p><lable for="email_id">Email:  </lable>
      <input type="email" name="email_id" id="email_id" required></input></p>
      <p>password:  <input type="text" name="pwd"></input></p>
      <p><lable for="dob">Date of Birth:  </lable>
      <input type="date" name="dob" id="dob" required></input></p>   
      <button type="button" onclick="alert('Successful')">Login</button>
    </div>
  );
}
