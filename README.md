<!DOCTYPE html>
<html>
<head>
<style>
#linear
{
	     
	height: 80px;
    width: 80px;
    margin: 10px 500px;
    text-align: center;
    line-height: 80px;
    border-radius:10%;
    box-shadow: 5px 5px 2px #888888;
    background: red; 
    background: -webkit-linear-gradient(left, red , green); 
    background: -o-linear-gradient(right, red, green);
    background: -moz-linear-gradient(right, red, green);
    background: linear-gradient(to right, red , green);
}
#radial{
    height: 80px;
    width: 80px;
    margin: 10px 600px;
    text-align: center;
    line-height: 80px;
    border-radius:10%;
    box-shadow: 5px 5px 2px #888888;
    background: -webkit-radial-gradient(top,circle,red, yellow, green); 
    background: -o-radial-gradient(top,circle,red , yellow,green);
    background: -moz-radial-gradient(top,circle,red , yellow,green);
    background: radial-gradient(top,circle,red, yellow ,green);
}
#ellipse {
    height: 80px;
    width: 80px;
    margin: 10px 700px;
    text-align: center;
    line-height: 80px;
    border-radius:10%;
    box-shadow: 5px 5px 2px #888888;
    background: red; 
    background: -webkit-radial-gradient(top, red , yellow, green); 
    background: -o-radial-gradient(top, red, yellow,green);
    background: -moz-radial-gradient(top, red, yellow,green);
    background: radial-gradient(to top, red , yellow,green);
}

</style>
</head>
<body>
<div id="linear">Box</div>
<div id="radial">Box</div>
<div id="ellipse">Box</div>
</body>
</html>
