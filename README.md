<!DOCTYPE html>

<html>

<head>

	<title>Registrasi</title>

</head>

<body>

<form action="contact.php" method="POST">

	<fieldset>

	<legend>Registrasi</legend>

    <p>

    	<label>Nama:</label>

    	<input type="text" name="nama" placeholder="Nama lengkap...">

    </p>

    <p>

    	<label>Username:</label>

    	<input type="text" name="Username" placeholder="Username...">

    </p>

    <p>

    	<label>Email:</label>

    	<input type="email" name="email" placeholder="Your email...">

    </p>

    <p>

    	<label>Password:</label>

    	<input type="password" name="password" placeholder="Your password...">

    </p>

    <p>

    	<label>Jenis Kelamin:</label>

    	<label><input type="radio" name="jenis_kelamin" value="laki-laki">Laki-laki</label>

    	<label><input type="radio" name="jenis_kelamin" value="perempuan">Perempuan</label>

    	<label><input type="radio" name="jenis_kelamin" value="trap">Trap</label>

    </p>

    <p>

    	<label>Agama:</label>

    	<select name="agama">

    		<option value="islam">Islam</option>

    		<option value="kristen">Kristen</option>

    		<option value="hindu">Hindu</option>

    		<option value="budha">Budha</option>

    		<option value="atheis">PKI</option>

    	</select>

    </p>

    <p>

    	<label>Biografi:</label>

    	<textarea name="biografi"></textarea>

    </p>

    <p>

    	<input type="submit" name="submit" value="Daftar">

    </p>

	</fieldset>

</form>

</body>

</html>
