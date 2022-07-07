#Working Directory


#Staging Area



#Git Directory(Repository)




gaura@LAPTOP-PPU5V8NV MINGW64 /d/study/git/Learning/udemy/udemyIanGitCourse (feature1)
$ touch file5.html

gaura@LAPTOP-PPU5V8NV MINGW64 /d/study/git/Learning/udemy/udemyIanGitCourse (feature1)
$ git status
On branch feature1
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        file5.html

nothing added to commit but untracked files present (use "git add" to track)

gaura@LAPTOP-PPU5V8NV MINGW64 /d/study/git/Learning/udemy/udemyIanGitCourse (feature1)
$ git commit -m"Adding html file"
On branch feature1
Untracked files:
        file5.html

nothing added to commit but untracked files present

gaura@LAPTOP-PPU5V8NV MINGW64 /d/study/git/Learning/udemy/udemyIanGitCourse (feature1)
$ git log
commit 59ee6a3b04d471b69b88124ea7ddd47d4f6152b4 (HEAD -> feature1, master)
Author: 8440Gau <8440gaurav@gmail.com>
Date:   Wed Jul 6 11:19:03 2022 +0530

    adding from staging to repo

gaura@LAPTOP-PPU5V8NV MINGW64 /d/study/git/Learning/udemy/udemyIanGitCourse (feature1)
$ git status
On branch feature1
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        file5.html

nothing added to commit but untracked files present (use "git add" to track)

gaura@LAPTOP-PPU5V8NV MINGW64 /d/study/git/Learning/udemy/udemyIanGitCourse (feature1)
$ git log
commit 59ee6a3b04d471b69b88124ea7ddd47d4f6152b4 (HEAD -> feature1, master)
Author: 8440Gau <8440gaurav@gmail.com>
Date:   Wed Jul 6 11:19:03 2022 +0530

    adding from staging to repo

gaura@LAPTOP-PPU5V8NV MINGW64 /d/study/git/Learning/udemy/udemyIanGitCourse (feature1)
$ git add .

gaura@LAPTOP-PPU5V8NV MINGW64 /d/study/git/Learning/udemy/udemyIanGitCourse (feature1)
$ git commit -m"Adding the html file"
[feature1 65428c9] Adding the html file
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 file5.html

gaura@LAPTOP-PPU5V8NV MINGW64 /d/study/git/Learning/udemy/udemyIanGitCourse (feature1)
$ git status
On branch feature1
nothing to commit, working tree clean

gaura@LAPTOP-PPU5V8NV MINGW64 /d/study/git/Learning/udemy/udemyIanGitCourse (feature1)
$ git log
commit 65428c978f69ed38bcab69d0f8925f0b28452cc5 (HEAD -> feature1)
Author: 8440Gau <8440gaurav@gmail.com>
Date:   Thu Jul 7 15:27:48 2022 +0530

    Adding the html file

commit 59ee6a3b04d471b69b88124ea7ddd47d4f6152b4 (master)
Author: 8440Gau <8440gaurav@gmail.com>
Date:   Wed Jul 6 11:19:03 2022 +0530

    adding from staging to repo

gaura@LAPTOP-PPU5V8NV MINGW64 /d/study/git/Learning/udemy/udemyIanGitCourse (feature1)
$ git checkout master
Switched to branch 'master'

gaura@LAPTOP-PPU5V8NV MINGW64 /d/study/git/Learning/udemy/udemyIanGitCourse (master)
$ git log
commit 59ee6a3b04d471b69b88124ea7ddd47d4f6152b4 (HEAD -> master)
Author: 8440Gau <8440gaurav@gmail.com>
Date:   Wed Jul 6 11:19:03 2022 +0530

    adding from staging to repo
