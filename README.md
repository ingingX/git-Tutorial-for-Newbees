# git-Tutorial-for-Newbees
Learning git commands from beginning as a newbee.

## other useful cmd:
### back to upper-level folder
	cd ..
	cd ../

### clear the cmd window
	clear

### show all file and folder names in current folder
	ls

### create new sub-folder
	mkdir ./newFolder

### create empty txt file
	touch ./newFolder/name.txt

### ssh related
	ssh usr@server.com # connect to server
	scp -r local/folder usr@server.com:/remote/folder # upload local foler to server
	scp -r usr@server.com:/remote/folder ~/local/folder # download server foler to loccal
	scp  local/file_path usr@server.com:/remote/file # upload local file to server
	scp  usr@server.com:/remote/file ~/local/file_path # download server file to local


## git clone
	cd Documents/github

	git clone https://tokenhere@github.com/user_name/repo_name.git

## check status
	git status

## push
	cd github/test

	git add -all
	git commit "update messages"
	git push

## gitignore
more ref: https://www.youtube.com/watch?v=3KrjEytC5qc

	touch .gitignore
	touch ./shouldBeIgnored/important.txt
	touch ./shouldBeIgnored/shouldBeIgnored.py

in .gitignore:

	*.py #all .py files will be ingored
	/shouldBeIgnored #this folder will be ignored
	
	!important.txt #this txt file in the ignored folder will be tracked


