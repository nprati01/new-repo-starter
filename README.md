# new-repo-starter

## Setup 

1. Click the `fork` button in the top-right corner of this webpage. 
1. The browswer will navigate to a new page for creating a fork, make sure that your user name is displayed and select `Create Fork` button. 
1. Verify that the browser has navigated to a page that includes this url: `https://github.com/<your-gh-username>/new-repo-starter`.
1. Click the green `Code` butto and the `clone` button shown in the pop-up menu of your personal `new-repo-starter` repository. 

### Follow the rest of the instructions shown below:

1. Move to the `new-repo-starter` directory.
1. Open in VS Code: 
    
    ```bash
    code .
    ```
    
1. Edit the `tell-us-about-yourself.js` and answer the 5 questions
1. `Suggestion` In VSCode you can turn `Auto Save` on and  the changes you are making are will be saved with each keystroke.
1. Check the status of the repository:
    
    ```bash
    git status
    ```
    
1. You'll see that there are changes not staged for commit - let's stage them with this command:
    
    ```
    git add .
    ```
    
    Then check the status again. You'll see that there are now changes to be committed. Let's do so:
    
    ```bash
    git commit -m "Solve addOne"
    ```
    
    Check the status one last time. You'll see now that there are no changes to commit. We're ready to push the committed changes up to GitHub.
    
    ```
    git push origin main
    ```
    

## Congrats on saving your changes to the local repo and pushing it to GitHub! 
