MyLearningGit


This is my notepad for learning git.

The website I learned git is:
https://www.liaoxuefeng.com/wiki/896043488029600

&

https://git-scm/

This's Xuefeng Liao's blog.


--------------------------------------
(1)
mkdir MyLearningGit
cd MyLearningGit
pwd

//make a directory for learning git.

(2)
git init

// creat an empty repository or reinitialize an exisiting one.
// this command create an empty Git repository-basically a .git directory with subdirectories for objects, refs/heads, refs/tags, and template file. An initial HEAD file that references the HEAD of the master branch is also created.
// but what is master branch???
// if the $GIT_DIR enviroment variable is set then it specifies a path to use instead of ./.git for base of the repository.
// if the object storage directory is specified via the $GIT_OBJECT_DIRECTORY enviroment variable, then the sha1 directories are created underneath-otherwise then default $GIT_DIR/objects directory is used.
// runing git init in an exisiting repository is safe. It will not overwrite things that are already there. The primary reason for reruning git init is to pick up newly add templates( or to move the repository to another place if--separate-git-dir is given).


(3)
vim README.md
// wrote some learning point to the file.

(4)
git add README.md
// add file contents to the index
// but
//
//
