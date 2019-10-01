# Quiz
```c
C:\Users\IME13>git config --global user.name 17011775

C:\Users\IME13>git config --global user.email antonio629@naver.com

C:\Users\IME13>git clone https://github.com/17011775/Quiz.git
Cloning into 'Quiz'...
warning: You appear to have cloned an empty repository.

C:\Users\IME13>cd C:\PatternRecognition

C:\PatternRecognition>git config --global user.name 17011775

C:\PatternRecognition>git config --global user.email antonio629@naver.com

C:\PatternRecognition>git clone https://github.com/17011775/Quiz.git
fatal: destination path 'Quiz' already exists and is not an empty directory.

C:\PatternRecognition>cd Quiz

C:\PatternRecognition\Quiz>git add .

C:\PatternRecognition\Quiz>git commit -m "Add 20190924_Quiz1[Add]"
On branch master
Your branch is based on 'origin/master', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

nothing to commit, working tree clean

C:\PatternRecognition\Quiz>git commit -m "Add 20190930_Quiz2_solution
On branch master
Your branch is based on 'origin/master', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

nothing to commit, working tree clean

C:\PatternRecognition\Quiz>git push
Logon failed, use ctrl+c to cancel basic credential prompt.
Username for 'https://github.com': 17011775
Password for 'https://17011775@github.com':
remote: Invalid username or password.
fatal: Authentication failed for 'https://github.com/17011775/Quiz.git/'

C:\PatternRecognition\Quiz>GIT PUSH
fatal: cannot handle PUSH as a builtin

C:\PatternRecognition\Quiz>git push
Logon failed, use ctrl+c to cancel basic credential prompt.
Username for 'https://github.com': 17011775
Password for 'https://17011775@github.com':
remote: Invalid username or password.
fatal: Authentication failed for 'https://github.com/17011775/Quiz.git/'

C:\PatternRecognition\Quiz>git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (5/5), 398 bytes | 199.00 KiB/s, done.
Total 5 (delta 0), reused 0 (delta 0)
To https://github.com/17011775/Quiz.git
 * [new branch]      master -> master

C:\PatternRecognition\Quiz>git branch solution

C:\PatternRecognition\Quiz>git branch
* master
  solution

C:\PatternRecognition\Quiz>git add .
warning: LF will be replaced by CRLF in 20190924_Quiz1_solution.py.
The file will have its original line endings in your working directory

C:\PatternRecognition\Quiz>git commit -m "Add 20190924_Quiz1_solution[Add]"
[master f7db90a] Add 20190924_Quiz1_solution[Add]
 1 file changed, 185 insertions(+)
 create mode 100644 20190924_Quiz1_solution.py

C:\PatternRecognition\Quiz>git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 2.42 KiB | 2.42 MiB/s, done.
Total 3 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/17011775/Quiz.git
   d98f717..f7db90a  master -> master

C:\PatternRecognition\Quiz>git branch merge

C:\PatternRecognition\Quiz>git branch
* master
  merge
  solution

C:\PatternRecognition\Quiz>
