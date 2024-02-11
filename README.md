# Large Picture
In order to be an effective contributing member to the robotics team there are many 
things that you must understand! First of all, you must understand the importance of growing in your own time. There is 
only so much time that Naj and I have. You must take the initiative to learn and grow on your own. This is not to say 
that we will not help you, but we are not going to hold your hand through the entire process. We are here to help you 
when you get stuck, but we are not here to do the work for you. There will be many resources that I will give you and 
there are many resources that are online. Use both. Not of my lists are comprehensive, but they are a good starting point. 
In this repo there are many assignments and reading materials that you can use to help you grow. There will also be a 
private repo of some properitary code I wrote that I cannot expose publicly. So neither should you expose it publicly. 

#  How to use
This repo is a collection of assignments and reading materials that you can use to help you grow. As such, you should 
use this repo to your advantage. And this should be no surprise, but assignments are something that you must do (GASP). 
However, there is much flexibility with them. I have a set up order, but the goal is to give you initiative to learn. 
Therefore, it is very much encouraged that you come up with things that you want to do independent of the assignments. 
However, if the assignments look like fun, (which I hope they do) then you can do those also. How let's get into the 
fine details. The readings will just have links: you should probably click them.

## Submitting Assignments
This is a very simple and straightforward process. Make sure you follow the instructions and you will be good. Nothing 
bad will happen if you mess up (which you probably will - I mess things up all the time). But if you make a mistake, 
just let me know, so I can fix it. Anyways let's go through the simple steps. First of all navigate in a terminal to a 
directory where you want this repo. Anything that has a `{}` around it means you replace it with the necessary information. 
Here is a simple example: `git push {your_branch}` => `git push my_branch`. Let's go through the commands. I will have the 
commands with the "variables" and an appropriate example below for replacing the variables. And there is a great thing 
called ChatGPT and it can explain what all these commands mean. It can even explain the scary terminal!

### Setting up the repo
**The Terminal Commands**
```
git clone https://github.com/Micah-Ribbens/Robotics-Onboarding
cd Robotics-Onboarding
git branch -b {date}{your_initials}{task}
touch test.txt
git add test.txt
git commit -m "Setting up branch"
git push --set-upstream origin {your_branch}
```

**The Example**
```
git clone https://github.com/Micah-Ribbens/Robotics-Onboarding
cd Robotics-Onboarding
git branch -b 02_10_2024_MR_Assignment1
touch test.txt
git add test.txt
git commit -m "Setting up branch"
git push --set-upstream origin 02_10_2024_MR_Assignment1
```

### Submitting an Assignment
This is honestly about as easy as it gets now that the repo is set up! To state the obvious, you will need to commit 
your code to the local repo. I cannot see the work on your local computer through tea leaves (at least not yet!) Okay, 
now let's get to the big scary command:

git push

Yup, that's it! You are done! You have submitted your assignment! Now I will be able to see your work and give you feedback

