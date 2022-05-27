# WorkFLow
Nama: Annisa Laila Rahmawati <br>
NIM : E41200097<br>
TIF A <br>
Repositori ini saya buat untuk memenuhi tugas Literasi Digital <br>

# Clone Repositori WorkFlow
Berikut ini langkah - langkahnya : <br>
1. Membuat sebuah repositori dengan nama WorkFlow pada github.<br>
2. Lakukan clonning repositori di gitbash dengan perintah  https://github.com/Annisa6780/WorkFLow.git <br>
3. Masuk ke direktori WorkFlow dengan perintah cd WorkFLow <br>
4. Tambahkan sebuah file dengan nama matriks.html atau file apasaja yang anda miliki <br>
5. Pindahkan file matriks.html yana ada di working area ke staging area dengan perintah git add . <br>
6. Setelah berhasil, lakukan commit file dengan perintah git commit -m "menambahkan file matriks.html" <br>
7. Ketikkan git push untuk mengupload di github

# Membuat Branch dan Melakukan Marge
Berikut ini langkah - langkahnya : <br>
1. Tambahkan sebuah branch dengan nama tampilan menggunakan perintah git checkout -b tampilan <br>
2. Buat sebuah file yang bernama operasiMatriks.html pada branch tampilan dan ketikkan perintah git add . <br>
3. Lalu ketikkan perintah git commit -m "Menambahkan file operasiMatriks.html" <br>
4. Ketikkan git push --set-upstream origin tampilan <br> <br>
Langkah - langkah untuk menggabungkan file operasiMatriks.html pada branch tampilan menuju branch main : <br>
1. Pindah ke branch main dengan perintah git checkout main <br>
2. Gabungkan file operasiMatriks.html dengan perintah git merge tampilan <br>
3. Ketikkan git push maka penggabungan branch sukses

# Membuat release branch dan hotfix branch
Berikut ini langkah - langkahnya : <br>
1. Gunakan perintah git checkout -b release/v1.0.0 <br>
2. Ketikkan perintah git add . <br>
3. Lalu ketikkan git commit -m "release v1.0.0" <br>
4. Lalukan push dengan perintah git push -u origin release/v1.0.0 <br>
5. Membuat hotfix branch ketikkan perintah git checkout -b hotfix/nama <br>
6. Ketikkan perintah git add . <br>
7. Lalu ketikkan git commit -m "hotfix/nama" <br>
8. Lalukan push dengan perintah git push -u originhotfix/nama <br>
