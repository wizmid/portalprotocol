readme
git config user.name 'alexxscofield' && git config user.email alexxscofield07@gmail.com && git config credential.${remote}.username alexxscofield && git config credential.helper store

git add . && git commit -m "first commit" && git branch -M main && git remote add scofield https://github.com/alexxscofield/portalrectify.git && git push -u scofield main
