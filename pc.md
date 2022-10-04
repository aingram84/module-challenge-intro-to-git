## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
2. What is the difference between Git and GitHub?
3. Why do we create a branch?
4. What is the purpose of a Pull Request?
5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
7. What is a merge conflict?
8. How do you resolve a merge conflict?

1. Git is a version control mechanism.
2. The difference between Git and GitHub is that Git is a system, a method of doing things.  GitHuB is a container that contains and interprets those methods.  A similar comparison would be the internet vs. Internet Explorer, you open Internet Explorer to make use of the internet, not the other way around.
3. We create branches to work on pieces of code, features, or bugs in our own environment without effecting the original code.  In a sense, it is a form of Non-Destructive Testing.
4. The purpose of a pull request is to allow others to know that yuo have finished the coding that you wanted to do, and are ready to let others review it before merging it back into the main code.
5. THe command would be: git checkout main
6. 'git fetch' will download code from a repository's remote URL, 'git merge' will merge the work of other people with your own, "git pull" is a combination of the previous two commands.
7. A merge conflict is something that happens when multiple commits attempt to change the same line of code in a different way, or if the original file gets feleted.
8. You can resolve a merge conflict by opening the file with conflicts in a text editor.  There will be indicators for where the conflicts are.  You will have to decide which set of changes to accept into your merge and also need to delete the conflict indicators.  You would then add and commit once more, this time without the conflicting lines of code.
