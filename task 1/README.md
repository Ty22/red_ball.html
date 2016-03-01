<!DOCTYPE html>
<html>
    <head>
        <script type="text/javascript" src="https://storage.googleapis.com/ics-redball/redball.js"></script>
        <script type= "text/javascript">
            function sayhello(){
                alert("hi there");
            }
            //move redball right//
            function moveright(){
                redball.left= redball.left +10;
            }
            //move redball left//
            function moveleft(){
                redball.left= redball.left -10;
        
            }
            //move redball up//
            function moveup(){
                redball.top= redball.top -10;
            }
            //move redball down//
            function movedown(){
                redball.top= redball.top +10;
                 </script>
            </head>
        <body>
             <img Id="redball" src="http://lrn.icstars.org/redball.jpg"></img>   
             <button onclick="sayhello()">Hello World</button>
            <button onclick="moveright()">move right</button> 
            <button onclick="moveleft()">move left</button>
            <button onclick="moveup()">move up</button>
            <button onclick="movedown()">move down</button>
            </body>         
</html>