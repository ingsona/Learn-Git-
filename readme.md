ini contoh git add

head adalah identitas dari "commit"
untuk melihat head gunakan command "git log"

untuk kembali ke commit sebelumnya gunakan command "git checkout <head>"

untuk menghapus log dari head commit , gunakan "git reset"
terdiri dari 3 jenis soft, mixed, hard
command 
    git reset --soft <head>
    git reset --mixed <head>
    git reset --hard <head>

git revert mirip git reset tapi tidak menghapus log dari head
command 
    git revert <head>
lalu akan memunculkan COMMIT_EDITMSG

untuk mengupload perubahan code di github
gunakan git push
command
    git push -u origin master

untuk mengambil code di github
gunakan git pull
command 
    git pull origin master

command
    git remote add origin <link>
    mirip git clone tapi ini dipakai untuk download dari repository orang lain
command
    git pull origin master

PULL REQUEST
adalah permintaan untuk menggabungkan suatu code

untuk membuat branch baru
command
    git checkout -b <nama branch>

untuk menghapus branch
command 
    git branch -b <nama branch>