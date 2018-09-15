<!DOCTYPE html>
<html>
<head>
	<title>React First App</title>
	<script type="text/javascript" src=".\react-0.14.3\build\react.js"></script>
	<script type="text/javascript" src=".\react-0.14.3\build\react-dom.js"></script>
</head>
<body>
<div id="mydiv"></div>
<script type="text/javascript">
	ReactDOM.render( 
		React.createElement('h1',null,"Hello World!"),
		document.getElementById('mydiv')
		);
</script>
</body>
</html>
