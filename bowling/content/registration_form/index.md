<!DOCTYPE html>
<html>
<style>

input[type=text], select {
  width: 20;
  padding: 12px 20px;
  margin: 8px 0;
  display: inline-block;
  border: 1px solid #ccc;
  border-radius: 4px;
  box-sizing: border-box;
}

input[type=submit] {
  width: 300px;
  height: 100px;
  background-color: #4CAF50;
  color: white;
  align-items: center;
  margin: 8px 0;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

input[type=submit]:hover {
  background-color: #45a049;
}

form {
  border-radius: 5px;
  background-color: #f2f2f2;
  padding: 20px;
}

textarea {
  width: 50%;
  height: 150px;
  padding: 12px 20px;
  box-sizing: border-box;
  border: 2px solid #ccc;
  border-radius: 4px;
  background-color: #f8f8f8;
  resize: none;
}

input[type=checkbox] {
  height: 30px;
  width: 30px;
}

hr {
  border: 5px solid #ccc;
}
</style>
<body>
  <b><font size ="+6">2019 Registration Form</font>
<form action="/thankyou" method="post" name="2019 Tournament Registration" data-netlify-recaptcha="true" data-netlify="true" netlify-honeypot="bot_field" netlify>
    <p style="visibility: hidden">
        <label> Don't fill this out"</label> <input name=bot_field>
        </p>
    <b><font size="+6">Team Event</font></B>
    <br>
    <br>
    <label for="tname">Team Name</label>
    <br>
    <input type="text" id="tname" name="teamname" placeholder="Your Team Name">
    <br>
    <br>
    Squad Time
    <br>     
    <select name="Team_Squad">
        <option value="SquadA">Squad:</option>
        <option value="SquadA">Squad A</option>
        <option value="SquadB">Squad B</option>
        <option value="SquadC">Squad C</option>
        <option value="SquadD">Squad D</option>
    </select>
    <br>
    <br>
    <label for="bowler1">First Bowler</label>
    <br>
    <input type="text" id="bowler1" name="firstbowler" placeholder="First Bowler">
    <br>
    <br>
    <label for="bowler2">Second Bowler</label>
    <br>
    <input type="text" id="bowler2" name="secondbowler" placeholder="Second Bowler">
    <br>
    <br>
    <label for="bowler3">Third Bowler</label>
    <br>
    <input type="text" id="bowler3" name="thirdbowler" placeholder="Third Bowler">
    <br>
    <br>
    <label for="bowler4">Fourth Bowler</label>
    <br>
    <input type="text" id="bowler4" name="fourthbowler" placeholder="Fourth Bowler">
    <br>
    <hr>
    <br>
    <b><font size="+6">Doubles Pairing 1</font></b>
    <br>
    <br>
    Squad Time
    <br>
    <select name="Doubles_1_Squad">
        <option value="SquadA">Squad:</option>
        <option value="SquadA">Squad A</option>
        <option value="SquadB">Squad B</option>
        <option value="SquadC">Squad C</option>
        <option value="SquadD">Squad D</option>
    </select>
    <br>
    <br>
    <label for="doubles1">Doubles 1 First Bowler</label>
    <br>
    <input type="text" id="doubles1" name="doublesfirstbowler" placeholder="First Bowler">
    <br>
    <br>
    <label for="doubles2">Doubles 1 Second Bowler</label>
    <br>
    <input type="text" id="doubles2" name="doublessecondbowler" placeholder="Second Bowler">
    <br>
    <hr>
    <br>
    <b><font size="+6">Doubles Pairing 2</font></b>
    <br>
    <br>
    Squad Time
    <br>
    <select name="Doubles_2_Squad">
        <option value="SquadA">Squad:</option>
        <option value="SquadA">Squad A</option>
        <option value="SquadB">Squad B</option>
        <option value="SquadC">Squad C</option>
        <option value="SquadD">Squad D</option>
    </select>
    <br>
    <br>
    <label for="doubles3">Doubles 2 First Bowler</label>
    <br>
    <input type="text" id="doubles3" name="doublesthirdbowler" placeholder="First Bowler">
    <br>
    <br>
    <label for="doubles4">Doubles 2 Second Bowler</label>
    <br>
    <input type="text" id="doubles4" name="doublesfourthbowler" placeholder="Second Bowler">
    <br>
    <hr>
    <br>
    <b><font size="+6">Singles</font></b>
    <br>
    <br>
    <label for="singles1">Singles First Bowler</label> 
    <br>
    <input type="text" id="singles1" name="singlesfirstbowler" placeholder="First Bowler">
    <select name="Singles_1_Squad">
        <option value="SquadA">Squad:</option>
        <option value="SquadA">Squad A</option>
        <option value="SquadB">Squad B</option>
        <option value="SquadC">Squad C</option>
        <option value="SquadD">Squad D</option>
    </select>
    <br>
    <br>
    <label for="singles2">Singles Second Bowler</label>
    <br>
    <input type="text" id="singles2" name="singlessecondbowler" placeholder="Second Bowler">
    <select name="Singles_2_Squad">
        <option value="SquadA">Squad:</option>
        <option value="SquadA">Squad A</option>
        <option value="SquadB">Squad B</option>
        <option value="SquadC">Squad C</option>
        <option value="SquadD">Squad D</option>
    </select>
    <br>
    <br>
    <label for="singles3">Singles Third Bowler</label>
    <br>
    <input type="text" id="singles3" name="singlesthirdbowler" placeholder="Third Bowler">
    <select name="Singles_3_Squad">
        <option value="SquadA">Squad:</option>
        <option value="SquadA">Squad A</option>
        <option value="SquadB">Squad B</option>
        <option value="SquadC">Squad C</option>
        <option value="SquadD">Squad D</option>
    </select>
    <br>
    <br>
    <label for="singles4">Singles Fourth Bowler</label>
    <br>
    <input type="text" id="singles4" name="singlesfourthbowler" placeholder="Fourth Bowler">
    <select name="Singles_4_Squad">
        <option value="SquadA">Squad:</option>
        <option value="SquadA">Squad A</option>
        <option value="SquadB">Squad B</option>
        <option value="SquadC">Squad C</option>
        <option value="SquadD">Squad D</option>
    </select>
    <br>
    <hr>
    <br>
    <label for="contact">Contact Info</label>
    <br>
    <textarea id="contact" name="contact" placeholder="Please leave your email address or phone number and preferred contact method (text, call, etc.) so we can confirm your registration." style="height: 300px" style="width:500px"></textarea>
    <br>
    <br>
    <input type="checkbox" required> Check here to submit
    </label>
    <br>
    <br>
    <input type="submit" value="Submit" style="">
</form>