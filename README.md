# Reuse-Near-You
Reskill Americans Phase 3 Group Project

****************

A guide on how to use the repo.
Team Contact: @cbojo5

    1. Fork the Parent Repo

    2. Clone your preferred branch from your Fork
   ..... For FrontEnd Branch
          git clone -b 'FrontEnd' URLofFork
   ..... For BackEnd Branch
          git clone -b 'BackEnd' URLofFork

    3. Now that the branch is cloned to your machine, change to the directory
         cd clonedFolder
 
    4. Create your workbranch and checkout to that branch
        git branch nameOfTask
        git checkout nameOfTask  
     
    To ensure nameOfTask is updated with main Repo, do
        git remote add upstream URLofMainRepo

    To update nameOfTask branch with either the FrontEnd or BackEnd of the main Repo (depending on which track you are in) do,
         git fetch upstream/FrontEnd
            or
         git fetch upstream/BackEnd

    5. Start coding. Add your code, commit and push when done
        git add -A
        git commit -m "Adding so so so"
        git push origin nameOfTask

    6. Create a pull request on your fork on GitHub - your base is your branch (nameOfTask) and the head is either FrontEnd or BackEnd Branch of the main repo.
        Your PR should have a screenshot of the output to enable faster code review. 
   
    7. Your Teamlead or designated person can merge after checking.

    8. Your main branch can be the combination of finished work on backend and frontend (i.e Backend person to consume the frontend and push to main) that will          be deployed to Heroku to go live.




