# Basic-Html-and-Css-project
This is first week capstone project.


 How to setup your Git and Github
This is instruction to Setup your Git and GitHub Account
- 1 Go an create a Github account @ www.github.com
- 2 Then search for Css-babe in the search Input left hand side.
- 3 Click on the Group-25 repository and find the code button at the right hand side
- 4 Select the code button and copy the ssh link provided

** Next step
- Go to terminal, you can just search it on the desktop search
- if you dont already have Git installed on your laptop. Go to https://git-scm.com/download/win
        **download and install.
- To verify that youve downloaded git, type git --version on your terminal,it should bring out the version of the git you have downloaded
- Provide where you want to clone the repo by typing "cd desktop"
- Then,in the terminal, type git clone and paste the ssh link you copied earlier. e,g "git clone https://github.com/css-babe"
- You should see the group 25 folder appearing on your desktop after cloning.
- Now you can open the folder in your Vs code editor. 

**Next step
- In the vs code locate and open your terminal in the heading above where you have file.
- Your terminal should be showing path name that ends with group 25, if so type "git config user.name" then add the name of your git profile and enter.
- type "git config user.password then provide your access token
    **Go to Generate access token
    - Go to your github page and click the profile icon on the right side
    - Click on Settings, then click on Developer settings
    - Find and click personal access token
    - Click on Generate token, enter token name(any name), best to set it never expired, Grant all access and generate token then paste in the above

**Next step is create a new Branch(Do this before write any code ooo)
- To create a new branch, type "Git branch branchName(can be any name)"
- Then type "git checkout theNewbranchYouCreated"

**Do this after you write any code you are satisfied with and doesnt have any error
- Type git add .
- then type "git commit -m "give your changes a name can be anything"
- then type git push
(if you are asked userName, provide your gitHub username and provide access token for password)

**Next Step - Go to your Github online
- you will most likely see a notification asking you to create pull request
- if don't see notification, go to pull request tab and create new pull request.
- In the pull request compare your branch with develop branch and if no conflict, create the pull request.
- Get in touch with me and ask to merge your pull request



