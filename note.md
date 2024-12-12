# Terms
Repository (Repo)
Branch
Conflict

# Commands
<!-- Cài Đặt git vào dự án -->
- git init 

<!-- Xem tình trạng dự án  (tất cả các file hay folder) -->
- git status


<!-- Chuẩn bị lưu tại thời điểm hiện tại của dự án -->
- git add <tên-file>
   Ex: git add index.html
<!-- Tất cả các file -->
- git add . 

<!-- Hủy các chuẩn bị của git add -->
- git reset

<!-- Chính thức lưu -->

- git commit

   Ex: git commit -m 'inital commit' 
   <!-- Commit đầu tiên -->

<!-- Xem các thời điểm commit -->

- git log

- git log --oneline <!--gọn hơn-->

<!-- Back to any commit -->
<!-- Dùng quay lại cá thời điểm nào đó -->
<!-- B1: copy id commit from "git log" -->
- git checkout <id-commit> 
- git checkout <branch-name>

- git branch

<!-- Create New Branch -->
- git checkout -b <branch-name>

<!-- Merge -->

- git merge <tên-branch>

<!-- Xóa branch -->

git branch -d <tên-branch>
