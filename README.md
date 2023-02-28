## add file

<br/>
git add .

## commit file<br/>

git commit -m "message"

## push file<br/>

git push origin master

## git history<br/>

git log

## remove committed file<br/>

git restore --staged <file>

## remove uncommited file<br/>

git restore <file>

## reset to particular git sha

git reset b15390dec4227f6b09d7721b3d390d98ffbdd3ed (from git log)

## pull from master to fork master

git pull upstream master

## squash

git rebase -i b15390dec4227f6b09d7721b3d390d98ffbdd3ed (sha of before commits)
replace pick with s leaving 1 pick
