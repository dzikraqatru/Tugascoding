# Tugascoding.github.io
Tugascodinpunyanabilaadawiyah
<!DOCTYPE html>

<html>
<head>
    <title>Adaw Pacar Haechan</title>
</head>
<body>

    <form action="action_page.php" method="POST">

        <div>
            <label for="fname">First name:</label>
            <input type="text" id="fname" name="fname" placeholder="Nabila" required>
        </div>

        <br>

        <div>
            <label for="lname">Last name:</label>
            <input type="text" id="lname" name="lname" placeholder="Adawiyah" required>
        </div>

        <br>

        <div>
            <label for="pass">Password:</label>
            <input type="password" id="pass" name="pass" maxlength="12" required>
        </div>

        <br>

        <div>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="adawhaechan@gmail.com">
        </div>

        <br>

        <div>
            <label for="phone">No HP:</label>
            <input type="tel" id="phone" name="phone" placeholder="(+62)">
        </div>

        <br>

        <div>
            <label for="bdate">Tanggal lahir:</label>
            <input type="date" id="bdate" name="bdate">
        </div>
        
        <br>

        <div>
            <label for="quantity">Donasi:</label>
            <input type="number" id="quantity" name="quantity" min="0" max="1000000" value="1">
        </div>
        
        <br>

        <div>
            <label for="title">Jenis kelamin:</label>

            <label for="Mr.">Laki-laki</label>
            <input type="radio" id="Mr." name="title" value="Mr.">

            <label for="Mrs.">Perempuan</label>
            <input type="radio" id="Mrs." name="title" value="Mrs.">

        </div>
        
        <br>

        <div>
            <label for="payment">Pembayaran:</label>
            <select id="payment" name="payment">
                <option value="visa">Dana</option>
                <option value="mastercard">Shopeepay</option>
                <option value="giftcard">Gopay</option>
            </select>
        </div>
        
        <br>

        <div>
            <label for="subscribe">Dukung haechan:</label>
            <input type="checkbox" id="subscribe" name="subscribe" min="0" max="99" value="1">
        </div>
        
        <br>

        <div>
            <input type="reset">
        </div>

        <br>

        <div>
            <input type="submit">
        </div>

    </form>

</body>
</html>
