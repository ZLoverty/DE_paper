# DE_paper
Collaborate with Cristian to draft the paper on active fluctuations in double emulsions.

## Formatting guideline

1. Start a new line (\n) for each sentence. This is good for synctex (click pdf and find the line in tex), and also good for Git when comparing versions.
2. Communicate thoughts in comments. For example, if you think a figure of something is needed but missing some where, put a comment and describe the needs.
3. Colored text: I use red text to emphasize that the claim is not fully backed by our results. The wording may be modified in the future.
4. Figure crossref: at the beginning of a sentence, use `Figure~\ref{}`. Otherwise, use `Fig.~\ref{}`. Note that the `~` is to prevent line breaking in the middle of the crossref.

## Git workflow

### First time

1. Setup the local files by cloning the repo.

### Every time

1. Pull the main branch.
2. Create a new branch. It's preferred to name it with the thing you want to write, add or correct, so that when we merge the branch to main we will have a meaningful name.
3. Switch to your branch.
4. Edit and commit to your branch.
5. Create a pull request to merge the new branch to main.
6. If there are conflicts, we should set up a meeting to discuss.
7. Next time when you want to write, start from step 1.

NOTE: it's important to set a milestone (in mind) to a new branch. That is, once the goal is reached, merge it to main. On the contrary, if the goal is not reached, we should not simply merge it. We can still use the branch as a way of cloud storage without merging it.

The current workflow may result in many branches, but I don't think it is a problem, because we can delete them using the web interface. 
