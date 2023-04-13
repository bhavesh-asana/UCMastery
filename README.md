# UCMastery
The UCMastery repository includes the academic materials, assignments, project work of the individual subjects.

In this repository the branches are the acedmic courses. You can access the course files on choosing the specific branch.

# Working with repository
## Accessing files in local
1. Clone the Master branch
   ```terminal
   git clone https://github.com/bhavesh-asana/UCMastery.git
   ```
2. Clone a course from the repository
    ```terminal
    git clone -b <branch-name> https://github.com/bhavesh-asana/UCMastery.git
    ```
    
# Contribution
## Adding files to exsisting branch
1. Clone the branch as stated above
2. In the cloned directory, you can find a brach created, which is named as your course.
   ```terminal
   git branch
   ```
3. Add the files and make a commit
   ```terminal
   git add <file-name/path>
   git commit -m "<commit-message>"
4. Send your work
   ```terminal
   git push --set-upstream origin <branch-name>
   ```

## Adding files on creating a new brach
1. Create a folder in your local machine.
2. Initialize the GitHub repository
   ```terminal
   git init
   ```
3. Set the repository to UCMastery
   ```terminal
   git remote add origin https://github.com/bhavesh-asana/UCMastery.git
   ```
4. Create a branch
   ```terminal
   git branch -M <course-name>
   ```
   In this repository, the course name will be the branch name.
5. Add the files and make commit
    ```terminal
    git add <file-name/path>
    git commit -m "<commit-message>"
    ```
6. Send the work to remote repository
   ```terminal
   git push --set-upstream origin <branch-name>
   ```
