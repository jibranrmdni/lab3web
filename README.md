# lab3web
# Praktikum HTML & CSS - Form Data Diri

##  Tujuan
Membuat form HTML yang berfungsi untuk menampilkan data diri pengguna dengan elemen-elemen:
- Text field
- Text area
- Radio button
- Dropdown menu
- Listbox dengan multiple selection  
serta diberikan styling menggunakan CSS.


##  Langkah-Langkah Praktikum

### 1. Membuat Struktur Dasar HTML
Langkah pertama adalah membuat struktur dasar dokumen HTML menggunakan tag:
```html
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>Form Data Diri</title>
</head>
<body>
</body>
</html>

Tag `<head>` berisi informasi meta dan judul halaman, sedangkan isi form ditempatkan di dalam `<body>`.


### 2. Menambahkan Judul Form
Gunakan tag `<h1>` untuk menampilkan judul form agar terlihat jelas.
```html
<h1>FORM DATA DIRI</h1>
```

** Screenshot:**
<img width="371" height="69" alt="Cuplikan layar 2025-10-07 111219" src="https://github.com/user-attachments/assets/3bda6336-c2a2-485b-a4ed-f1b81bbfa618" />


---

### 3. Menambahkan Fieldset dan Legend
Form dikelompokkan menggunakan tag `<fieldset>` dan diberi judul bagian dengan `<legend>` agar lebih terstruktur.
```html
<form>
  <fieldset>
    <legend>DATA DIRI</legend>
  </fieldset>
</form>
```

** Screenshot:**

---

### 4. Menambahkan Input Nama dan Alamat
Input teks untuk nama menggunakan tag `<input type="text">`, sedangkan alamat menggunakan `<textarea>` agar pengguna bisa mengetik lebih panjang.
```html
<label>Nama</label>
<input type="text" name="nama"><br>

<label>Alamat</label>
<textarea name="alamat"></textarea><br>
```

---

### 5. Menambahkan Pilihan Jenis Kelamin
Gunakan tag `<input type="radio">` untuk membuat pilihan tunggal antara “Laki-laki” dan “Perempuan”.
```html
<label>Jenis Kelamin</label>
<input type="radio" name="jk" value="Laki-laki"> Laki-laki
<input type="radio" name="jk" value="Perempuan"> Perempuan<br>
```

---

### 6. Menambahkan Dropdown Menu
Dropdown digunakan untuk memilih **kota**, dibuat dengan tag `<select>`.
```html
<label>Kota</label>
<select name="kota">
  <option value="Jakarta">Jakarta</option>
  <option value="Bandung">Bandung</option>
  <option value="Surabaya">Surabaya</option>
  <option value="Yogyakarta">Yogyakarta</option>
</select><br>
```

---

### 7. Menambahkan Listbox dengan Multiple Selection
Gunakan atribut `multiple` agar pengguna dapat memilih lebih dari satu hobi.
```html
<label>Hobi</label>
<select name="hobi" multiple size="4">
  <option value="Membaca">Membaca</option>
  <option value="Olahraga">Olahraga</option>
  <option value="Musik">Musik</option>
  <option value="Travelling">Travelling</option>
</select><br>
```

---

### 8. Menambahkan Tombol Login
Gunakan tag `<button>` dengan class CSS agar terlihat menarik.
```html
<button type="submit" class="btn">Login</button>
```

---

### 9. Memberikan Styling dengan CSS
Agar tampilan form lebih rapi dan seragam, gunakan CSS:
```css
body {
  font-family: Arial, sans-serif;
  margin: 30px;
}

h1 {
  color: darkgreen;
}

legend {
  color: brown;
  font-weight: bold;
}

input[type="text"], textarea, select {
  border: 1px solid green;
  padding: 4px;
}

.btn {
  background-color: green;
  color: white;
  padding: 6px 15px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}
.btn:hover {
  background-color: darkgreen;
}
```

---

### 10. Hasil Akhir Form
Berikut tampilan akhir form setelah seluruh langkah dijalankan:

**📸 Screenshot Hasil Akhir:**
<img width="602" height="683" alt="Cuplikan layar 2025-10-07 105110" src="https://github.com/user-attachments/assets/35633c77-beae-43f0-becb-7cc5291fa903" />


---

##  Kesimpulan
Dari praktikum ini, kita belajar:
- Cara membuat elemen form dasar menggunakan HTML.
- Cara menampilkan pilihan dengan dropdown dan listbox multiple.
- Cara mempercantik tampilan form menggunakan CSS.
- Pentingnya struktur form yang rapi dan mudah dibaca oleh pengguna.

---

**Dibuat oleh:**  
👤 **Jibran Ramdani**  
📅 *Praktikum Pemrograman Web*  
