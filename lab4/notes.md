# Lab 4 Notes

1. --global saves the setting for every repository on my computer (in ~/.gitconfig). Without it, the setting would only apply to the repository I am currently in.

2. A hidden folder called .git appeared. It stores the repository's history, commits and settings.

3. Git offered to track only 2 items: README.md and week02/. Nothing looked like code I did not write since I have no .venv folder.

4. Nothing disappeared because I did not have a .venv folder. The only change was that .gitignore appeared as a new untracked file.

5. It should be committed so that everyone who uses the repository ignores the same junk files.

6. README.md moved from "Untracked files" to "Changes to be committed". It went from the working directory to the staging area.

7. Git printed the commit hash 07c51ff and said 3 files changed, 4 insertions, listing .gitignore, README.md and week02/notes.md.

8. They are the short commit hash. It is a unique ID used to refer to that specific commit.

9. The loop is: edit a file, stage it with git add, commit it with git commit and check with git status / git log.

10. README.md is the first file people see when they open the repository  and GitHub automatically shows it on the front page. It explains what the project is  so it needs a standard name that everyone and every tool recognises.

11. gh auth login saved a login token on my computer and set up Git to use it   so Git uses that token instead of asking for a password when I push.

12. The README is shown on the front page below the list of files. GitHub automatically displays README.md because it is the standard file that explains what the project is.

13. No. git log --oneline shows the same 3 commits as before. Pushing only sent a copy to GitHub and did not change my local history.
14. A private repository exists on GitHub, but only I and the people I invite can see it. If it did not exist at all there would be nothing online for anyone including the TAs to see.
