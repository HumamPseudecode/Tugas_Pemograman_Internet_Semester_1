<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tugas Pertama HTML</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>    
        <div class="anu">
            <h2>Pendaftaran Mahasiswa</h2>
            <img src="https://www.cic.ac.id/assets/images/cic.png" alt="" width="500" >
            <form action="KenaHack.html" method="post">
                <label for="Nama">NAMA LENGKAP:</label>
                <input type="text" id="Nama" required>
                <br>
                <label for="Nim">NIM:</label>
                <input type="text" id="Nim" required>

                <br>
                <label for="Email">Email:</label>
                <input type="text" id="Email" required equired placeholder="contoh@gmail.com">
                <br>
                <label for=""></label>
                <select name="Program Studi" id="ProgramStudi">
                    <option value="">Pilihan Program Study</option>
                    <option value="">Teknik Informatika</option>
                    <option value="">Bisdi</option>
                    <option value="">Sistem Informasi</option>
                    <option value="">Management Informatika</option>
                    <option value="">Management Bisnis</option>
                    <option value="">Pikor</option>
                </select>
                <label for="jk">Jenis Kelamin</label>
     <div class="gender">
        <label><input type="radio" name="gender" value="Laki-laki" required> Laki-laki</label>
        <label><input type="radio" name="gender" value="Perempuan" required> Perempuan</label>
    </div>
                <div class="itu">
                <button type="submit">kirim</button>
                </select>
                </div>
            </form>

</body>
</html>
