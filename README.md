10th
1.folder in desktop(eg.project 1)
2.login to GitHub
3.create new repo with readme on (Myproject1)
4.click on folder to open terminal
5.git init
6.git branch -M main
7.git add .
8git commit
9. git remote add orogin https://github.com...git
10.push code
10.echo "# mt project" > README.md
11.git add README.md
12.git commit -m "ADD README"
---result---
13.git push -u origin main
14.git remote -v
---------
15.open Jenkins
16.click new item
17.enter item name(My-project2)
18.select freestyle prjct
19.ok
note:in source code management select git also paste url and change masters to main
--------
20 terminal
21.echo "pipeline { agent any; stages { stage(clone.....}}}}
22.git add Jenkinsfile
23.git commit -m "Add Jenkinsfile"
--relut 1 file chang----
git push origin main

open folder see .git Jenkins readme.md
24.open vsc
25.open ur folder
26.create new file(main.py)
27.main.py
   def test_example():
      assert 1 + 1 == 2
28.command : mvn run
             python -m pytest main.py
----result ---1 paased in 000sec------
