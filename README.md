<html>
<head>
	<title>Homework</title>
	<link rel="stylesheet" type="text/css" href="style.css">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<meta charset="utf-8">


</head>
<body>
<br><h1>Homework</h1></br>


	<form method="post" action="server.php" >
		<div class="input-group">
			<label>Name :</label>
			<br><input type="text" name="name" value=""></br>
		</div>
		<div class="input-group">
			<label>Weight :</label>
			<br><input type="text" name="weight" value=""></br>
		</div>
		<div class="input-group">
			<label>Height :</label>
			<br><input type="text" name="height" value=""></br>
		</div>
		<br>
		<div class="input-group">
			<button class="btn" type="submit" name="save" >Insert</button>
			<button class="btn" type="submit" name="save" >Update</button>
			<button class="btn" type="submit" name="save" >Delete</button>
		</div>
	</form>
</body>
</html>
