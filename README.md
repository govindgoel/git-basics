# git-basics

### Prerequisites:
  - Git should be installed in the system
  - If not take a look here: https://git-scm.com/downloads
  - Terminal :P

### To get started

- Fork the repo: https://github.com/govindgoel/git-basics/fork  
- Clone the repo: `git clone https://github.com/{your-github-username}/git-basics.git`
- Navigate to the cloned repo: `cd git-basics`
- Create a new branch: `git checkout -b {yourName}`
- Now you can add a new file with name `yourName-exploring-git.md` and write something in it.
- It's time to push your changes:
  - First see what you have added/changed by doing: `git status`
  - To add changes to staging do: `git add .` 
  - To commit changes do: `git commit -m "yourName-learning-git"` [in quotes you provide the commit message basically]
  - To push changes do: `git push origin {branchName}` [it will be your name that you used to create a branch]
  - If it asks to add upstream then do that and push again otherwise it's done.
  
- To create a pull request:
  - Go to the repo in your Github account and click on contribute<span>
  ![Screenshot from 2022-12-30 18-31-55](https://user-images.githubusercontent.com/52847415/210073025-55ac147f-b276-4114-a0c0-c12a8e3c772c.png)</span>
  - You should see something like below
![Screenshot from 2022-12-30 18-38-28](https://user-images.githubusercontent.com/52847415/210073459-e8ceff30-eda2-4e90-b9c5-0db54837d958.png)

- Click on create pull request
- It's done :tada: 


### Key Takeaways:
- What is Git 
- Why we need Git
- Git basic commands
- What is a commit
- How to add & push changes to a GitHub Repo
- How to raise a pull request

### If you are interested to learn & explore more do checkout this: https://learngitbranching.js.org/
