# Getting started with Git Lab
## Instructions
In this lab, we'll be going through some basic tasks you'll need to do as you manage the GitHub repository for your CollectionBuilder site. The questions below are designed to help you learn and remember what you need to do to perform these tasks, as well as where you can go to look for help. 
## Creating your repository and editing files
**What did you click on to create a new repository in the web interface of Github (i.e., on Github.com)?**  
The + sign on the top right corner (4th to the left of the profile button) and then "New repository" in the drop down menu.

**What is the difference between a private and a public repository?**  
Public repositories are available to everyone on the internet, whereas private repositories are only available to the owner, people the owner explicitly shares access with, and organization members in the case of private repositories owned by organizations.

**Once your repository has been made and has at least one file, what button do you need to click on the web interface in order to create a new file in your repository?**  
The "Add file" button on the left of the green "Code" button, and then "Create new file" in the drop down menu.

**Describe the steps you took to clone your repository on Github Desktop**  
I clicked on "File", then "Clone repository" and then selected "markdown-playground" from the list.

**What is the title of GitHub documentation?**  
GitHub Docs

**What is the URL for GitHub documentation on creating your first repository?**  
https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-new-repository 

**Where is your local repository versus the remote repository?**  
The local repository is stored on my computer (which I can access through GitHub Desktop), while the remote repository is exists online (can be accessed through the GitHub site).

**What happens when you fetch?**  
Fetch on GitHub Desktop retrieves updates and new commits from the remote repository to the local repository. It allows you to see what new changes have been made, without immediately implementing those changes to the local copies of repo items.

**What happens when you pull changes/commits?**  
Pull implements the new changes and commits to the repo items in the remote repository to the local copies of those items.

**When working on GitHub Desktop, what order should you generally perform push, pull, and fetch?**  
Fetch should be performed first, in order to view new changes or commits done on the remote repo.  
Pull should be performed second, in order to merge the changes and commits from the remote repo to the copies of the items in the local repo.  
Lastly, and after having made changes on the local copies, we perform push, to push those changes to the remote repo.

**What happens when you push commits from your local repository?**  
Push implements the changes or commits from the local repository to the remote repository.

**What is the URL for the Github glossary?**  
https://docs.github.com/en/get-started/learning-about-github/github-glossary

**Where can you find a list of your commits?**  
A list of commits can be found under "History" on GitHub Desktop (towards the top left, under the repository name, and to the right of "Changes").

**What is the URL for documentation on reverting a commit?**  
https://docs.github.com/en/desktop/managing-commits/reverting-a-commit-in-github-desktop

**How do you revert a commit?**  
Find the commit you want to revert under "History", right-click on the commit, and click on "Revert changes in commit" in the pop-up menu.

## Git-flavored markdown
**What is the name of the page or URL in GitHub documentation where there's information on how to format your Markdown for GitHub?**  
The name of the page is "Basic Writing and Formatting Syntax" and the URL is https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#GitHub-flavored-markdown.

**What precedes a second-level heading in Github markdown?**    
`##`

**How do you indicate text that has been struckthrough?**  
`~~ ~~` or `~ ~`

**How do you create a hyperlink in your markdown?**  
`[text](link)`

**How do you link to a section in the same or another markdown file?**  
According to the documentation, "To link to a section in the same Markdown file, use the header text as the anchor. Replace spaces in the header text with hyphens and make it lowercase. For example, if the header is `## My Section`, the link would be `[My Section](#my-section)`.To link to a section in another Markdown file, include the file path followed by the anchor. For example, `[My Section](path/to/file.md#my-section)`."

**What are the three possible symbols for indicating an unordered list?**  
`-` , `+` and `*`

**Format the following text into a footnote:**    
Alex Wingate went to William and Mary. [^1]  
[^1]: [William and Mary](https://www.wm.edu/) is a university in Williamsburg, VA founded in 1693. 
