<!DOCTYPE html>
<html lang="en-us">
    <head>
        <meta charset="utf-8">
        <title>Coding (html+css)</title>
        <style>
    body {
        font-family:"Garamond", "Helvetica",monospace, "aerial";
        background:black;
        color:white;
        width:70%;
    }
        p.warning {
            color:red;
            background:orange;
        }
        h1, h2, h3 {
            color:brown;
        }
        #middle {
            color:rgb(247, 5, 247);
        }
        .new {
            color:black;
            background:white;
        }
        a:hover {
            background:green;
            color:blue;
        }
        a:focus {
            background:purple;
            color:yellow;
        }
        .LINK {
            position:fixed;
            margin-left:340px;
            background:rgb(240, 9, 102);
        }
        #up {
            top:50px;
        }
        #upp {
            top:90px;
        }
        #hard {
            color:white;
        }
        table.table {
            color:black;
            background:white;
        }
        a:link {
            color:orange;
        }
        a:visited {
            color:yellow;
        }
        div {
            font-weight:bold;
            color:yellow;
            background:red;
            font-style:italic;
            font-family:"Helvetica", cursive;
        }
        </style>
    </head>
    <body>
    <!--NOT COMPLETE YET-->
    <h4 class="LINK">Links</h4>
    <a class="LINK" id="up" href="https://en.wikipedia.org/wiki/Coding">coding wiki</a>
    <a class="LINK" id="upp" href="https://www.washington.edu/accesscomputing/webd2/student/unit1/module3/html_history.html#:~:text=The%20first%20version%20of%20HTML,HTML%20as%20an%20XML%20language.">history</a>
    <a href="#basics">begenning/basics</a><br>
    <a href="#middle">middle/intermediete</a><br>
    <a href="#hard">hard/advanced</a>
    <p class="warning">NOT TO BE CONFUSED WITH C++<p>
    <h1 style="background:blue;">BASICS</h1>
    <p id="basics"> The first and most basic tag is the body tag. It is the simple tag containing all of your elements. (Please note that there is also &lt;!doctype html!>, &lt;head>, &lt;meta=????>, and &lt;title> tags)</p><br>
    <p>All other basic tools are the comment(&lt;!--???-->), the h1-6, the p(&lt;p>, the break(&lt;br>), and the (/(whatever tag you're using))(pictures are img).</p><!--like this--><h1>h1</h1>
    <h2>h2</h2>
    <h3>h3</h3>
    <h4>h4</h4>
    <h5>h5</h5>
    <h6>h6</h6>
    <h1 id="middle" style="background:orange;">Middle</h1>
    <h4 class="new">Some new tags are the style, color,  and background. The new html tags are <strong>strong</strong>, <em>em/empasis, </em>, div(for background color and color), class, and id.(Also &lt;a href="id here">text&lt;a> for links). All the style related tags are in the table below (you might not agree with my diffuculties)</h4>
    <table class="table">
        <tbody>
            <tr>
                <th>TAG
                <th>WHAT IT DOES
            </tr>
            <tr>
                <td>color
                <td>choses the color of the text
            </tr>
                        <tr>
                <td>background
                <td>what the background is
            </tr>
                        <tr>
                <td> insert thing here {}
                <td>choses the specific thing or things it is changing
            </tr>
                        <tr>
                <td>width and height
                <td>choses the width and height of the text or picture (pictures are img).
            </tr>
                        <tr>
                <td>margin, margin-left, right, bottom, top, padding, border
                <td>margin for position, padding for pushing away from a border, border for outline
            </tr>
                        <tr>
                <td>a:focus just to name 1
                <td>adds neat things (you'll get to the video)
            </tr>
        </tbody>
    </table>
    <h1 id="hard" style="background:red;">HARD</h1>
    <h4> The more advanced ones are like cloud for style, position fixed, relative, or something else, and z-index for positining things.</h4>
    <h4>There will be more in this table below.</h4>
    <table>
        <tbody>
            <tr>
                <th>thing
                <th>what it does
            </tr>
            
            <tr>
                <td>Specificity
                <td>If two style tags are fighting, the one with more specificity or on the bottom wins.
            </tr>
            <tr>
                <td>Style in tags
                <td>works like syle tags (&lt;h1 id="thing" class="things" <div>style:"color:yellow;"</div>&lt;/h1>)</td>
            </tr>
            <tr>
                <td> Button, input, inframe
                <td>Stuff
            </tr>
        </tbody>
    </table>
    </body>
</html>
