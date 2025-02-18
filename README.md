# PrProgWeb
[Soal_HTML #2_Grup B.pdf](https://github.com/user-attachments/files/18840850/Soal_HTML.2_Grup.B.pdf)


![image](https://github.com/user-attachments/assets/2c5f99ed-bb77-4ca3-9dd9-d579bd27ac5c)


<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form Pendaftaran Asisten Dosen FTI</title>
</head>
<body>
    <h3>Buatalah <b>form HTML</b> dengan ketentuan sebagai berikut:</h3>
    <form action="hasil.html" method="POST">
        <table border="1" cellspacing="0" cellpadding="5">
            <tr>
                <td>
                    <fieldset>
                        <legend><b>Data Diri</b></legend>
                        <table>
                            <tr>
                                <td>NIM:</td>
                                <td><input type="number" name="nim" required></td>
                            </tr>
                            <tr>
                                <td>Nama Lengkap:</td>
                                <td><input type="text" name="nama" required></td>
                            </tr>
                            <tr>
                                <td>Tempat Lahir:</td>
                                <td><input type="text" name="tempat" required></td>
                            </tr>
                            <tr>
                                <td>Tanggal Lahir:</td>
                                <td><input type="date" name="tanggal" required></td>
                            </tr>
                            <tr>
                                <td>Jenis Kelamin:</td>
                                <td>
                                    <input type="radio" name="gender" value="Laki-laki" required> Laki-laki
                                    <input type="radio" name="gender" value="Perempuan" required> Perempuan
                                </td>
                            </tr>
                            <tr>
                                <td>Program Studi:</td>
                                <td>
                                    <select name="prodi" required>
                                        <option value="">--Pilih Program Studi--</option>
                                        <option value="Informatika">Informatika</option>
                                        <option value="Sistem Informasi">Sistem Informasi</option>
                                    </select>
                                </td>
                            </tr>
                            <tr>
                                <td>Upload Foto Diri:</td>
                                <td><input type="file" name="foto" accept="image/*" required></td>
                            </tr>
                        </table>
                    </fieldset>
                </td>
                <td>
                    <fieldset>
                        <legend><b>Data Akademik & Pilihan</b></legend>
                        <table>
                            <tr>
                                <td>IPK Terakhir:</td>
                                <td><input type="number" step="0.01" name="ipk" required></td>
                            </tr>
                            <tr>
                                <td>Mata Kuliah Pilihan:</td>
                                <td>
                                    <input type="checkbox" name="mk1" value="Pemrograman Web"> Pemrograman Web<br>
                                    <input type="checkbox" name="mk2" value="Struktur Data"> Struktur Data<br>
                                    <input type="checkbox" name="mk3" value="Jaringan Komputer"> Jaringan Komputer
                                </td>
                            </tr>
                        </table>
                    </fieldset>
                </td>
            </tr>
            <tr>
                <td colspan="2">
                    <fieldset>
                        <legend><b>Kontak</b></legend>
                        <table>
                            <tr>
                                <td>Email:</td>
                                <td><input type="email" name="email" required></td>
                            </tr>
                            <tr>
                                <td>Nomor Telepon:</td>
                                <td><input type="number" name="telepon" required></td>
                            </tr>
                        </table>
                    </fieldset>
                </td>
            </tr>
            <tr>
                <td colspan="2" align="center">
                    <button type="reset">Reset</button>
                    <button type="submit">Simpan</button>
                </td>
            </tr>
        </table>
    </form>
</body>
</html>



<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form Pendaftaran Asisten Dosen FTI UKDW</title>
</head>
<body>
    <div align="center">
        <img src="logo_universitas.png" alt="Logo Universitas" width="100"><br>
        <h2>Universitas Kristen Duta Wacana</h2>
        <h3>Form Pendaftaran Asisten Dosen FTI UKDW</h3>
    </div>
    <form action="hasil.html" method="POST">
        <table border="1" cellspacing="0" cellpadding="5" align="center">
            <tr>
                <td>
                    <fieldset>
                        <legend><b>Data Diri</b></legend>
                        <table>
                            <tr>
                                <td>NIM:</td>
                                <td><input type="number" name="nim" required></td>
                            </tr>
                            <tr>
                                <td>Nama Lengkap:</td>
                                <td><input type="text" name="nama" required></td>
                            </tr>
                            <tr>
                                <td>Tempat Lahir:</td>
                                <td><input type="text" name="tempat" required></td>
                            </tr>
                            <tr>
                                <td>Tanggal Lahir:</td>
                                <td><input type="date" name="tanggal" required></td>
                            </tr>
                            <tr>
                                <td>Jenis Kelamin:</td>
                                <td>
                                    <input type="radio" name="gender" value="Laki-laki" required> Laki-laki
                                    <input type="radio" name="gender" value="Perempuan" required> Perempuan
                                </td>
                            </tr>
                            <tr>
                                <td>Program Studi:</td>
                                <td>
                                    <select name="prodi" required>
                                        <option value="">--Pilih Program Studi--</option>
                                        <option value="Informatika">Informatika</option>
                                        <option value="Sistem Informasi">Sistem Informasi</option>
                                    </select>
                                </td>
                            </tr>
                            <tr>
                                <td>Upload Foto Diri:</td>
                                <td><input type="file" name="foto" accept="image/*" required></td>
                            </tr>
                        </table>
                    </fieldset>
                    <div align="center">
                        <button type="reset">Reset</button>
                        <button type="submit">Simpan</button>
                    </div>
                </td>
                <td>
                    <fieldset>
                        <legend><b>Data Akademik & Pilihan</b></legend>
                        <table>
                            <tr>
                                <td>IPK Terakhir:</td>
                                <td><input type="number" step="0.01" name="ipk" required></td>
                            </tr>
                            <tr>
                                <td>Mata Kuliah Pilihan:</td>
                                <td>
                                    <input type="checkbox" name="mk1" value="Pemrograman Web"> Pemrograman Web<br>
                                    <input type="checkbox" name="mk2" value="Struktur Data"> Struktur Data<br>
                                    <input type="checkbox" name="mk3" value="Jaringan Komputer"> Jaringan Komputer
                                </td>
                            </tr>
                        </table>
                    </fieldset>
                    <fieldset>
                        <legend><b>Kontak</b></legend>
                        <table>
                            <tr>
                                <td>Email:</td>
                                <td><input type="email" name="email" required></td>
                            </tr>
                            <tr>
                                <td>Nomor Telepon:</td>
                                <td><input type="number" name="telepon" required></td>
                            </tr>
                        </table>
                    </fieldset>
                </td>
            </tr>
        </table>
    </form>
</body>
</html>
