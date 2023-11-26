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

touch ./shouldBeIgnored/py

in .gitignore:

	*.py: ingored
	./shouldBeIgnored: ignored
	!important.txt: tracked


