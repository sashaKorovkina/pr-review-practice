# Practice for Your Pull Request Review Interview

I made this while preparing for a pull request review interview and thought it could be helpful for someone out there... 

# Contents 
- [How to create a good pull request?](#how-to-create-a-good-pull-request)
- [How to review a pull request?](#how-to-review-a-pull-request)

# How to create a good pull request?

(Add your content here)

# How to review a pull request?
1. Look at the title and the description. In particular:
- Does the pull request solve a specific issue?
- If it does link to the issue, read the issue 
- Does it contain any instructions on how to reproduce the change - API keys, build instructions etc.?
- If there are insufficient instructions - leave a comment for the person on the other end to give you the data

2. Look at the files changed.
- Once you have seen the files changed, you should have an idea of what the code is doing. If it is not evident from a poorly written title or description - you can go back and change the text there.
- Look at the commit history to understand the development process. There might be a need to squash the commits.

3. Reproduce the commit locally
- Grab the name of the branch on which the changes were made and reproduce the locally by using the following command: git checkout branch-name
- See if there are any errors when you reproduce it locally - is it a problem with the code or is it a problem with the description of the code?

4. Now you have run the code locally...you understand what works and what needs to change and it is time to make some comments
- In most cases, you would need to open a review session. This is useful if you are making a bunch of comments which you don't want to spam the receipient with
- 

# Bonus Info
1. Should you use a PR review interview:
https://blog.brujordet.no/post/devops/open_a_pull_request_to_merge_this_engineer/
