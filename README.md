# Lab-2
                                                                      TASK-1

//////////////////////////////////////////STEPS TO ADD SEPERATE FILES TO DIFFERENT BRANCHES AND THEN MERGING IT WITH MAIN BRANCH\\\\\\\\\\\\\\\\\\\\\\\\\\\\

1-   CREATE NEW BRANCH BY USING THIS COMMAND            git branch "branch-name"
2-   CHECKOUT TO NEW BRANCH                             git checkout "branch-name"
3-   CREATE FILE MANUALLY IN THIS BRANCH(LOCALLY) 
4-   ADD FILE TO BRANCH                                 git add "filename"
5-   COMMIT CHANGES                                     git commit-m "commit"
6-   PUSH INTO REPO                                     git push origin "name of branch"
7-   CHECKOUT BACK TO MAIN                              git checkout "main"
8-   MERGE NEW BRANCH WITH MAIN                         git merge "filename"
9-   REPEAT SAME STEPS FROM 1-8 AGAIN TO
     CREATE THE SECOND BRANCH
 

/////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

                                                                           TASK-2
                                                                           
CREATE AN ANNOTAED TAG                           git tag -a "tag name" -m "Commit"
PUSH IT INTO REPO                                git push origin "tagname"
HOW TO LIST TAGS                                 git tag
HOW TO DELETE TAG LOCALLY                        git tag -d "tag name"
HOW TO DELETE TAG REMOTELY                       git push origin --delete "Tag name"
