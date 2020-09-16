# Git Hooks Test

Make sure to configure the Git hooks directory at least locally in this repository by running one of the following commands.

    git config core.hooksPath .githooks
    git config --local core.hooksPath .githooks

Alternatively, configure it for all projects at once by using the `--global` flag.

    git config --global core.hooksPath .githooks

Try to make some commits to see the given hooks in action.