## Getting Started

1. [Creating a Git repository](#creating-a-git-repository)
2. [Git Plugin](#git-plugin)

### Creating a Git repository

1. Open [Jupyter Notebook](https://jupyter.bangor.ac.uk/jupyter) in your browser.
    - Jupyter Notebook is a web-based interactive development environment (IDE) that allows you to create and share documents that contain live code, equations, visualizations, and narrative text.
<p align="center">
    <img align="center" src="img/jupyterhub-login.png" width="60%">
</p>

2. Open the File Browser by pressing `ctrl + shift + F` (Windows).
    - The File Browser is where you can navigate and manage files and folders on your system.
<p align="center">
    <img align="center" src="img/file-browser.png" width="60%">
</p>

3. To create a new folder for storing your project files, right-click on the File Browser window and select "New Folder". Name the folder "hello_world".
<p align="center">
    <img align="center" src="img/new-folder.png" width="60%">
</p>

4. Double-click the newly created "hello_world" folder to open it.
<p align="center">
    <img align="center" src="img/hello-world-folder-open.png" width="60%">
</p>

6. Click on the "Git" plugin in the left-hand menu.
    - The Git plugin allows you to manage Git repositories directly from within Jupyter Notebook.
<p align="center">
    <img align="center" src="img/github-plugin.png" width="60%">
</p>

7. Click "Initialize a Repository" in the Git plugin menu.
    - This will create a new Git repository in your "hello_world" folder.
    - Initializing a repository is an important step in version control with Git. By initializing a repository, you are essentially telling Git to start tracking changes to your files and directories within that repository.
<p align="center">
    <img align="center" src="img/initialize-a-repository.png" width="60%">
</p>

8. Confirm that you want to initialize the "hello_world" directory by clicking "Yes."
    - When you initialize a repository, Git will create a hidden directory named ".git" within your "hello_world" folder. This directory contains all of the metadata that Git uses to track changes and manage the repository.
<p align="center">
    <img align="center" src="img/initialized-repository.png" width="60%">
</p>

By following these steps, you have successfully created a new Git repository for your project in Jupyter Notebook. From here, you can start adding files to your repository and committing changes to track the progress of your project over time.

---

### Git Plugin

The Git Plugin is a feature within Jupyter Notebook that allows you to manage Git repositories directly. It displays the current Git repository and branch you are working with, and shows the changes made to files in the repository grouped into three categories: "Staged," "Changed," and "Untracked." The plugin also provides options to initialize a new repository, commit changes, and push/pull changes to/from remote repositories.

1. **Current Repository** and **Current Branch**
    - This tab displays the current Git repository and branch that you are working with in Jupyter Notebook.
    - This information can be useful when working with multiple repositories or branches, as it helps you keep track of which one you are currently working on.

2. **Changes**
    - This tab displays the changes that have been made to files in the current Git repository.
    - The changes are grouped into three categories: "**Staged**," "**Changed**," and "**Untracked**."
        - **Untracked** changes can be compared to unfinished sketches or drafts that you're working on but haven't yet decided whether to incorporate into your final artwork. You may have ideas in your head or on paper, but they haven't been formally added to your project yet.

        - **Changed** changes can be compared to preliminary versions of your artwork that you're in the process of refining. You've already started working on them and may have made significant progress, but they're not yet ready to be considered finished.

        - **Staged** changes can be compared to the final version of your artwork that you've completed and are ready to display or share. You've put the finishing touches on it and are happy with how it looks, and now it's time to make it available to others. Similarly, staged changes are those that you've reviewed, finalized, and are ready to commit to the repository for others to see.
 
