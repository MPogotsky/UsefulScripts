# bear-git-config
Git configuration and set of aliases for git terminal.

## Setting up

1. Open your global `.gitconfig` file in a text editor:

```sh
nano ~/.gitconfig
```

2. Copy and paste the configuration from [bear-git-config.txt](./bear-git-config.txt) your `.gitconfig` file

3. Replace **\<name\>** and **\<email\>** with your actual name and email address.

4. Save and close the file

## Git Aliases overview

Below are the aliases defined in the provided configuration:

1. **`br`**: Shortcut for `branch`
   - Usage: `git br`
   - Description: Lists all branches in the repository.

2. **`co`**: Shortcut for `checkout`
   - Usage: `git co <branch>`
   - Description: Checks out a specified branch.

3. **`st`**: Shortcut for `status`
   - Usage: `git st`
   - Description: Shows the working tree status.

4. **`lg`**: Logs with a simple oneline graph
   - Usage: `git lg`
   - Description: Displays the commit history in a simple oneline format with a graph and decorations.

5. **`lga`**: Logs with a simple oneline graph for all branches
   - Usage: `git lga`
   - Description: Displays the commit history for all branches in a simple oneline format with a graph and decorations.

6. **`lol`**: Pretty log with detailed formatting
   - Usage: `git lol`
   - Description: Shows the commit history with a detailed and colorful graph, including commit hash, decorations, subject, date, and author.
