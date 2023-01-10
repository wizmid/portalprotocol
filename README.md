readme
git config user.name 'wizmid' && git config user.email wizmid92@gmail.com && git config credential.${remote}.username wizmid && git config credential.helper store

git add . && git commit -m "first commit" && git branch -M main && git remote add wizmid https://github.com/wizmid/portalprotocol.git && git push -u wizmid main

