# Git pull
1. Tạo 2 thư mục `git-rebase` và `git-rebase-v2`, cả 2 thư mục cùng ở nhánh `git_pull`
2. Vào thư mục `git-rebase` push nhánh `git_pull` với commit `pull1`
3. Vào thư mục `git-rebase-v2` không pull nhánh `git_pull` về mà push tiếp commit `git pull 2` lên nhánh `git_pull`
4. Git báo cần pull nhánh `git_pull` về
5. Thực hiện `git pull` xong rồi push lên nhánh `git_pull` nhưng không push được
6. Không dùng `git pull git_pull` nữa mà dùng `git pull git_pull --rebase` thì kéo được code về, fix conflict xong commit rồi `git push` nhưng vẫn không đẩy được code lên, dùng `git push --force-with-lease` thì mới đẩy được code lên nhưng commit `pull1` thì đã không còn mà thay bằng commit `git pull 2`

# Document Git rebase & Git merge
https://www.youtube.com/watch?v=yn7FJvQdBTs
