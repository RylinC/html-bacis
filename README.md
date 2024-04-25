# html-basics
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Basics</title>
</head>
<body>
<!-- Headings -->

<h1>Heading One</h1>
<h2>Heading Two</h2>
<h3>Heading Three</h3>
<h4>Heading Four</h4>
<h5>Heading Five</h5>
<h6>Heading Six</h6>
<hr>


<!-- Paragraph -->
Lorem ipsum dolor, sit amet consectetur adipisicing elit. Aliquam totam, sunt consequatur modi maiores velit excepturi sint vel provident reiciendis eaque animi cupiditate repudiandae commodi molestias nisi voluptatem, nesciunt voluptatum!

<!-- Paragraph -->

Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda eveniet placeat corporis, praesentium iure fuga cum fugit culpa modi enim hic! Ipsum quod nostrum sequi dicta unde facilis cupiditate enim.
<hr>
 <!--Links-->
<a href="https://github.com/" target="_blank">github</a><br>
<a href="https://www.netflix.com/" target="_blank">netflix</a><br>
<a href="https://www.youtube.com/" target="_blank">youtube</a><br>
<hr>

<!-- images -->
<img src="sky.jpeg" alt="sky" height="250">
<img src="Red sky.jpeg" alt="Red Sky" height="250">
<img src="ocean and sky.jpeg" alt="Ocean and Sky">
<br>
<hr>
<!-- list -->
<h2>Favorite Foods</h2>
<ul>
<li>Pasta</li>
<li>Chicken</li>
<li>Tacos</li>
<li>Burgers</li>
<li>Fried Chicken</li>
<li>Spaghetti</li>
</ul>

<h2>Favorite Colors</h2>
<ol>
<li>Black</li>
<li>White</li>
<li>Blue</li>
<li>Red</li>
<li>Gray</li>
<li>Purple</li>
</ol>
<hr>
<!--forms  -->
<h2>html forms</h2>
<form action="/action_page.php">
<label for="fname">First name:</label><br>
<input type="text" id="fname" name="fname" value="Rylin"><br>
<label for="lname">Last name:</label><br>
<input type="text" id="lname" name="lname" value="Crane"><br>
<input type="submit" value="Submit">
</form>

<h2>Checkboxes</h2>
<form>
<form action="/action_page.php">
 <input type="chechbox" id="vehicle1" name="vehicle1" value="Bike">
 <label for="vehicle1"> I have a bike</label><br>
 <input type="chechbox" id="vehicle2" name="vehicle2" value="Car">
 <label for="vehicle2"> I have a car</label><br>
 <input type="chechbox" id="vehicle3" name="vehicle3" value="Boat">
 <label for="vehicle3"> I have a boat</label><br><br>
 <input type="submit" value="Submit">
</form>
<table>
    <thead>
        <tr>
            <th>Name</th>
            <th>Email</th>
            <th>Age</th>
        </tr>
    </thead>
    <tbody>
    </tr>
    <td>Bob Smith</td>
    <td>bob@emai.com</td>
    <td>25</td>
</tr>
<tr>
    <td>Sarah Jones</td>
    <td>sarah@emai.com</td>
    <td>29</td>
    </tr>
    <tr>
        <td>Eric James</td>
    <td>Eric@emai.com</td>
    <td>32</td>
    </tr>
    
</tr>
    </tbody>
</table>




</body>
</html>
