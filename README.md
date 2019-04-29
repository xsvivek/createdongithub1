# createdongithub1

this was created on github website.


new change... Instructions
//commands for GIT.

// To login........
git config --global user.name "Your Username"
git config --global user.email abcd@xyz.com 

git config --list      // it shows the list of all the GIT configuration settings. 

git  init           // it creates a new repository, or convert an existing(unversioned) repository.
                                     
                                     OR  

git clone <url of GIT repository ends with .git>        // downloads the entire repository to the local machine (your laptop)
                                                                                           // it has the options to choose HTTPS or SSH as well

git status       // ( After cloning, You Need to be in that same folder in order to use this status command)
                         //  it provides the info of that repository such as.. branch name, modifications made, 

git commit -a -m  "Any message you wanna write"     // Use this command Once you're done with any changes 
                                                                                                 // and you want to save them all on the main GIT repository
                                                                                                 // "-a" arguement  means all, "-m" argur=ement means message.
 
 git log  -2       // it shows the logs of last 2 commits.. like who made those changes and when. 


git remote    // it shows the list of all the remotes associated with your project                                                                                
                       // a "remote" is the github here, there can be multiple remotes for one project.

git remote -v   // shows the url of origin (remote)
                           // ( -v means verbose, which provides further details of what is happening)  
--->>
NOTE: in case if there is no remote, you will have to create one.
             git remote add <name you want for remote> 
             // Ex.   git init
                           git add Readme.md 
                           git commit -m "First commit"
                           git remote add origin https://github.com/xsvivek/createdongithub1.git
                           git push -u origin master
--->>

---------------------------------------------------------------------------
---------------------------------------------------------------------------


git push <remote> <branch name> // (Ex. git push origin master) It will then ask for the username, password on github, 
                                                                // and then you can push the changes or commits which were locally made, to the Github repo.

-------------------------------------------------------------------------------------------------------------

git add  
git commit -m "adding a change from the feature branch" 
git push origin <feature>


-----------------------------------------------------------

git branch   // to list all the branches of the repository
                        // you will just see a master branch if there are no other branches existing.

git branch branch1  // creates a new branch named "branch1"

git push pehlaremote branch1   // This will finally push and make the changes (i.e. adding a new branch to the master branch)
                                                            // You can now see on the github website that there is a new branch created named "branch1".
                                                            

git clone <url> --branch <branch> --single-branch [<folder>]  // to download a specific branch ONLY. 










