# contents
git add
git commit
git status
git log --no-pager log -n 10 --oneline --parents --graph
git cat-file -p <hash>
    commit > tree > blob > file-content
git config --add --local webflyx.ceo primeagen
git config --add --local webflyx.cto leanegen
git config --list --local
cat .git/config
locationi
system = /etc/gitconfig
global location = ~/.gitconfig
local location = /.git/configi
worktree = .git/config.worktree
webflyx = section, ceo = key, primeagen = value
git config --get <key>
git config --unset webflyx.ceo
git config --unset-all example.key
git config --remove-section section
git brach
git branch -m master main (rename a branch)
git branch my-new-branch or, git switch -c my-new-branch or, git chechout -b my-new-brach
git find | grep refs
git log --decorate=full or, git log --oneline (show branch name)
git log --decorate=no or, git log --oneline | tee out (don't show branch name)
git log --graph


