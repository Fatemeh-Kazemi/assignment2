# assignment2

<html>
<head>
	<title>Assignment 2</title>
	<link rel="stylesheet" href="css/style.css">
	<link rel="stylesheet" href="css/fontawesome/css/all.css">
</head>
<body>
	<form action="">

		<table border="2">
			<tr>
				<td>نام</td>
				<td><input type="text" placeholder="name" name="name"></td>
			</tr>
			
			<tr>
				<td rowspan="2">ایمیل</td>
				<td><input type="email" placeholder="email" name="email"></td>
			</tr>

			<tr>
				<td><input type="password" placeholder="password" name="pass"></td>
			</tr>
			
			<tr>
				<td>تاریخ تولد</td>
				<td><input type="date" placeholder="Date" name="date"></td>
			</tr>
			
			<tr>
				<td>سن</td>
				<td><input type="number" placeholder="age" name="age"></td>
			</tr>
			
			<tr>
				<td>رنگ موردعلاقه</td>
				<td><input type="color" name="color"></td>
			</tr>
			
			<tr>
				<td>ماسک مزنی یا نه یره؟</td>
				<td>
					<input type="radio" value="yes" name="mask">
					<label>ماسک مزنم</label>
					<br>
					<input type="radio" value="no" name="mask">
					<label>ماسک نمزنم</label>
				</td>
			</tr>
			
			<tr>
				<td>میوه مورد علاقه</td>
				<td class="fruit">
					<input type="checkbox" name="name"><i class="fa-solid fa-apple-whole apple0"></i>
					<input type="checkbox" name="name"><i class="fa-solid fa-carrot"></i>
					<input type="checkbox" name="name"><i class="fa-solid fa-lemon"></i>
					<input type="checkbox" name="name"><i class="fa-solid fa-apple-whole apple1"></i>
					<input type="checkbox" name="name"><i class="fa-solid fa-pepper-hot"></i>
				</td>
			</tr>
			
			<tr>
				<td>کشور</td>
				<td>
					<select name="country">
						<option value="Iran">ایران</option>
						<option value="America">آمریکا</option>
					</select>
				</td>
			</tr>
			
			<tr>
				<td>زندگینامه</td>
				<td><textarea name="" cols="30" rows="8" placeholder="هرچه میخواهد دل تنگت بگو ..."></textarea></td>
			</tr>
			
			<tr>
				<td colspan="2"><button>نام نویسی</button></td>
			</tr>
		</table>
		
	</form>
</body>
</html>
