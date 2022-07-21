# neuromatch-compneuro-2022-project
Files for the NMA 2022 behavior project by the Sfenj1 group
> **Warning**
> You can now open the notebooks by opening them in Github (click above) and then use the "Open in Colab" link

## Structure 
* There is a `main` and a `development` branch (see dropdown menu on the top left)
* The idea is that `main` is always stable and will run when executed in Google Colab, `development` is where recent code additions get tested before they are pulled into `main`.
* Therefore: Please direct pull requests towards `development`
* Workflow for getting your code into `main`:
    * fork this repository (if you have not done so already)
    * change code in your local development branch (you can use the "File -> Save to Github" option in Google Colab to transfer your changes in Colab directly to your forked repo)
    * make sure there is some documentation (either in code or as text cells) stating what your code does, the algorithm you used, and why you picked this specific approach
    * make sure that your code runs in the latest version of the development branch by pulling the latest changes from `development` into your repository and locally merge all changes
    * if it runs locally for you: create a pull request asking to merge your changes
    * one of the admins reviews your changes 
    * if there are no conflicts or issues, your changes get merged into the  `development` branch
    * if everything works, it gets pulled into `main`

## Resources to learn Github
* [Introduction to Git and Github by W3](https://www.w3schools.com/git/git_intro.asp?remote=github)

## Useful links
* [Dataset overview](https://sites.google.com/view/computational-behavior/our-datasets/calms21-dataset)