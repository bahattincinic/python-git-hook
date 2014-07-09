PEP8 Git Commit Hook
====================
Pre-commit hook for Git checking Python and Javascript code quality

Usage
------
The commit hook will automatically be called when you are running `git commit`.


Screenshots
------

![alt text](https://cloud.githubusercontent.com/assets/1684999/3529919/f39c73d4-079e-11e4-85d8-f1a379cc2cc8.png)
![alt text](https://cloud.githubusercontent.com/assets/1684999/3529923/00b296d4-079f-11e4-9d43-d463511792ca.png)


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
