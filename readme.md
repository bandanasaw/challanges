 initialize : `` git  init``

 add changes to local repo `` git add .``

 process  ``add => commit => push`` 

 commiting the changes to local repo `` git commit -m "YOUR COMMENT"``


 # git process to add new repo to git origin

 echo "# challanges" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/bandanasaw/challanges.git
git push -u origin main