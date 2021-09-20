1. Membuat sebuah folder kosong dengan namamu sendiri = git init wikearvianti.dwiputri
2. Membuat sebuah file dengan nama Readme.md, isi file tersebut dengan kalimat "Halo perkenalkan aku halaman utama" = touch Readme.md 
3. Inisialisasi folder dengan Git, kemudian dokumentasikan menggunakan commit dengan pesan "Inisialisasi Git Repository" = 
    ~ git init .
    ~ git add Readme.md
    ~ git commit -m "Inisialisasi Git Repository"
    ~ git push -u origin master
4. Buat branch baru dengan nama cv = git branch cv
5. Pindah branch kedalam cv, kemudian buat file dengan nama cv.txt dan isi file tersebut dengan kalimat : "Ini adalah file CV" =
    ~ git checkout cv
    ~ touch cv.txt
6. Dokumentasikan menggunakan commit dengan pesan "Inisialisasi CV" = 
    ~ git init .
    ~ git add .
    ~ git commit -m "Inisialisasi CV"
    ~ git push -u origin cv
7. Dokumentasikan menggunakan commit = 
    ~ git commit -m "Inisialisasi CV keempat"
    ~ git push -u origin cv
8. Kembali ke branch master = git checkout master
9. Mendokumentasikan menggunakan commit dengan pesan "update master pertama" = 
    ~ git add .
    ~ git commit -m "update master pertama"
    ~ git push -u origin master
10. Gabungkan branch cv kedalam branch master menggunakan perintah git merge = git merge cv
11. Unggah git repository kedalam GitHub = git push -u origin master