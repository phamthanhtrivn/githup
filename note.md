# Terms

Repository (Repo): thư mục dự án (core)
Branch: nhánh trong dự án
Conflict: xung đột
Local
Remote

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
- git push <duong_dan_git_sau_khi_tao_repo> <ten_nhanh>
- git push
- git clone <duong_dan_git_sau_khi_tao_repo>: lấy code về từ githup
- git remote add origin <duong_dan_git> : chuyển đường dẫn git thành origin
- git push -u origin <ten_nhanh> : đẩy nhánh lên githup
- git fetch origin : cập nhật local khi có thay đổi từ remote
- git checkout -b <ten_nhanh> origin/<ten_nhanh> : cập nhật tên nhánh mới dưới local khi có thay đổi từ remote
- git pull origin <ten_nhanh>: lấy code từ nhánh về dự án
 