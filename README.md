# Rasilab-Spelman Comp Bio internship 2023
- Katharine Chen
- Grace Quarterman
- Christine Bynum

## Useful resources

### Markdown

- ["What is markdown"](https://www.markdownguide.org/getting-started/#what-is-markdown) and ["Why use markdown"](https://www.markdownguide.org/getting-started/#why-use-markdown) sections of this [guide](https://www.markdownguide.org/getting-started/)
- Markdown is typically used in text editors (like VSCode)
- Note that this document is written in markdown, which automatically renders into the denoted formatting when pushed/opened on [github](https://github.com/kychen37/rasilab_spelman_2023/blob/main/README.md)

### Command line & terminal

- https://www.technigo.io/explained/what-is-the-terminal
- The terminal (mac/linux) or command prompt (windows) is a way to execute simple commands directly on the files in your computer

### Github

- Make an account on github and verify your email address
- Install git to your laptops by following [this](https://www.atlassian.com/git/tutorials/install-git) site
- Clone our group's remote repository to your local computer by opening the terminal and executing the following: ```git clone https://github.com/kychen37/rasilab_spelman_2023.git```
  - Since this repo was made in my account (kychen37), I needed to added gquarter and christinebynum users to the repo on github under [Settings](https://github.com/kychen37/rasilab_spelman_2023/settings) before they had permission to push/pull
- Each user needs to then generate a personal access token:
  - Go to your user settings -> Developer settings -> Personal access tokens -> Tokens (classic) -> Generate new token (classic)
  - Under Note, name the token something descriptive and check 'repo'
  - Press Generate token, copy the entire token to a different location like a notepad
- Follow the top comment on https://stackoverflow.com/questions/46645843/where-to-store-my-git-personal-access-token for saving the personal access token to the git credential helper so you don't have to keep copy/pasting it each time you push
  - ```git config --global user.name "Katharine Chen"```
  - ```git config --global user.email kychen37@uw.edu```
  - ```git config --global credential.helper manager-core```
- The default behavior of git is to rebase, but if you don't set it explicitly it will give you an error each time you try to pull, so run:
  - ```git config --global pull.rebase true```
- Now you can run the usual git workflow:
  - ```git add ``` filename of the file you editted
  - ```git commit -m "descriptive message about what was editted```
  - ```git push origin main```
- You should also do ```git pull origin main``` to get any changes to the remote repo that other users may have pushed

### R programming

#### Installing R
- https://rstudio-education.github.io/hopr/starting.html

### VSCode
- A very useful text editing and coding application
- Various extensions make coding/writing in VSCode much easier:
  - Go to Extensions on the side panel and install the extension called Jupyter

#### Setting up Jupyter kernels in VSCode
