# Hover Button

Make a **Submit button** with `black` background & `white` as **font color** & `5px` **border radius** which on hover changes to `yellow` as background & `black` as **font color** with `30px` as **border radius**. 

 Assign `btn` as id to the button.
 
 Do not use any other tag inside the button tag, just use the plain text.
 
 Note: It should not have any border (hint: none at all) but just **border radius**.
<!DOCTYPE html>
<html>
<head>
<style>
.button {
  background-color: #4CAF50; /* Green */
  
  color: white;
  padding: 16px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  transition-duration: 0.4s;
  cursor: pointer;
}

.button1 {
  border-width: 5px;
  background-color: black; 
  color: white; 
  border: 2px solid #4CAF50;
}

.button1:hover {
   border-width: 30px;
  background-color: yellow;
  color: black;
}

</style>
</head>
</html>


