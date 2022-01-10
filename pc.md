# Setting Up Your Computer

Welcome to day 1 at BloomTech, today we are going to spend time setting up your computer and learning the tools that you will be using to complete this program. Just like day 1 at a job, you will need to get your environment set up to build and run your code. Complete the set up tasks below and then get started on the research questions. Once you have finished check out the submission instructions in the `README.md` file to turn in your assignment for the day. 

## Set Up Tasks 
1. [X] [Download gitbash]() - Windows computers speak in a language called powershell however we will be speaking to our computers in a language called unixshell, in order to all be speaking the same language if you are using a PC you will need to download gitbash and use this program instead of the native command line. Whenever you see an instruction to use the terminal that will be your queue to open up gitbash. On a PC gitbash will be your terminal. 
2. [X] sign up for a [GitHub account](https://github.com/join) - please use a professional username. We recommending using your `firstname` `lastname`
3. [X] [Set up your SSH key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) - GitHub uses SSH to keep their files secure. You will need to set up one SSH key for every computer that you want to access your GitHub account on. Please ensure you go through all of the steps to generate a new key, add a new key and test your connection. 
4. [X] [Download Zoom](https://zoom.us/download) - make sure your zoom display name is your `first name` `last name`
5. [X] [Download Slack](https://slack.com/intl/en-ca/help/articles/209038037-Download-Slack-for-Windows) - make sure your slack display name is your `first name` `last name` 
6. [X] [Download VS code](https://code.visualstudio.com/download) - this will be the tool you use to write all of your code. We recommend installing the following extensions: 
- [ES Lint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
7. [X] [Download Node.JS](https://nodejs.org/en/) - Please download the latest stable version. We will be using Node.JS to run the tests in all of our javaScript assignments. Test driven development is a common practice in the world of web dev. You can read more about it [here](https://www.freecodecamp.org/news/test-driven-development-what-it-is-and-what-it-is-not-41fa6bca02a2/) 
8. [X] Sign up for a free [codepen account](https://codepen.io/accounts/signup/user/free)

## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You can type your answer below the questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en) doc short for documentation are the instructions on how to use a languge, or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your google skills. 

1. What is git? What is the difference between git and GitHub?
Git is version control tool, mainly used to work on changes to a main source code. github is a hosting service to host source code which consist of git repositories.
2. Why do we create a branch? 
we create branches mainly so that it is easier for multiple developers to work on the same source code without modifying said source code. It also helps since you would have to test the code inside a branch before merging it with the main code so there is less errors to deal with. 
3. What is the purpose of a pull request? 
The purpose is to let other poeple know of tha changes that you are making to a project. said changes can then be reviewed annd discussed before merging the changes to the source code. 
4. What is the command you can use to switch between branches? For example you are working on a feature branch and you want to switch back to main. 
the command to switch bewtween branches is git checkout 
5. Explain the difference between `git fetch`, `git merge` and `git pull` what does each command do? 
git fetch is used to retrieve branches form other repertories into the branch you are working on, git merge is used to merge the current branch into the main code. git pull is basically a combination of the git fetch and git merge put into one single command. 
6. What is a merge conflict? How do you resolve a merge conflict? 
a merge conflict happens when two different developers try to modify the same line or code or when one developer tried to modify a file while another developer has delted the file. The best way to solve a merge conflict is to edit the confilcted file to remove any changes to the same line or file.