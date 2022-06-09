# git-config

Algumas configs legais de git

[core]
	editor = code --wait
[alias]
	s = !git status -s
	c = !git add . && git commit -m
	amend = !git add . && git commit --amend --no-edit
	l = !git log --pretty=format:'%C(blue)%h%C(red)%d%C(white) %s %C(cyan)[%cn] %C(green)%cr'
