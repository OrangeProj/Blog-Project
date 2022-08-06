<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blog Project</title>
    <link rel="stylesheet" type="text/css" href="blog_project_css.css">
    <style>
        body {
    margin: 0;
}

* {
    box-sizing: border-box;
}

ul {
list-style-type: none;
margin: 0;
padding: 0;
overflow: hidden;
background-color: darkslategrey;
}

li {
float: left;
border-right:1px solid #bbb;
padding: 0, 5px; 
}

li:last-child {
border-left: 1px solid #bbb;
}

li a {
display: block;
color: white;
text-align: center;
padding: 14px 16px;
text-decoration: none;
font-family: sans-serif;
}

li a:hover:not(.active) {
background-color: grey;
}

.active {
background-color: grey;
}

li a, .dropbtn {
display: inline-block;
color: white;
text-align: center;
padding: 14px 16px;
text-decoration: none;
}
li a:hover, .dropdown:hover .dropbtn {
background-color: grey;
}
li.dropdown {
display: inline-block;
position:absolute;
}

.dropdown-content {
display: none;
position: absolute;
background-color: #f9f9f9;
min-width: 160px;
box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
}

.dropdown-content a {
color: black;
padding: 12px 16px;
text-decoration: none;
display: block;
text-align: left;
}

.dropdown-content a:hover {background-color: #f1f1f1}

.dropdown:hover .dropdown-content {
display: block;
}

input[type=text], select {
    width: 100%;
    padding: 12px 20px;
    margin: 8px 0;
    display: inline-block;
    border: 1px solid #ccc;
    border-radius: 4px;
    box-sizing: border-box;
    /**
    border: none;
    border-bottom: 2px solid red;
    **//**red bottom**/
}
/**
input[type=text]:focus {
    border: 3px solid #555;
}
**//**when clicked on**/

input[type=submit] {
    width: 100%;
    background-color: darkslategrey;
    color: white;
    padding: 14px 20px;
    margin: 8px 0;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}

input[type=submit]:hover {
    background-color: grey;
}

div {
    border-radius: 5px;
    background-color: #f2f2f2;
    padding: 40px;
}

textarea {
    width: 100%;
    height: 150px;
    padding: 12px 20px;
    box-sizing: border-box;
    font-size: 16px;
    resize: none;
    border: 1px solid #ccc;
    border-radius: 4px;
}

        #head {
            width: 100%;
            padding: 10px;
            background: url(1594120643734.jpg) repeat;
            text-align: center;
            font-size: 100px;
            font-family: sans-serif;
            color: white;
            border-radius: 0px;
            background-size: cover;
            background-position: center;
            position: relative;
            align-items: center;
            justify-content: center;
        }
        #navigation {
            width: 100%;
            padding: 0px;
            position: sticky;
            top: 0px;
        }
        div {
            float: left;
            margin: 0;
        }
        #box1 {
            width: 400px ;
            padding: 10px;
            background-color: white;
        }
        #box2 {
            width: 400px;
            padding: 10px;
            background-color:  white;
            margin-left: 0px;
        }
        #advert {
            width: 100px;
            height:100vh;
            background-color: white;
            padding: 200px 0px 200px 0px;
            border: 2px solid grey;
            border-radius: 0%;
            border-top: 0px;
            border-left: 0px;
        }
       /**#adverts {
            width: 150px;
            height:10%;
            background-color: white;
            padding: 200px 0px 200px 0px;
            border: 2px  solid grey;
            border-top: 0px;
            border-right: 0px;
            border-radius: 0%;
            float:right;
            position: fixed;
            right:0px;
        }**/
        #adverta {
            width: 150px;
            height:1000%;
            background-color: white;
            padding: 200px 0px 200px 0px;
            border: 2px solid grey;
            border-radius: 0%;
            float:right;
            margin: 30px 0px 30px 0px;
            border-right: 0px;
            position: fixed;
            right: 0px;
            top: 150px;
        }
        #commentbox {
            width: 40%;
            background-color: white;
            padding: 0px;
            margin: 30px 10px 40px 10px;
            clear: both;
        }
        blockquote {
            width: 50%;
            background-color: white;
            border: 2px solid grey;
            padding: 1px;
            clear: both;
            margin: 0px 0px 10px 10px;

        }
        #othernews {
            width: 900px;
            background-color: white;
            border: 2px solid grey;
            padding: 200px;
            clear: both;
            margin: 0px 0px 10px 10px;
        }
        #footer {
            width: 100%;
            padding: 5px 5px 5px 50px;
            background-color: darkslategrey;
            border-radius: 0%;
            font-family: sans-serif;
            color: white;
            clear:both;
            margin:0%;
        }
    </style>
</head>
<body>
    
    <div id="head">BLOG</div>
    <div id="navigation">
        <list>
            <ul>
                <li><a class="active" href="navigation_bar.html">home</a></li>
                <li><a href="z-index_test.html">Chat</a></li>
                <li><a href="iframe_test.html">Friends</a></li>
                <li><a href="rgba.html">Notifications</a></li>
                <li class="dropdown">
                    <a href="#" class="dropbtn">Menue</a>
                    <div class="dropdown-content">
                      <a href="#">Link 1</a>
                      <a href="#">Link 2</a>
                      <a href="#">Link 3</a>
                    </div>
                </li>
                <li style="float:right;"><a href="wwww.gistan.com">Previous</a>/<a>Next</a></li>
                

            </ul>
        </list>
    </div><br>

    <div id="advert"></div>

    <div id="box1"> <h1>The Spanning Heading</h1>
        Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat. Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis at vero eros et accumsan et iusto odio dignissim qui blandit praesent luptatum zzril delenit augue duis dolore te feugait nulla facilisi. Nam liber tempor cum soluta nobis eleifend option congue nihil imperdiet doming id quod mazim placerat facer possim assum.
    </div>

    <div id="box2"><h1>The Spanning Heading</h1>
        Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat. Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis at vero eros et accumsan et iusto odio dignissim qui blandit praesent luptatum zzril delenit augue duis dolore te feugait nulla facilisi. Nam liber tempor cum soluta nobis eleifend option congue nihil imperdiet doming id quod mazim placerat facer possim assum.
    to the moon</div>

    <div id="adverts"></div>

    <div id="commentbox">
        <form action="http://www.w3schools.com/css/action_page.php">
            <label for="fname">First Name</label>
            <input type="text" id="fname" name="firstname">
        
            <label for="lname">Last Name</label>
            <input type="text" id="lname" name="lastname">
        
            <label for="country">State</label>
            <select id="country" name="country">
              <option value="australia">Abia</option>
              <option value="canada">Imo</option>
              <option value="usa" selected>Anambra</option>
            </select>

            <textarea placeholder="comments..."></textarea>
          
            <input type="submit" value="Submit">
        </form>
    </div><br>

    <div id="adverta"></div>

    <blockquote></blockquote>

    <blockquote id="othernews"></blockquote>

    <div id="footer">
        <p>Copyright@Nigeria Copyright Laws</p>
        <p>More info About Us</p>
        <h1>Leave Site</h1>
    </div>

</body>
</html>
