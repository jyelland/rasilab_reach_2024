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
- Install git to you laptops by following [this](https://www.atlassian.com/git/tutorials/install-git) site
- Clone our group's remote repository to your local computer by opening the terminal and executing the following: ```git clone https://github.com/kychen37/rasilab_spelman_2023.git```
  - Since this repo was made in my account (kychen37), I needed to added gquarter and christinebynum users to the repo on github under [Settings](https://github.com/kychen37/rasilab_spelman_2023/settings)
- Each user needs to then generate a personal access token:
  - Go to you user settings
  - Go to Developer settings
  - Personal access tokens -> Tokens (classic) -> Generate new token (classic)
  - Under Note, name the token something descriptive and check 'repo'
  - Press Generate token, copy the entire token to a different location
- Each user should now be able to use git/github
- Usual git workflow:
  - ```git add filename```
  - ```git commit -m "descriptive message about what was editted```
  - ```git push origin main```
- You should also do ```git pull origin main``` to get any changes to the remote repo that other users have pushed
