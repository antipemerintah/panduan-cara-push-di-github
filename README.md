# langkah langkah untuk project/folder yang belum pernah di push

1. git init
2. git add .
3. git commit -m "first commit"
4. git remote add origin https://github.com/(nama_akun_lu)/(repo_lu)
5. git branch -m main
6. git push -u origin main

# Untuk yang sudah pernah di push
1. git add .
2. git commit -m "commit yang ke dua"
3. git push / git push origin main

# error?
kalau masih error coba cek
1. git status
2. git remote -v
3. git log --oneline kalau di push masih ga bisa palai ini
4. git push --set-upstream origin main
