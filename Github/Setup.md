# Github

### How to setup Github CLI

This is useful for when your Git client such as VS Code, GitKraken, Github Desktop, etc... gives you errors on logging in or merging or anything else.

==================

Windows
---------------------

1. Head to the [Github CLI](https://cli.github.com/) source page which includes a button to download the Installation Wizard tool

2. Open the Installation Wizard and install into the appropriate folder (usually its the `C:\Program Files\GitHub CLI\` folder)

3. Verify that it works on your machine by running `gh`. Then if its working, run `gh auth login` to login into your account for easier utility when cloming repositories.


Mac OS
---------------------

1. Copy and run `brew install gh` in your terminal

2. Follow the onscreen instructions to login into your GH account

This should help resolve any SSO issues when cloning
