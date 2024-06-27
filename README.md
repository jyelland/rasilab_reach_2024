# REACH internship in the Subramaniam Lab (Summer 2024)

## Students

- Kaleaha Davis
- Kentavious Veal

## Mentor

- Jamie Yelland

## PI

- Rasi Subramaniam's lab at Fred Hutch Cancer Center

# Documentation
[Last year's documentation is here.](https://github.com/kychen37/rasilab_spelman_2023/blob/main/notes/gq_and_cb_methodology.md)

# Project Workflow
- [Last year's workflow is here.](https://github.com/kychen37/rasilab_spelman_2023/blob/main/project_workflow.md)

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
- Make a git/ folder on your computer, somewhere you can easily find it, with the command ```mkdir git```.
- In your git/ folder, clone this repository to your local computer with the following command: ```git clone git@github.com:kychen37/rasilab_reach_2023```
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

### Programming in python
#### Installing miniconda: 
- [What is miniconda?](https://docs.conda.io/en/latest/miniconda.html)
- Mac: https://docs.conda.io/projects/conda/en/latest/user-guide/install/macos.html
  - Follow the link "Miniconda installer for macOS."
  - Click on the link "Miniconda3 macOS Intel x86 64-bit bash", which will download the installation to your Downloads folder
  - Open terminal and navigate to your Downloads folder (hint ```cd```)
  - Run: ```sh Miniconda3-latest-MacOSX-x86_64.sh``` and follow prompts in terminal (say 'yes' to 'conda init' question)
  - After installation is done, close and reopen terminal
  - Run: ```conda list```, which should show a list of packages if the installation was successful (will probably say something like ```conda not found``` if it was unsuccessful)
- Windows: https://docs.conda.io/projects/conda/en/latest/user-guide/install/windows.html
  - Open the executable and follow instructions
- After you've finished installing miniconda, install ```pandas``` by typing: ```conda install pandas``` on the command line
- If you need any more packages down the road, you would run: ```conda install packagename``` on the command line
  - e.g. numpy and matplotlib are common python packages, to install them you would run: ```conda install numpy```, ```conda install matplotlib```

### VSCode
- A very useful text editing and coding application.
- Various extensions make coding/writing in VSCode much easier.

#### Setting up Jupyter kernels in VSCode
- In VSCode, find the Extensions panel
- Search for the extension called Jupyter and download it
- Open a python interactive notebook (called a Jupyter notebook)
  - For Mac: press CMD+SHIFT+P to open the drop-down menu -> click Create Jupyter notebook
- In top right corner: select "Select Kernel" -> "Python environments" -> choose the "base (miniconda3/bin/python)" 
- Start coding!
  - The first time you run a code chunk, VSCode may ask you to download some needed additional extensions, download those

# Link to Notes/ Checklist
