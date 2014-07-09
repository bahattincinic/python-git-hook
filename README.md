PEP8 Git Commit Hook
====================
Pre-commit hook for Git checking Python and Javascript code quality

Usage
------
The commit hook will automatically be called when you are running `git commit`.


Screenshots
------

![alt text](https://cloud.githubusercontent.com/assets/1684999/3529832/20d0e75a-079e-11e4-96a6-b318ecc2214f.png)

![alt text](https://cloud.githubusercontent.com/assets/1684999/3529887/a8619318-079e-11e4-9a09-12fdda1118f0.png)


Checklist
------
1. pep8
2. pyflakes
3. ipdb
4. print
5. console.log
6. debugger
7. JShint


Requirements
-------------
1. pep8 (`pip install pep8`)
2. pyflakes (`pip install pyflakes`)
3. jshint (`npm install -g jshint`)


Installation:
-------------
1. Save pre-commit as your_project/.git/hooks/pre-commit
2. Mark pre-commit executable: ```$ chmod +x your_project/.git/hooks/pre-commit```


Override
------
The hook can be overridden: ```$ git commit --no-verify```


This code was forked from [https://gist.github.com/spulec/1364640](https://gist.github.com/spulec/1364640).
