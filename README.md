Question 1: Why does Git show these files as untracked?
    Answer: They are newly created files in your working directory that Git isn't watching yet until you explicitly use git "add ."
Question 2: What information does git diff provide?
    Answer: A line by line breakdown of additions and deletions made to your files since your last commit.
Question 3: What is the purpose of git restore?
    Answer: It discards uncommitted changes in your working directory to revert a file back to its last committed state.
Question 4: What does git revert do?
    Answer: It creates a new commit that undoes the changes from a previous commit, safely keeping your project history intact without rewriting past history.
Question 5: How is git revert different from git restore?
    Answer: git restore is used for uncommitted changes in your working directory, throwing away local edits and reverting a file back to its last saved/committed state.

    git revert is used for already committed changes in your project history, creating a whole new commit to undo them safely.