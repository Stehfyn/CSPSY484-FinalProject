# CSPSY484-FinalProject

<p align="center">
  <img width="100%" height="vw5625" src="common/4-08.gif?raw=true">
</p>

### Your first commit


#### Background
Our VR project uses `Unity` as the Editor/Game Engine. Our project is essentially a whole bunch of files where these files collectively make up our game. To manage the versions and existence of these files as we collectively work on the project, we'll be using `Git` as our source control tool.

`Git` manages things called `repositories`. A repository is just a folder with a whole bunch of files and subfolders! Therefore, we can think of our VR Project as analogous to a repository, where:

```
/CSPSY484-FinalProject─┐
                       │
                       ├─/484Project (Our Unity Project)
                       │
                       ├─/common     (Repository media, like the .gif you see at the top)
                       │
                       ├─/docs       (Our Canvas assignments)
                       │
                       ├─LICENSE     (A trivial but necessary software license)
                       │
                       └─README.md   (A Markdown file, or literally the file you're reading right now! Github will automatically 'render' or display these files when placed in a repository.)
                       
* the '/' character denotes a folder!
```


#### Checklist
We need to download two software applications to work on our project:
- [Unity 2021.3.20](https://unity.com/releases/editor/whats-new/2021.3.20) 
- [Github Desktop](https://desktop.github.com/)

On the Unity download page, scroll to find the appropriate version for your system and select the relevant:

![image](https://user-images.githubusercontent.com/67705843/231612371-52828c89-c5f3-4a53-b57a-7059f52181ac.png)

If you're on macOS, follow these steps to discover your architecture:
1. Go to the apple logo, and click about this mac
2. Look in the information box, it should give details like Storage, memory, and processor.
3. If your processor is a INTEL processor, its X64
4. If it says Apple M1 or M2, it’s arm.

#### Cloning the repository (Downloading the project)
Once both software applications are installed, open up Github Desktop.
1. Select `File` > `Options` > `Accounts`, then sign in with your GitHub account.
2. Select `File` > `Clone Repository` > (Under *your repositories*) `Stehfyn/CSPSY484-FinalProject` > `Clone` 
* Make sure you remember the path to where you cloned (downloaded) the repository! For me it was:

![image](https://user-images.githubusercontent.com/67705843/231613960-8b895695-df95-4f7d-9072-5193cb725b1a.png)

#### Opening the VR project
1. Launch Unity Hub
2. Select `Open` > find where you cloned the repository, then select and open `484Project`

On Windows, that looks something like this: 

![image](https://user-images.githubusercontent.com/67705843/231614778-51092548-1470-475f-9b73-004caf3899f5.png)

* Opening the project may take a long time to load as it builds the necessary files and binaries


#### Workflow
Once `Unity` has finished opening our project, we should see something like this:

![image](https://user-images.githubusercontent.com/67705843/231615345-3bf92113-be33-4218-aca9-5ccf85bac4d9.png)

First, `Fetch origin` in `Github Desktop` to retrieve the most recent version of the project:

![image](https://user-images.githubusercontent.com/67705843/231619255-a7794fb8-3357-4477-bd5d-c51c71feb0f8.png)

Find the `Project` window at the bottom of the screen, and double select `Assets`>`Scenes`>`MainScene` to load `MainScene` in the Editor.

![image](https://user-images.githubusercontent.com/67705843/231615616-eb25ee49-3cbf-4922-8859-7bc730768990.png)

Our first commit will be to create a new `Scene` file to act as our personal workspace that we can work on or test things out without affecting `MainScene`. Since we are not using branches or know what kinds of prefabricated items we need just yet, we will use personal `Scene` files as a workaround.

To create a personal `Scene` that uses our `MainScene` as a template, we can create a copy of `MainScene` and rename it:
1. With the `MainScene` file selected, select `Edit` > `Duplicate`, and should see a new `Scene` file named `MainScene 1`
2. Select `MainScene 1`, then double-click its name and rename it to `<YourName>Scene`

`Github Desktop` should now see your updated changes, for me it looks like:

![image](https://user-images.githubusercontent.com/67705843/231617370-e846ae7e-e710-4511-afbd-51e83f1e37e7.png)

To commit these changes from `Github Desktop`:
1. Add a summary of your changes (required)
2. Add a description of your changes (optional)
3. Select `Commit to main`
4. Select `Push origin` to push these changes to our public repository

If you now refresh our Github repository webpage, you will now see your commit is now available for everyone else:

![image](https://user-images.githubusercontent.com/67705843/231618353-89048cce-5dff-4297-81c5-b4c862e6f934.png)

#### Additional commits
When working on the project make sure to `Fetch origin` before making a commit in `Github Desktop` to ensure your commits do not conflict with others' changes. To avoid these conflicts as best one can, it is best to `Fetch origin` often while working on the project.

![image](https://user-images.githubusercontent.com/67705843/231619141-8266695f-2f51-49a4-96b8-4ac41bb0a286.png)

 
