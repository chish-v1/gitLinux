Tutorial to install git on linux ubuntu using command line interface. 
Instructions from **The Odin Project** and [Github documentation](https://docs.github.com/en/authentication/connecting-to-github-with-ssh)

Create github account if you don't have one. **Keep the password**

1. First update the system using the following commands
    - ``` sudo apt update ```
    - ``` sudo apt upgrade ```

2. Install git using the following command 
    - ``` sudo apt install git ```

3. Verify git version using the following command
    - ``` git --version ```

4. Configure git and github following the following commands. You are letting git know who you are.
    - ``` git config --global user.name "Your Name" ```
    - ``` git config --global user.email "Your email address" ```

5. Github default branch no longer called master (apparently invokes slavery connotations/vibes) so change it to main
    - ``` git config --global init.defaultBranch main ```

6. Enable colorful output in git
    - ``` git config --global color.ui auto ```

7. Verify your name and email address using the following commands
    - ``` git config --get user.name ```
    - ``` git config --get user.email ```

8. Check if you have an SSH key installed on your machine using the following command, replace ed25519 with rsa if compatible with machine. 
    - ``` ls ~/.ssh/id_ed25519.pub ```

