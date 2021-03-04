# cicd
Tim hieu ve CI/CI

# Cac cau lenh git hay dung

Git global setup
git config --global user.name "Quang Tran Van"
git config --global user.email "quangtv@nuce.edu.vn"

Create a new repository
git clone git@gitlab.com:quangtv1/cicd.git
cd cicd
touch README.md
git add README.md
git commit -m "add README"
git push -u origin master

Push an existing folder
cd existing_folder
git init
git remote add origin git@gitlab.com:quangtv1/cicd.git
git add .
git commit -m "Initial commit"
git push -u origin master

Push an existing Git repository
cd existing_repo
git remote rename origin old-origin
git remote add origin git@gitlab.com:quangtv1/cicd.git
git push -u origin --all
git push -u origin --tags