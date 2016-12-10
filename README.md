# Project

set HOMEPATH=\Users\alice
set HOMEPATH=\Users\bob

git config --list
git config --global user.name "Alice"
git config --global user.email "oxyx@yandex.ru"
git config --list --show-origin
git config --global alias.st status
git config --global alias.l3 "log -n 3"
git config --global alias.lg "log --pretty=format:\"%h %s\" --graph -n 7"
