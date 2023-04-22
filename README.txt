1. "git init" -> powers your folder to be managed by git, and initialises a new repository. 
It also creates a new .git folder that has all relevant logic to make versions of your project.


2. 'Working area' -> There can be a bunch of files that are not currently handled by git.
It means that changes done or to be done in those files are not managed by git yet. A file which is in working area is considered to be not in staging area.
When we do "git status" and we see bunch of untracked files, then these are called to be in working area.

3. 'Staged area' -> What all files are going to be part of next version that we will create.
This staged area is the place where git knows what changes will be done from last version to next version.

4. 'Repository area' -> This area contains details of all previous registered versions. Files in this area are already managed by git and knows their version history

5. 'git add <file>' -> moves file from working to staged area
6. 'git rm --cached <file> ' -> brings back file from staging to working area.

7. 'commit' -> it is particular version of project.
it captures a snapshot of the projects, staged changes and creates version out of it.

8. 'git commit' -> registers changing changes to a commit 
