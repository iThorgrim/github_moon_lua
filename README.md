# GitHub Moon to Lua Action 🚀

This GitHub Action converts `.moon` files to `.lua` files and creates a pull request with the changes.

## How It Works
1. The action checks for any `.moon` files in the repository.
2. If `.moon` files are found, it installs the necessary dependencies.
3. It then compiles the `.moon` files to `.lua` files and removes the original `.moon` files.
4. A new branch is created, the changes are committed, and a pull request is opened.
5. The pull request is merged automatically.
