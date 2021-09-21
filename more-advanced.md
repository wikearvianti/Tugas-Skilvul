1. What is the difference between git reset and git revert. When would you use one over the other? =
    git reset : mengembalikan file ke kondisi sebelumnya, kemudian menghapus catatan sejarah commit berikutnya.
    git revert : mengembalikan file dengan tidak menghapus sejarah commit.
    Digunakan ketika ingin mengembalikan file
2. What is the difference between git merge and git rebase. When would you use one over the other? =
    git merge : meleburkan 2 state dari 2 branch
    git rebase : memindahkan cabang fitur menjadi master
    Digunakan ketika ingin mengintegrasikan perubahan dari 1 cabang ke cabang lainnya.
3. What is the difference between git stash pop and git stash apply. When would you use one over the other? =
    git stash pop : Membuang simpanan (paling atas, secara default) setelah menerapkannya.
    git stash apply : Menyimpannya didaftar simpanan
    Digunakan ketika ingin melakukan commit tanpa harus menghapus progres
4. What kinds of things can you do in interactive mode when rebasing? = Ketika perintah memasuki mode interaktif, itu menunjukkan file dan direktori yang akan dibersihkan, dan masuk ke loop perintah interaktifnya. Perulangan perintah menunjukkan daftar subperintah yang tersedia dan memberikan prompt "what now>". Secara umum, ketika prompt diakhiri dengan satu >, anda hanya dapat memilih salah satu pilihan yang diberikan atau mengetik return.