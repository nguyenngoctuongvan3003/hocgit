#Terms
Repository(Repo)
branch

#Command
git init
git status : trang thai du an
git add : chuan bi luu lai trang thai hien tai cua du an
git reset: khong chuan bi luu nua
git log:
git log --oneline
git checkout --code cua commit
git checkout -b
git merge {branchname}
git push https://github.com/nguyenngoctuongvan3003/hocgit.git master
git remote add origin https://github.com/nguyenngoctuongvan3003/hocgit.git (đặt đường dẫn tên là origin)

lấy 1 remote repo có sẵn trên git về máy của chúng ta

tạo branch trên github: git push -u origin dev
lấy branch đang có trên github:
git fetch origin
git checkout -b staging origin/staging 


merge với master:
trên github
git pull