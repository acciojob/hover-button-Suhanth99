# Hover Button

Make a **Submit button** with `black` background & `white` as **font color** & `5px` **border radius** which on hover changes to `yellow` as background & `black` as **font color** with `30px` as **border radius**. 

 Assign `btn` as id to the button.
 
 Do not use any other tag inside the button tag, just use the plain text.
 
 Note: It should not have any border (hint: none at all) but just **border radius**.
<!DOCTYPE html>
<html>
<head>
<style>

.button1 {
  border-width: 5px;
  background-color: black; 
  color: white; 
}

.button1:hover {
   border-width: 30px;
  background-color: yellow;
  color: black;
}
<button class="button button1">Submit button</button>
</style>
</head>
</html>


