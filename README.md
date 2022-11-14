# :book: Clone-me

The purpose of this repository is to practice the `git clone` command.

## :paw_prints: Steps

1. Go to the [asgdevops/clone-me](https://github.com/asgdevops/clone-me) [github](https://github.com) repository.

2. Take the git repository name from the SSH code `git@github.com:asgdevops/clone-me.git` tab.

3. In your local machine open a new ssh terminal and go to the directory where you would like to drop the cloned repository.


    ```bash
    cd $HOME/portfolio
    ```

4. Issue the `git clone` repository command.

    ```bash
    git clone git@github.com:asgdevops/clone-me.git
    ```

5. Get in the cloned directory.

    ```bash
    cd clone-me
    ```

6. Verify the cloned directory is configured properly.

    ```bash
    git remote -v
    ```
