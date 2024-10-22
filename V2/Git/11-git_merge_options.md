# merge options 
Typically there are 3kinds of Merge Options :-
[1] Normal Merge [create a merge commit]
[2] Squash and merge 
[3] rebase and merge 
==> Lets start to discuss about Normal Merge -
1. Create a new repository "mergerepo" in git.
   create new file "imp.txt" 
   input "line1" and commit as "c1" 
   input "line2" and commit as "c2" 
   input "line3" and commit as "c3"
2. now cut new branch from main branch, and name it as feature
   input "feature1" and commit as "f1" 
   input "feature2" and commit as "f2" 
3. Go back to MAIN branch and make new insert into imp.txt file
   input "line4" and commit as "c4"
4 Once this is done you will observe " compare and pull " request
![image](https://github.com/user-attachments/assets/63c2ed70-7ff6-4c41-b4df-37913a2058b0)
click on it -- > next page 
add title - give some name
add description  - give some descritpion
click on "Create Pull Request"
![image](https://github.com/user-attachments/assets/b949c830-b692-459f-931c-a85f80d8b16b)
select the option show in the screenshot
click in " confirm merge "
5 Now you will notice the commits in this order
![image](https://github.com/user-attachments/assets/a1fb844b-4718-4870-ae82-fb4d0efc15a3)
and new commit ( since we merged two branches ) will be formed and when you click on that new commit , you will the below information
![image](https://github.com/user-attachments/assets/c7b0deb5-c6fa-4224-af32-733fcd0b758d)



