# blank_deno_blog
a blank deno blog!

1. ☝️☝️☝️ ~> click "Use this template" to create a new repo with these files, in your account.  You can change the name, just be sure to remember what you named it - we will need that in a few steps.
2. Make sure you have [git](https://git-scm.com/) installed.
3. Using terminal (macOS) or PowerShell (Windows), navigate the location on your computer where you would like to put your blog repository:
   -  `pwd` will give you the present working directory
   -  `cd ..` moves you out to the parent folder
   -  `cd folder_name` moves you into the folder `folder_name`, providing such a folder exists in your current location
4. Type `git clone https://github.com/your_username/your_reponame`, where `your_username` is your username, and `your_reponame` is whatever name you gave the new repository in step 1. 
5. This should create a local repository in a folder with that name, in your current location. Use `cd` to navigate into that folder.
6. Type `open .` to open to that location in Finder (macOS), or `ii .` to open it in Windows Explorer.
7. Type `code .` to open that folder in VS Code (you might need to add `code` to `PATH`).
8. Type `deno task dev` to start serving your blog locally.  Navigate to the URL in a browser to view it.  The server will automatically update the page when you make changes to the blog, although you may need to refresh.
9. Make changes to the blog.
10. Push to the github repo with:
    -  `git add .`
    -  `git commit -m 'description of changes'`
    -  `git push`
11. Go to [deno deploy](https://deno.com/deploy), and link your github repo to make it live.