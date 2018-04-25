
# Homework Submission Guide

Sometimes there will be too much homework to complete, and sometimes you might just get stuck and not get everything done, and that's totally okay. However, if there's a portion of the homework you're having trouble with, rather than not submitting anything, please comment out a note in your file to let us know. It's a good idea to set a limit for how long you work on the homework: generally speaking, you want to dedicate about four to five hours each night (set a cutoff of midnight - 1am CST). You want to be properly rested for the next day's learning.


### 1. Get your homework
#### The instructors may post the homework early in the day, but changes may be made during the afternoon. You will want to follow these instructions after 4:30 pm CST to ensure the most accurate assignment is in the repository.

1. To access your homework, you will fork a copy of the [Student-Homework-Repo](https://git.generalassemb.ly/WDIplus-ATX/Student-Homework-Repo), to your profile on Github. 
2. Then go to your profile and clone your copy of the Student-Homework-Repo into a local repository onto your machine.
3. Open a terminal shell and `cd` navigate to an easily accessible place on your machine where you can clone the repo.


### Here's an example of what that would look like:
 `$ git clone https://git.generalassemb.ly/<your github username>/Student-Homework-Repo.git`


### 2. Complete your homework

Work on your homework listed as a **day of the week markdown file** (ex. Monday.md) located in the **Week** folder for that particular week (ex. Week_One, Week_Two etc).

- Some homework will come with an additonal folders with **starter code** and you can start coding directly in the provided files inside the homework folder according to the instructions.

- If homework does not come with starter code, you will need to create the necessary folders and files.

- At certain intervals in your homework markdown, you will be given prompts to commit your work to git. Please follow these prompts because they are an important part of grading your work.


### 3. Commit your work to your local Git repo

* To submit your homework after you have followed all the commit prompts
  1. commit it on your local Git repo
  2. push it to your repo on Github. 
  
The overall process looks like this: in the root folder of your class repo you will run the following commands:

```
git add .
git commit -m 'my commit message'
git push origin master
```


Note that you are pushing to `origin` **not** `upstream`. Your forked repo in this case is your **origin**, and this is where you want to push your homework.

- Now your folders and files should appear in your repo on Github. 
- Feel free to contact one of you local instructors if you have an issues. 





