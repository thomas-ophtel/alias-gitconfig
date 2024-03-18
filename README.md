# gitAlias
Save time with git Alias

1/ Open you .gitconfig  
2/ and after [user] put :  

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