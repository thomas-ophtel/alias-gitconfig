[alias]
	co = checkout
	br = branch
	st = status 
	sta = stash 
	stap = stash pop 
	p = pull
	pu= push
	a = add
	m = merge
	ci = commit
	l = log
	lola = log --graph --decorate --pretty=oneline --abbrev-commit --all
	fast = "!f() { git add -A && git commit -m \"$@\" && git push; }; f"