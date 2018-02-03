Microsoft Windows [Version 10.0.16299.192]
(c) 2017 Microsoft Corporation. All rights reserved.


1 - CREATE A REPO ON GITHUB AND A PROJECT IN R. NAME THE REPO AND THE PROJECT THE SAME

2. FROM CMD - CHOOSE THE FOLDER WHERE FILES ARE AT - THE FOLDER NAME NEEDS TO MATCH THE REPOSITORY ON GITHUB

C:\Users\jfzjonathan> cd "desktop/doing data science/unit 4/anotherfolder"


3. INITIALIZE GIT

C:\Users\jfzjonathan\Desktop\Doing Data Science\Unit 4\anotherfolder>git init
Reinitialized existing Git repository in C:/Users/jfzjonathan/Desktop/Doing Data Science/Unit 4/anotherfolder/.git/



4. ADD THE REMOTE GITHUB 

C:\Users\jfzjonathan\Desktop\Doing Data Science\Unit 4\anotherfolder>git remote add origin https://github.com/jfzjonathan/anotherfolder.git


5. COMMIT THE FILES

C:\Users\jfzjonathan\Desktop\Doing Data Science\Unit 4\anotherfolder>git commit -a -m "Initial commit"
[master (root-commit) eb6ab3f] Initial commit
 3 files changed, 1444 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 EducationData (4) (1).csv
 create mode 100644 anotherfolder.Rproj



6. COPY THE FILES FROM THE FOLDER

C:\Users\jfzjonathan\Desktop\Doing Data Science\Unit 4\anotherfolder>git add .

7. PUSH THE FILES TO REMOTE GITHUB

C:\Users\jfzjonathan\Desktop\Doing Data Science\Unit 4\anotherfolder>git push origin master
Counting objects: 5, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 3.11 KiB | 1.55 MiB/s, done.
Total 5 (delta 0), reused 0 (delta 0)
To https://github.com/jfzjonathan/anotherfolder.git
 * [new branch]      master -> master
 
 8. FILES SHOULD BE NOW ON GITHUB

C:\Users\jfzjonathan\Desktop\Doing Data Science\Unit 4\anotherfolder>
