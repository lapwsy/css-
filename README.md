# css-
第一次尝试
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>古诗词鉴赏</title>
	<style type="text/css">
		oi {font-size:12px;color:red;}
		.shige{font-size:12px;color:blue;}
		#title{font-size:20px;color:green;}
		#size{font-size:25pt;}
		div {font-weight:bold;color:grey;}
	</style>
</head>
<body>
	<form action="">
		浏览者姓名：<input type="text">
		<input type="submit" value="确认" name="submit">
		<input type="reset" value="重置" name="reset">
	</form>
	<p>如有疑问可查询：<a href="https://baidu.com">百度知道</a></p>
	<hr />
	<div align="center">
		<table>
			<tr>
				<td><h1 id="title">静夜思</h1></td>
			</tr>
			<tr>
				<td><h2>床前明月光</h2></td>
			</tr>
			<tr>
				<td><h2>疑是地上霜</h2></td>
			</tr>
			<tr>
				<td><h2>举头望明月</h2></td>
			</tr>
			<tr>
				<td><h2>低头思故乡</h2></td>
			</tr>
		</table>
	</div>
	<hr />
	<div>
	你最喜爱的是第几句：<br>
	<ol>
		<form action="">
			<oi>1.</oi> <input type="radio" value="1" name="gender" checked="checked">
			<oi class="shige" id="size">2.</oi> <input type="radio" value="2" name="gender" >
			<oi>3.</oi> <input type="radio" value="3" name="gender" >
			<oi>4.</oi> <input type="radio" value="4" name="gender" >
		</form>
	</ol>
	</div>

</body>
</html>
