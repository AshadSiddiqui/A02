# A02

Part 1: Step-by-Step Instructions for Using WebStorm with GitHub

1. Download and Install WebStorm
Go to: https://www.jetbrains.com/webstorm/download/
Install WebStorm on your computer by following the installer instructions.

2. Open WebStorm and Create a Project
- Launch WebStorm.
- Click New Project
- Choose your desired folder location and click Create

3. Initialize Git in WebStorm
- Go to VCS > Enable Version Control Integration
- Choose Git from the dropdown
- This will initialize a Repository in your project folder.

4. Commit Changes
- After editing files, go to VCS > Commit or press Ctrl + K
- Write a meaningful commit message (e.g., Task: Created index.html)
- Click Commit

5. Connect to GitHub
- Go to File > Settings > Version Control > GitHub
- Click Add Account and log in to GitHub
- In your project, go to Git > GitHub > Share Project on GitHub
- Enter A02 as your Repository name and click Share

6. Push Changes
- Go to Git > Push or use Ctrl + Shift + K
- This uploads your commits to GitHub

7. Pull or Fetch Updates
- Use Pull to download and apply updates from GitHub
- Use Fetch to check for updates without applying them

8. Create a New Branch (Optional)
- Go to Git > Branches > New Branch
- Name your branch and click Create

9. Merge Branches
- After switching back to your main branch, go to Git > Branches > Merge
- Choose the branch you want to merge
- If there's a Merge Conflict, WebStorm will help you resolve it

Part 2: Glossary of Git Terms

- **Branch** - A separate line of development in a Git project.
- **Clone** - To make a full copy of a GitHub repository to your local machine.
- **Commit** - A snapshot of changes in your project with a message.
- **Fetch** - A command that checks for changes in a remote Repository without merging.
- **GIT** - A version control system used to track changes in code.
- **Github** - A platform for hosting and sharing Git Repositories online.
- **Merge** - The process of combining changes from one Branch into another.
- **Merge Conflict** - A situation when Git cannot automatically merge files and requires manual     resolution.
- **Push** - Sending local Commits to a remote Repository.
- **Pull** - Downloading and merging changes from a remote Repository.
- **Remote** - A version of your project hosted on another server like GitHub.
- **Repository** - A directory that contains your project files and Git history.

References
- GitHub Docs: https://docs.github.com
- JetBrains WebStorm Docs: https://www.jetbrains.com/help/webstorm/
- Pro Git Book: https://git-scm.com/book/en/v2
