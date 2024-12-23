# Terms

Repository (Repo): thư mục dự án (core)
Branch: nhánh trong dự án
Conflict: xung đột

# Commands

- git init
- git status
- git add <ten_file> : chuyển file sang trạng thái staging
- git add . : chuyển tất cả file sang trạng thái staging
- git rm --cached <ten_file> hoặc git reset -- <ten_file>: chuyển file trở về trạng thái working 
- git reset: chuyển tất cả file trở về trạng thái working 
- git commit -m "<tin_nhan>" : đẩy các file trong trạng thái staging sang repository
- git log: coi những thời điểm đã lưu
- git log --oneline
- git checkout <commit_id> : trở lại các thời điểm được commit
- git checkout master : trở lại hiện tại
- git branch : xem các nhánh trong dự án
- git checkout -b <ten_branch> : tạo nhánh mới
- git checkout <ten_branch> : di chuyển qua các branch
- git merge <ten_branch> : hợp nhánh vào master
- git branch -d <ten_branch> : xóa nhánh