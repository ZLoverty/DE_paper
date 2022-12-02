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
2. Merge main branch to your branch.
2. Switch to your branch.
3. Edit and commit to your branch.
4. Create a pull request to merge the new branch to main.
5. If there are conflicts, we should set up a meeting to discuss.
