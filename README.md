# UseGIT
Using Git for your local code from Quality Softwares Kushalnagar (https://www.qlitysoftware.com)


Scenario:
You have made certain amount of coding in your repository, or just a file to initialize git. Now you want to keep a copy in cloud(git hub), to avoid loosing

Requirements:
1) Open an account in git hub
2) Install github locally in your computer
3) Launch the github application and login with same credential as in step 1 (you can also select option to login via browser)
4) If git is not used in your project so far:
  i) Install Git-bash
  ii) Open Git Bash and navigate to root directory of your project
  iii) Type the command git init. This will initialize your project
5) In git hub application, check the repository name
6) Create a same named repository in git hub as public without any file not even README
7) Assuming in local repo, your branch name is master,( you will get your branch URL in quick setp)
  i) git remote add origin <URL of your project: eg: https://github.com/Madhu-Guddana/RepoName.git
  ii) git push -u origin master
