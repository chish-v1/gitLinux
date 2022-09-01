Tutorial to install git on linux ubuntu. 
Instructions from **The Odin Project**
1. First update the system using the following commands
    - sudo apt update
    - sudo apt upgrade

2. Install git using the following command 
    - sudo apt upgrade

3. Verify git version using the following command
    - git --version

4. Configure git and github following the following commands. You are letting git know who you are.
    - git config --global user.name "Your Name"
    - git config --global user.email "Your email address"

5. Github default branch no longer called master (apparently invokes slavery connotations/vibes) so change it to main
    - git config --global init.defaultBranch main

6. Enable colorful output in git
    - git config --global color.ui auto

7. Verify your name and email address using the following commands
    - git config --get user.name
    - git config --get user.email