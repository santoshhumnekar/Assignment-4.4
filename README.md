<!DOCTYPE html>
<html>
<head>
<style>
#linear
{
	     
	height: 80px;
    width: 80px;
    margin-right: 100cm;
    text-align: center;
    line-height: 80px;
    border-radius:10%;
    box-shadow: 5px 5px 2px #888888;
    background: red; 
    background: -webkit-linear-gradient(left, red , green); 
}
#radial{
    height: 80px;
    width: 80px;
    margin-right: 110cm;
    text-align: center;
    line-height: 80px;
    border-radius:10%;
    box-shadow: 5px 5px 2px #888888;
    background: -webkit-radial-gradient(top,circle,red, yellow, green); 
}
#ellipse {
    height: 80px;
    width: 80px;
    margin-right: 120cm;
    text-align: center;
    line-height: 80px;
    border-radius:10%;
    box-shadow: 5px 5px 2px #888888;
    background: red;
    background: -webkit-radial-gradient(top, red , yellow, green); 
}


</style>
</head>
<body>
<div id="linear">Box</div>
<div id="radial">Box</div>
<div id="ellipse">Box</div>
</body>
</html>
