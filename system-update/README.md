# bear-update
This script automates the process of updating your Linux system. It updates the package list, upgrades all packages to their newest versions, and cleans up unnecessary files. If a reboot is required after the updates, it notifies the user.

## Setting up

Assuming that you`ve cloned this repo: 

1. Run the following command to make sure that user can execute script:
     ```sh
     sudo chmod u+x bear-update
     ```

2. Place script in local binary directory:
     ```sh
     sudo cp bear-update /usr/local/bin/
     ```

3. You can now run the script at any time by typing:
     ```sh
     bear-update
     ```


