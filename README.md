# cis-4301-spring-2020
This is the shared repository for the group's database project.

## Initializing the Repository Locally:

1.  Navigate to the repository on gitHub.  Then, click on the *Clone or Download* button:

![](Images/Step%201.jpg)

2.  Click on the *Copy to Clipboard* button next to the file path:

![](Images/Step%202.jpg)

3.  Finally, navigate to your command line.  Use *git clone*, then paste the previously copied filepath to the command line.  GitHub will initialize the file structure and start your repository locally!

![](Images/Step%203.png)

## Work Flow:


1.  Use: 

         git branch [branch_name]

      to create your own, unique branch from the origin master branch.  This will be used to develop
      your own code for different user stories. 

2.   After you finish your code development, use:

         git diff
   
      to manually check any differences in your code from the master origin.

3.  If you do not see any major concerns at first, use the command:

         git add .
   
      to add all your local changes to the staging repository on your computer

4.  The next step is to use:

         git commit -m '[Your message here]'

      to add your file to the main repository

5.  Next, use:

         git pull https://github.com/cis-4301-spring-2020/CIS-4301-database-app

      to check any potential conflicts with future merging by comparing currently developed code
      with the newest version of the repository.

6.  After resolving all possible merge conflicts, use

         git push https://github.com/cis-4301-spring-2020/CIS-4301-database-app [branch_name]

      to stage a merge request.  You will need to follow the steps provided in the link
      github displays as a return to this request to finalize the merge request.

7.  The code will then be reviewed for conflicts by a fellow teammate.  If there is
      still a conflict, Ken will resolve the issue among the developers whose code is in conflict.

8.  After a new merge is approved, it will be available for review for all people.  Please be sure
      to clearly state what your proposed code will do as clearly as possible in each merge request!

