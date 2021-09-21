1. What does git clean do? = Git clean adalah perintah untuk undo, yang melengkapi perintah lain, seperti git reset dan git checkout. Perintah git clean berjalan pada file yang tidak terlacak.
2. What do the -d and -f flags for git clean do? = 
    -d : memberitahu git clean bahwa anda juga ingin menghapus direktori yang tidak terlacak, secara default ia akan mengabaikan direktory.
    -f : beroperasi pada semua direktori saat ini yaitu file yang tidak terlacak. Selain itu, nilai <path> dapat diteruskan dengan opsi -f yang akan menghapus file tertentu.
3. What git command creates a branch? = git branch nama_branch
4. What is the difference between a fast forward and recursive merge? = The merge commit memiliki 2 parents. Tidak ada yang benar dan salah dari salah satu strategi, tetapi dengan Fast forward merge, kita memiliki garis lurus sejarah, sedangkan recursive merge, itu adalah beberapa baris.
5. What git command changes to another branch? = git checkout nama_branch
6. How do you remove modified or deleted files from the working directory? = rm nama_file
7. What git command deletes a branch? = git checkout -b nama_branch
8. What does the git diff command do? = git diff berfungsi untuk membandingkan perubahan yang baru saja dilakukan dengan revisi atau commit terakhir.
9. How do you remove files from the staging area? = git rm --cached nama_file
10. How do merge conflicts happen? = Mengedit file atau menghapus conflicts, setelah itu git add nama_file 

