# Lab 4 Notes

1. --global saves the setting for every repository on my computer (in ~/.gitconfig). Without it, the setting would only apply to the repository I am currently in.

2. A hidden folder called .git appeared. It stores the repository's history, commits and settings.

3. Git offered to track only 2 items: README.md and week02/. Nothing looked like code I did not write, since I have no .venv folder.

4. Nothing disappeared, because I did not have a .venv folder. The only change was that .gitignore appeared as a new untracked file.

5. It should be committed, so that everyone who uses the repository ignores the same junk files.

6. README.md moved from "Untracked files" to "Changes to be committed". It went from the working directory to the staging area.

7. Git printed the commit hash 07c51ff and said 3 files changed, 4 insertions, listing .gitignore, README.md and week02/notes.md.

8. They are the short commit hash. It is a unique ID used to refer to that specific commit.
