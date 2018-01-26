# hello-world

## Workflow of GitHub


### Created an open source repository
- A repository: uses to organise ONE project. In order words, one repository:one prject.
- A repository or repositories can contain folder, files, images, videos, spreadsheets, data sets and etc.
- Basically it can contain anything that a project needs.
- Wokrkflow: 
    1. Click on `+` at the upper right corner.
    2. Select **New repository**, name it and write a short description.
    3. Select **Initialize this repository with a README**. 
    4. Click on **Create repository**.

### Started and managed a new branch
- Braching can treat as a different working versions of a repository (project).
- A repository has a default brach named **`master`**.
- Creation of a branch off the **`master`** branch will duplicate of the **`master`** branch as it was at that point in time. 
- By doing so, contributors (e.g. developers, writers, designers, programmers, scientists and etc) can work seperate without messing up contains of the **`master`** branch.
- When a change is ready, contributors can merge their branch into the **`master`** branch.
- Workflow:
    1. Go to the desire repository.
    2. Click on the drop down menu `branch:master`.
    3. Type a branch name for a new branch from `master` branch.
    4. Select the blue **Create branch** box or press *enter* key.
    
### Changed a file and committed those changes to GitHub
- Apparently, changes (saved changes) on GitHub are named as *commits*. 
- Each commit has its assigned message, which named as *commit message*. 
- The commit message is a decription of a/the change makes.
- Why commit message is important? 
    - It contains history and description of changes, thus, other contributors can understand why and what.
- Workflow:
    1. Click on the desire file. 
    2. To edite the file contant, click on the pencil icon on the upper right corner of the file view.
    3. Modify the file's contant. 
    4. Write also a brief decription about the commit changes (kind like comments in codes) 
    5. Press **Commit changes** button to make the changes.

### Opened and merged a Pull Request
- `Pull Request` : the heart of collaboration on GitHub.
- This feature allows contributors:
  - to propose their changes
  - to request for a review of their changes from other contributors
  - to allow other contirbutors to pull and merge one's contribution into their branch.
- The feature shows differences or `diffs` of the content from both branches, `base/branch` compare with `branch`.
- The changes and additions are shwon in **GREEN** while subtractions are shown in **RED**.
- `@mention` in pull request message allows contributors ask for feedback from specific people or groups.
- After that, contributors can merge changes from their branch into the **`master`** branch.
- Workflow:
    1. Click on **Pull Request** tab.
    2. Then, click on green **New pull request** button.
    3. Select the brach to compare with `master` branch in the **Example Comparisons**. Always, branching *branch* compare with `master`branch.
    4. Changes are shown on the **Compare** page. Check them careully.
    5. Click on green **Create Pull Request** button to submit the changes.
    6. Write a breif discription about the changes and give a title for the full request.
    7. If everthing was fine, merge the branching *branch* into the `master`branch by clicking on green **Merge pull request** button.
    8. Click on **Confirm merge** button to merge the changes.
    9. After the changes have been incorporated, it is safe to delete the branching *branch* by pressing on purple **Delete branch** button.
