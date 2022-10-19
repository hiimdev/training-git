- Khởi tạo git: 
**git init**

- Clone 1 remote repo:
**git clone repo_url**

- Sử dụng **git stash** khi bạn muốn ghi lại trạng thái hiện tại của thư mục làm việc và chỉ mục, nhưng muốn quay lại thư mục làm việc cũ.

- Xem trạng thái file: 
**git status**

- Lưu thông tin chuẩn bị commit: 
**git add file_name** ( **git add .** => add toàn bộ)

- reset trước khi add : 
**git reset**

- Lưu thông tin vào local repo:
**git commit**

- Xem commit: 
**git log** or
**git log --oneline**

- chuyển branch:
**git checkout branch_name**

- Tạo branch:
**git checkout -b branch_name**

- Merge branch:

**git merge branch_name** or **git rebase branch_name** (xây dựng lại các commit base kế thừa từ nhánh khác và viết lại lịch sử commit sau các commit cơ sở mới)


- Xoá branch:
**git branch -d branch_name**

- đẩy local lên remote:
**git remote add origin link_repo**
**git push origin master**

- Đẩy branch local lên remote:
**git push -u origin  branch_name**

- Lấy branch remote về local:
**git checkout -b  branch_name  origin/branch_name**

- Update mới nhất từ remote về local:
**git pull**

- Tương tự pull nhưng kh update ( phiên bản an toàn của git pull): 
**git fetch**

- File **.gitignore**: File này chứa các thông tin mà ta không muốn đẩy lên remote repo 
