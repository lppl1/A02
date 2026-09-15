# A02
IS117 || FALL2026

---Tutorial---
1. Go to https://git-scm.com/downloads and download Git for your OS
2. Run the installer and accept the default settings (Microsoft, 2026a)
3. Open a terminal (Git Bash on Windows) to confirm install with *git --version*
4. Go to https://code.visualstudio.com/ and download VS Code
5. Run the VS Code installer with the default settings
6. Go to https://github.com/signup and create a free GitHub account (Hendela, 2019; Microsoft, 2026b)
7. On GitHub, click the + icon in the top-right corner
8. Select *New Repository*
9. Name the repository *A02*
10. Set the visibility to *Public*
11. Check the box *Add a README file*
12. Click *Create Repository* (Hendela, 2019; Hendela, 2020)
13. On the new repo page, click the green *Code* button
14. Copy the HTTPS URL that it shows you (EX: https://github.com/yourUserorUCID/A02.git)
15. Open a terminal and navigate to where you want to project to be saved: *cd Documents* (or whatever other folder you want)
16. Once you are in the correct directory, clone the repository with *git clone https://github.com/yourUser/A02.git* (Microsoft, 2026b)
17. Doing this creates a new folder named A02 on your device
18. Open VS Code
19. Click *File*, then *Open Folder*
20. Select the A02 folder
21. Open a terminal inside VS Code by clicking *Terminal,* then *New Terminal,* then selecting *bash*
22. Set your Git username with *git config user.name "yourname"*
23. Set your Git email with *git config user.email "youremail@whatever.com"* (Microsoft, 2026a; Microsoft, 2026b)
24. Open the *README.md* in the file explorer
25. Edit the file and add some text like *gitignore*
26. Save the file (either manually or with *CTRL + S*)
27. Stage your changes *git add .* (Microsoft, 2026a)
28. Commit your changes *git commit -m "whatever message you would like"* (Microsoft, 2026a; Hendela, 2020)
29. Push your commit to GitHub with *git push origin main* (Microsoft, 2026a; Hendela, 2020)
30. Go to your repo page on GitHub
31. Refresh the page
32. Confirm that your edited README.md now shows the changes (Hendela, 2020)

---Glossary---

**Branch** - a separate line of development within a repository (Git, n.d.)

**Clone** - downloading a copy of a remote repository to your local machine (Git, n.d.)

**Commit** - saving a snapshot of staged changes with a message (Hendela, 2020)
 
**Fetch** - downloading the changes from a remote repository without merging them (Git, n.d.)

**GIT** - is an open source version control system used to track changes to source code (Hendela, 2019)

**Github** - is an online platform for hosting Git repositories (Hendela, 2019)

**Merge** - combines changes from one branch to another (Git, n.d.)

**Merge Conflict** - is a conflict that occurs when Git can't automatically reconcile differing changes (Git, n.d.)

**Push** - uploads local commits to a remote repository; like from VS Code to Github (Hendela, 2020)

**Pull** - downloads and merges changes from a remote repository (Git, n.d.)

**Remote** - is a version of a repository hosted elsewhere, such as on GitHub (Hendela, 2020)

**Repository** - a folder tracked by Git containing a project's files and history (Hendela, 2019)

---References---

Git. (n.d.). *gitglossary*. https://git-scm.com/docs/gitglossary

Hendela, A. H. (2019). *Introduction to GitHub and WebStorm* [PowerPoint slides]. NJIT, IS117.

Hendela, A. H. (2020). *Additional instructions on creating a Git and GitHub repository*. NJIT.

Microsoft. (2026a). *Source control in VS Code*. https://code.visualstudio.com/docs/sourcecontrol/overview

Microsoft. (2026b). *Work with GitHub in VS Code*. https://code.visualstudio.com/docs/sourcecontrol/github