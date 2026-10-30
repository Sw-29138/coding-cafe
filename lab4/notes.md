question 1. Using --global means my name and email are saved for all Git projects on this computer. If I leave it out, it only saves for this current folder.

question 2. A hidden folder named .git appeared. Inside it, Git stores all the history, settings, and tracking information for this project.

question 3. Git is offering to track 0 files because I created a brand new empty folder for this lab.I previously worked in windows powershell. Do not see any auto-generated files like .venv right now. 

question 4. Because I started with a new empty folder, nothing disappeared. But normally, this step hides auto-generated files like .venv and __pycache__ from Git.

question 5. The .gitignore file should be committed. This makes sure that the rules for ignoring files are saved and shared with anyone else working on this project.

question 6. Readme.md moved from "Untracked files" to "Changes to be committed". In the three-places model, the file moved from the working directory to the staging area.

question 7.The commit message says 3 files changed. In the three-places model, these files moved from the staging area into the repository. They are now permanently saved as a commit in the project's history.

question 8. The first seven characters are called the commit hash (or short hash). They act as a unique ID to identify that specific commit in the project's history.

question 9.The four steps of the cycle are: 1. Edit or create a file, 2. Check the state using git status, 3. Stage the file using git add, and 4. Save the changes using git commit.

question 10.Readme.md gets a special name and is placed in the main folder because it acts as the project's front page. Platforms like GitHub automatically look for this specific file and display its contents to anyone visiting the repository.

question 11. gh auth login securely connected my local Git terminal to my GitHub account using a web browser token. It saves my credentials locally so I don't have to manually type my password every time I push code.

question 12. The README.md file is showing on the front page. This happens because GitHub automatically looks for a README file to render as the introduction or landing page for the repository.

question 13. No, pushing did not change my local history. It simply copied my existing local commits to the remote GitHub repository.

question 14. A private repository exists safely on GitHub's cloud servers as a backup, but it is only visible to me and the specific people I invite. If it does not exist on GitHub at all, the code only lives locally on my laptop with no cloud backup or way to share it.