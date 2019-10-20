<a href="https://wes-chen.github.io/build-a-website/">Return to course home</a>

# GitHub Desktop, GitHub Pages

You have already learned that GitHub is the largest code host on the planet with over 11.9 million repositories. Furthermore, you have learned that Git is a distributed revision control and source code management (SCM) system with an emphasis on speed.

Gaining an firm understanding of Git and GitHub features opens to developers a new and liberating approach to source code management. The surest path for you to master Git is to immerse yourself in its utilities and operations and to experience it first-hand.

## What are we doing today?

-   GitHub Desktop
-   GitHub Pages
-   Task for this lesson: Make your very first website!

## GitHub Desktop

### Common Git commands

To use the functions of Git and GitHub, we would normally need to use the [_terminal_](https://askubuntu.com/questions/38162/what-is-a-terminal-and-how-do-i-open-and-use-it) to utilize a command line interface (CLI) on our computers to save our code in the cloud. Here is what it looks like:

Initializing a repository:

```bash
git init
```

Cloning a repository:

```bash
git clone https://github.com/wes-chen/build-a-website.git
```

Pulling the most recent changes from your repository:

```bash
git pull
```

Committing some changes in your local machine:

```bash
git commit
```

Pushing your changes to the cloud (GitHub):

```bash
git push origin [branch-name]
```

![Git Workflow](https://raw.githubusercontent.com/wes-chen/build-a-website/master/lesson-02/gitLocalWorkflow.png)

### Fear not - GitHub Desktop to the rescue!

Many of you may be unfamiliar with what a command line interface (CLI) is. Fortunately, you do NOT have to learn this terminal bogus until you get to college where courses require you to use a CLI.

Alternative to using a terminal and CLI is to use [GitHub Desktop](https://desktop.github.com/).

GitHub Desktop makes it easy for us to do all of these Git operations with the click of a few buttons!

Let's try to pull our repository from last lesson, edit some files, commit our changes, then push it back to GitHub!

If you do not remember the contents of last lesson, no worries! [Here](https://wes-chen.github.io/build-a-website/lesson-01) is the last lesson. Please [create a GitHub account](https://github.com/join) or [log in to your GitHub account](https://github.com/login) and follow [this guide](https://guides.github.com/activities/hello-world/) to make your own repository!

1. Sign in to GitHub Desktop

![Github Desktop Login](https://raw.githubusercontent.com/wes-chen/build-a-website/master/lesson-02/github-desktop-first-screen.png)

Sign into GitHub Desktop with your user credentials.

2. Clone your repository from the cloud.

Select a repository to clone from GitHub. In this case, it should be your hello-world repository that you made last lesson.
![Github Desktop Clone Step 1](https://raw.githubusercontent.com/wes-chen/build-a-website/master/lesson-02/github-desktop-no-repos.png)

Clone your repository into your local machine wherever you want to store your files. Make sure it is at a location where you can easily find it!
![Github Desktop Clone Step 2](https://raw.githubusercontent.com/wes-chen/build-a-website/master/lesson-02/github-desktop-clone-a-repo.png)

Congratulations! You have successfully cloned your repository from the cloud. If you navigate to the folder to where you cloned the repository, then you should be able to find a README.md file!
![Github Desktop Clone Step 3](https://raw.githubusercontent.com/wes-chen/build-a-website/master/lesson-02/github-desktop-repo-view.png)

3. Make a few edits!

![Editing my files original](https://raw.githubusercontent.com/wes-chen/build-a-website/master/lesson-02/text-editor-original-text.png)
This is a screenshot of what I originally had in my README.md file. You can open your README.md file using any text editor, but our text editor of choice is [Atom](https://atom.io/).

![Editing my files edited](https://raw.githubusercontent.com/wes-chen/build-a-website/master/lesson-02/text-editor-edited-text.png)
Here, I have edited the contents of my README.md file! Feel free to make any changes you would like to your README.md file, and then press _CTRL + S_ (on Windows) or _CMD + S_ (on Mac) to save your changes to the README.md file. Suggestions for changes include: your name, your GitHub username, or a list of your hobbies. To learn about how to create different size fonts that will appear on GitHub later, check out this [short guide](https://guides.github.com/features/mastering-markdown/) for more information!

4.  Commit your changes to your local Git repository.

![Github Desktop Commit](https://raw.githubusercontent.com/wes-chen/build-a-website/master/lesson-02/github-desktop-view-changes.png)
If we check GitHub Desktop, then we should see either red or green highlights on the right indicating which lines of the README.md file have been altered. You should be able to commit these changes to your local repository on the [master branch](https://git-scm.com/book/en/v2/Git-Branching-Branches-in-a-Nutshell)! Remember to write a meaningful [commit message](https://chris.beams.io/posts/git-commit/) so you know why you made this change!

5.  Push your changes to the repository.

![Github Desktop Ready to Push](https://raw.githubusercontent.com/wes-chen/build-a-website/master/lesson-02/github-desktop-ready-to-push.png)
Now that I have committed something to my local repository, I am ready to push my local changes to my online GitHub repository! Click the "Push origin" button near the top of the GitHub Desktop interface.

![Github Desktop Pushed](https://raw.githubusercontent.com/wes-chen/build-a-website/master/lesson-02/github-desktop-pushed.png)
I have pushed my local changes to GitHub!

![See changes on Github](https://raw.githubusercontent.com/wes-chen/build-a-website/master/lesson-02/github-my-changed-repo.png)
If I check my GitHub account, I can see my new changes reflected online on GitHub. If you are unable to find your repository, clicking on your profile should give you a list of your own repositories.

## GitHub Pages

GitHub has a really awesome feature where you can host your own website FOR FREE! All you need to do is create a repository named [your username here].github.io and it'll automatically host your website at [your username].github.io. It is pretty nifty, and it doesn't cost a dime!

[This tutorial](https://www.thinkful.com/learn/a-guide-to-using-github-pages/) runs through the basic workflow of using GitHub Pages. However, instead of the terminal nonsense, follow these steps:

1.  [Make a new repository](https://github.com/new) on GitHub.
2.  For repository name, enter: `username.github.io` ( Ex: if your username is `danHuang` then your repo name would be `danhuang.github.io`).
3.  Make the repository public.
4.  Check `Initialize the repository with a README`.
5.  Click `Create Repository`. ( If the button is grayed out please make sure the form has been filled out. )

<table border="0">
 <tr>
    <td><b style="font-size:30px">GitHub Desktop Workflow</b></td>
    <td><b style="font-size:30px">Alternative Workflow</b></td>
 </tr>
 <tr>
    <td width="50%">6. Open GitHub Desktop and clone the repository. </td>
    <td>6. In the repository, click <b>Create new file</b>.</td>
 </tr>

 <tr>
    <td>7. In any text editor, type "<b>Hello World!</b>".</td>
    <td>7. In the file editor, type "<b>Hello World!</b>". </td>
 </tr>
 <tr>
    <td>8. Save the file as "<b>index.html</b>" inside the repository folder.</td>
    <td>8. Name the file as "<b>index.html</b>". </td>
 </tr>
 <tr>
    <td>9. On GitHub Desktop <b>commit</b> the changes and <b>push</b> them to the online repository.</td>
    <td>9. Click <b>Commit new file.</b></td>
 </tr>
</table>
<br>

10. Go to <https://[your-username].github.io> to see your website! (Make sure to use your own username in the link)
    <a href="https://wes-chen.github.io/build-a-website/lesson-02/example.html">Here</a> is an example of what you should expect to see.
    <br>

11. Congratuluations! You are now hosting your mini website on GitHub Pages! If you would like to add text to your website, then you can edit _index.html_ in anyway you like, commit those changes to your local repository, then push those local changes to the online [username].github.io repository. You will be able to see your changes if you follow those steps correctly!
    <br>
    <br>

**Note:** If you want to go through the tutorial yourself, here are the steps after opening the Thinkful link:

-   At Step 1: Click `Starting from scratch`.
-   At Step 2: Click `User Pages`.

## CHALLENGE 01:

Knowing that you can use GitHub Pages to host your own website, your challenge is to make some simple changes to your single-paged website.

The challenge for this lesson will be the simplest out of all of the challenges from all of the lessons.

CHALLENGE: Remove the "Hello World!" text from the webpage and replace it with four separate lines:
   1. Your full name
   2. Your GitHub username
   3. Your favorite food(s)
   4. Your hobbies

To make sure your changes worked, always check your GitHub Pages website at [your username].github.io.

## Next Lesson

Next lesson, we learn about the essentials of HTML. HTML provides a skeleton for your webpage so that it will start to have a structure to it. If you are looking to get ahead, please run through this [CodeAcademy tutorial](https://www.codecademy.com/learn/learn-html) at your own pace before the next lesson.

<a href="https://wes-chen.github.io/build-a-website/">Return to course home</a>
