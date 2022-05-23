# medott.github.io
brief practices of html i learn today
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>practice table</title>
</head>
<body>
   
 <table body align="center"border="3"cellpadding="5"cellspacing="5">
     <tr>
         <th>Animals</th>
         <th>Trees</th>
         <th>Fruits</th>
         </tr>
         <tr>
             <td>cat</td>
             <td>iroko</td>
             <td>mango</td>
         </tr>
         <tr>
             <td>Dog</td>
             <td>Mahogany</td>
             <td>Orange</td>
         </tr>
         <tr>
             <td>Lion</td>
             <td>Obeche</td>
             <td>Apple</td>
         </tr>
         <tr>
             <td>Elephant</td>
             <td>Teak</td>
             <td>Watermelon</td>
         </tr>
 </table>
 <p>Fill-in your details below</p>
 <form action="mailto:imoruahmed@gmailc.com">
 <label for fullname>Fullname</label>
 <input type="text"placeholder="fullname"id="fullname"><br><br>
 <label for password>password</label>
 <input type="text"placeholder="password"id="password"><br><br>
 <p>what will you register for?</p>
 <input type="radio"value="uiux"name="option"id="uiux">
 <layer for="uiux">uiux</layer><br>
 <input type="radio"value="software"name="option"id="software">
 <layer for="software">software</layer>
 <fieldset>
     <legend align="center">Important information</legend>
     <p>select your courses</p>
     <input type="checkbox"value="maths"name="courses"id="maths">
     <label for="maths">maths</label><br>
     <input type="checkbox"value="english"name="courses"id="english">
     <label for="english">english</label><br>
     <input type="checkbox"value="physics"name="courses"id="physics">
     <label for="physics">physics</label>
 </fieldset><br>
 <fieldset>
     <p>select your favorite food</p>
     <select>
         <option>semo</option>
         <option>wheat</option>
         <option>amala</option>
         <option>rice</option>
         <option>beans</option>
     </select>
 </fieldset>
 <p>Tell us about yourself</p>
 <textarea cols="30"rows="10"></textarea><br>
 <input type="submit"value="send message">
</form>
</body>
</html>
