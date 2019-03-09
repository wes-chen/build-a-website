# Welcome, Setup, Github Accounts

Welcome! This week we will talk about what we plan to do over the course of the next few weeks and some logistics.

## tl;dr of this program

You will learn how use Github, and will make your very own website.

## What are we doing today?

-   [Introductions](/#introductions)
-   Why are you here?
-   Google is your friend
-   What is git?
-   What is Github?
-   What is Github Desktop?
-   Task: Make your own github accounts.

## Introductions

### Wesley Chen

Hi! My name is Wesley Chen, and I am a sophomore majoring in Computer Engineering at UCSD. I am also minoring in Music.

Interests:

-   Computer
-   Music
-   Swimming
-   Sleep
-   Community Service

Why you should believe what I say:

-   I was also in high school two years ago

## What is Triton Software Engineering?

Triton Software Engineering (TSE) is a multidisciplinary student organization at UC San Diego. We partner with nonprofits to design and develop software (e.g. websites or mobile applications) pro-bono for social good, while giving our students practical, real world experience.

Our founding members established TSE in the spring of 2017. They saw that nonprofits had few resources to procure professional web and technical development services, and that for these nonprofits, antiquated processes and tools led to significant organizational breakdowns. By providing a venue for both student developers and nonprofits to connect, we foster growth in both social good and technical expertise.

We believe that technology should be accessible to the community and especially to those who serve the community; something as simple as a sleek, updated, and easy-to-use website or as complicated as a mobile app to track donations can have immediate impact and value for organizations of any size.

Let us help you help the community.

Check us out [here](https://tritonse.github.io)!

## Why are you here?

The goal of this program is to give you some insight into what it's like to be a software programmer. Maybe you'll get inspired and become a CTO of some company worth billions of dollars (if so, please hook me up with a job).

You'll learn how to make your very own website, which you can put on your college resume.

Having web development skills is quite important these days as our society transitions to heavily rely on the internet. [Instagram](https://instagram.com), [Facebook](https://facebook.com), [Twitter](https://twitter.com) are all websites that you probably use on a daily basis - people made those!

## Google is your friend

Any good programmer knows how to use Google. If you have a problem, you should ask the internet first. _Most_ of the time it is right. If you don't know, ask Google!

## Git

> If you are a programmer, you should know what Git is.
>
>  — <cite>Wesley Chen, 2019</cite>

You use Google Drive to store and view documents on the cloud. Programmers use Git and Github to store and view their code on the cloud.

[This guide](https://guides.github.com/introduction/git-handbook/) is pretty good at explaining what Git is. Read it, then we'll summarize the essentials again here.

Basically, Git is a system that keeps a history of any changes to files - it can help you determine exactly _what_ files changed, _when_ they were changed, _who_ changed them, and the reasons _why_ they were changed.

Git can be useful when keeping track of collaborative work. For example: when multiple people are working on a project, the collaborators can report their progress by creating their own personal branch to make any update or changes (e.g. adding code to a file or adding a new picture inside a folder), taking a "snapshot" of their changes, then asking to have this "snapshot" of their changes added to the main branch.

There are a bunch of uses for Git, such as:

-   Viewing the history of the entire project
-   Adding or modifying files
-   Creating your own branch to work on
-   Merging your own branch into the main branch

Below are some examples of basic commands:

> Create your own project repository from scratch.

`git init [folder_name]`

A repository named `[folder_name]` will be created and will become your working directory (i.e. folder that holds your project)! Now, any changes you make can be committed into its history.

> Clone an existing project repository from somewhere online.

`git clone [git_link]`

This will download the latest "snapshot" from that online repository and become a working directory for you.

> View the status of your current working directory.

`git status`

This will print some basic information, including the files you have changed, and any changes ready to be "snapshotted" into history.

There are a bunch of stuff to understand about Git (which can be learned through the handbook above), but the basic flow of using Git in a personal project goes something like this:

1.  You make any changes you want to your working directory (whether you checked-out a branch or not - just anywhere in the project directory).
2.  Once you are satisfied with those changes, you can stage them to the staging area. In other words, this is where you take those "snapshots" of the changes then add it to an temporary "changes" area before you actually add it to your history of changes. To stage everything in your working directory, you would type the following in the terminal: `git add *`.
3.  Once you are satisfied with all "snapshots" in your staging area, you can commit them, which takes these "snapshots" and permanently stores them to your local Git directory. In other words, your changes are now part of the project history and in the future, you can always check what changes you have made at this point. To commit everything in your staging area, you would type the following in the terminal: `git commit -m [message]`. Inside `[message]`, you can type why you decided to make these changes (honestly just type anything).

Here is a picture if it helps:

![local workflow](https://github.com/wes-chen/build-a-website/blob/master/lesson-01/gitLocalWorkflow.png)

If you still are confused (even after reading the handbook), don't forget that Google is your friend - feel free to ask it anything you need help with!

## Github

[Github](https://github.com) is a website that helps us developers store and manage our code. [Google search results](http://lmgtfy.com/?q=what+is+github) can give us more insight into what Github is. Some features that Github have make it really easy for us to do cool things, like [contribute without knowing command line](https://desktop.github.com/) or [have our own website hosted online for free](https://pages.github.com/)!

## Github Desktop

Next time, we will explore what [Github Desktop](https://desktop.github.com) is and how we will use it. Github Desktop is an application that allows us to use Git without needing a command line interface.

## Task: Make a Github account!

One of the first steps of being a legit programmer is making a Github account.

![sign-up page](https://raw.githubusercontent.com/wes-chen/build-a-website/master/lesson-01/github-sign-up.png)

Steps:
1.  Go to [github.com](https://github.com).
2.  Sign up for an account.
3.  Think about your username! If you want to show off your work, colleges will see your github username attached to it. So while _xxxBigBallerMoneySwagMasterxxx_ is a cool username, it probably won't reflect well in front of the college admissions staff. Fortunately, you can change it afterwards in your settings.
4.  Follow the instructions of this [guide](https://guides.github.com/activities/hello-world/) to make your very first repository!
5.  Congratulations! You're one step closer to becoming a developer!
