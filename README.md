<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![forthebadge](https://forthebadge.com/images/badges/built-by-developers.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)

# AmongCode

A collection of simple programs and projects to enhance your skills.

If you are new to Github and open source then, visit [here.](https://towardsdatascience.com/getting-started-with-git-and-github-6fcd0f2d4ac6)

You have to solve the issue in 15 days from the day issue is assigned to you.

## Steps To Follow

- Select an issue and ask to be *assigned* to it.
- Check existing programs [here.](https://github.com/VIPverma01/AmongCode/tree/master/Programs)
- **Star** the repository.
- On the [GitHub page for this repository](https://github.com/VIPverma01/AmongCode), click on the Button "**Fork**".
   ![fork image](https://help.github.com/assets/images/help/repository/fork_button.jpg)
- Create clone ***your forked repository*** on your local machine.
   ![code ui](https://docs.github.com/assets/images/help/repository/code-button.png)

    For example, run this command inside your terminal:

    ```bash
    git clone https://github.com/<your-github-username>/AmongCode.git
    ```

    **Replace \<your-github-username\>!**

    Learn more about [forking](https://help.github.com/en/github/getting-started-with-github/fork-a-repo) and [cloning a repo](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository).
- Before you make any changes, [keep your fork in sync](https://www.freecodecamp.org/news/how-to-sync-your-fork-with-the-original-git-repository/) to avoid merge conflicts:

    ```bash
    git remote add upstream https://github.com/VIPverma01/AmongCode.git
    git fetch upstream
    git pull upstream master
    git push
    ```

- If you run into a **merge conflict**, you have to resolve the conflict. There are a lot of guides online, or you can try this one by [opensource.com](https://opensource.com/article/20/4/git-merge-conflict).

- Checkout to development branch (*name your branch according to the issue name*).

    ```basg
    git checkout -b <branch-name>
    ```

- Create a folder in [Programs directory](https://github.com/chavarera/python-mini-projects/tree/master/projects) according to issue name and add your github username in brackets eg. Program_Name(Username).
- Write your code and add to the respective folder in the Programs directory, locally.
- Don't forget to add a `README.md` in your folder, according to the [README_TEMPLATE.](https://github.com/VIPverma01/AmongCode/blob/master/README_TEMPLATE.md)
- Add the changes with `git add`, `git commit` ([write a good commit message](https://chris.beams.io/posts/git-commit/), if possible):

    ```bash
    git add -A
    git commit -m "<your message>"
    ```

- Push the code *to your repository*.

    ```bash
    git push origin <branch-name>
    ```

- Go to the GitHub page of _your fork_, and **make a pull request**:

    ![pull request image](https://help.github.com/assets/images/help/pull_requests/choose-base-and-compare-branches.png)

    Read more about pull requests on the [GitHub help pages](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).
- Now wait, until one of us *reviews your Pull Request*! If there are any conflicts, you will get a notification.
