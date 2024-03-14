steps:
1) git init
2) pip install -r requirements.txt
3) dvc init
4) data\data.txt (enter data into data.txt)
5) dvc add data/data.txt
6) git add data/.gitignore data/data.txt.dvc
7) git add .
8) git commit -m "message"
9) git remote add origin github link
10) git push origin main
11) modifiy data.txt file
12) perform step 5 and step 6
13) git commit -m "message2"
14) git push origin main
15) git log
16) copy  id of first commit
17) git checkout id 
18) dvc checkout (this command show previous data )
19) git checkout main
