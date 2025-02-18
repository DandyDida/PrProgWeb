# PrProgWeb
[Soal_HTML #2_Grup B.pdf](https://github.com/user-attachments/files/18840850/Soal_HTML.2_Grup.B.pdf)


<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form Pendaftaran Asisten Dosen FTI</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
        }
        header, main, footer {
            width: 80%;
            margin: 0 auto;
            border-bottom: 2px solid #000;
            padding: 10px;
        }
        .header-container {
            display: flex;
            align-items: center;
            justify-content: flex-start;
        }
        .header-container img {
            width: 50px;
            margin-right: 10px;
        }
        form {
            text-align: left;
            margin: auto;
            width: 50%;
        }
        .form-group {
            margin-bottom: 10px;
        }
    </style>
</head>
<body>
    <header>
        <div class="header-container">
            <img src="logo_ukdw.png" alt="Logo UKDW" onclick="window.location.href='https://ukdw.ac.id/'">
            <h1>Universitas Kristen Duta Wacana</h1>
        </div>
    </header>
    <main>
        <h2>Form Pendaftaran Asisten Dosen FTI UKDW</h2>
        <img src="logo_fti.png" alt="Logo FTI" width="250px" onclick="window.location.href='https://ukdw.ac.id/akademik/fakultas-teknologi-informasi/'">
        <form id="formPendaftaran" action="hasil.html" method="POST">
            <fieldset>
                <legend>Data Diri</legend>
                <div class="form-group">
                    <label>NIM:</label>
                    <input type="number" name="nim" max="99999999" required>
                </div>
                <div class="form-group">
                    <label>Nama Lengkap:</label>
                    <input type="text" name="nama" maxlength="50" required>
                </div>
                <div class="form-group">
                    <label>Tempat Lahir:</label>
                    <input type="text" name="tempat" maxlength="50" required>
                </div>
                <div class="form-group">
                    <label>Tanggal Lahir:</label>
                    <input type="date" name="tanggal" required>
                </div>
                <div class="form-group">
                    <label>Jenis Kelamin:</label>
                    <input type="radio" name="gender" value="Laki-laki" required> Laki-laki
                    <input type="radio" name="gender" value="Perempuan" required> Perempuan
                </div>
                <div class="form-group">
                    <label>Program Studi:</label>
                    <select name="prodi" required>
                        <option value="">Pilih...</option>
                        <option value="Informatika">Informatika</option>
                        <option value="Sistem Informasi">Sistem Informasi</option>
                    </select>
                </div>
                <div class="form-group">
                    <label>Upload Foto Diri:</label>
                    <input type="file" name="foto" accept="image/*" required>
                </div>
            </fieldset>
            <fieldset>
                <legend>Data Akademik & Pilihan</legend>
                <div class="form-group">
                    <label>IPK Terakhir:</label>
                    <input type="number" step="0.01" name="ipk" required>
                </div>
                <div class="form-group">
                    <label>Mata Kuliah Pilihan:</label>
                    <input type="checkbox" name="mk1" value="Pemrograman Web"> Pemrograman Web
                    <input type="checkbox" name="mk2" value="Jaringan Komputer"> Jaringan Komputer
                    <input type="checkbox" name="mk3" value="Sistem Basis Data"> Sistem Basis Data
                </div>
            </fieldset>
            <fieldset>
                <legend>Kontak</legend>
                <div class="form-group">
                    <label>Email:</label>
                    <input type="email" name="email" required>
                </div>
                <div class="form-group">
                    <label>Nomor Telepon:</label>
                    <input type="number" name="telepon" max="9999999999999" required>
                </div>
            </fieldset>
            <div class="form-group">
                <button type="reset">Reset</button>
                <button type="submit">Simpan</button>
            </div>
        </form>
    </main>
    <footer>
        <strong>Nama: [Nama Anda] | NIM: [NIM Anda]</strong>
    </footer>
</body>
</html>
