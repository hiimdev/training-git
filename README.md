- Khởi tạo git
git init 

- Xem trạng thái file
git status

- 
git add file_name ( git add . => add toàn bộ)

- reset trước khi add 
git reset 

git commit

- Xem commit  
git log 
git log --oneline

- chuyển branch:
git checkout branch_name

- Tạo branch
git checkout -b {branch_name}

- Merge branch
git merge {branch_name}      (đứng tại master)

- Xoá branch
git branch -d {branch_name}

- đẩy local lên remote
git remote add origin link_repo
git push origin master

- Đẩy branch local lên remote 
git push  -u origin  branch_name

- Lấy branch remote về local 
git checkout -b  branch_name  origin/branch_name

- Update mới nhất từ remote về local
git pull

- Tương tự pull nhưng kh update ( phiên bản an toàn)
git fetch