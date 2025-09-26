<h1>Mohammad Sayifullah</h1>
<h2>Laporan Intstalasi Git</h2>
<h3>1. Download Git dari link berikut : https://git-scm.com/download/win</h3>
<img width="1919" height="973" alt="image" src="https://github.com/user-attachments/assets/abcb1b2e-4e60-40a0-99fb-5ce7fee7b690" />
- setelah selesai unduh lalu install file.exe
- lanjut next saja sampai finish
<img width="813" height="403" alt="image" src="https://github.com/user-attachments/assets/ebee502e-e8d1-4ab9-ac03-a8a583fed314" />
<h3>2. Config Awal</h3>
masih di git bash untuk konfigurasi nama dan email
- git config --global user.name "Nama Kamu"
- git config --global user.email "email@kamu.com"
<img width="799" height="143" alt="image" src="https://github.com/user-attachments/assets/42de4bf9-fb72-46a2-bcd0-a866804d833b" />
<h3>3. Alur kerja Git</h3>
1.Buat folder dan inisialisasi
mkdir proyek-web
cd proyek-web
git init
2. Buat Beberapa File
echo "<h1>Selamat Datang</h1>" > index.html
mkdir css
echo "body { font-family: sans-serif; }" > css/style.css

3. Cek Status & Masuk ke Staging Area
git status
git add .

4. Simpan Perubahan (Commit)
git commit -m "feat: Inisialisasi proyek dengan file index dan css"

5. Buat Branch Baru
git checkout -b fitur-kontak

6. Buat File Baru di Branch
echo "<h1>Halaman Kontak</h1>" > kontak.html

7. Staging & Commit di Branch
git add .
git commit -m "feat: Menambahkan halaman kontak"

8. Gabungkan Branch (Merge)
git checkout main
git merge fitur-kontak
<h3>4. Membuat repository Github dan dihubungkan dengan git</h3>
git remote add origin https://github.com/NamaUserKamu/proyek-web-pertama.git
git branch -M main
git push -u origin main
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/1f7b40d0-18ce-4dfb-b0a0-afc767708b96" />



