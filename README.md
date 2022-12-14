# **Welcome to Python**
___
---

# Step 1

* ## Make a Github account
  * This is a tool for storing and collaborating on code
  * its also used together with Git for version control (i will explain all of this)
  * you can create an account [here](https://github.com/signup?source=login)

* ## Install Python
  * Download and install from [Python.org](https://www.python.org/downloads/)
  * this will also install Pip which we will use to install packages into our python projects
  * **Make sure to click the box that says "Add Python 3.x to PATH"**

* ## Install Vscode
  * This will be your main text editor/IDE 
  * Download and install Vscode from [VisualStudioCode](https://code.visualstudio.com/?wt.mc_id=DX_841432)
  * Sign into your github account
  * Install the extensions we will need for Python into vscode from [here](https://marketplace.visualstudio.com/items?itemName=donjayamanne.python-extension-pack)

* ## Install Git
  * Download and install Git from [Git Website](https://git-scm.com/)
  * select Vscode as your default text editor when asked


* You will want to make a folder in your Documents folder called "dev" for all your project folders
* you will also need a good monospace font for coding, i recommend [Monoid](https://larsenwork.com/monoid/) or [FiraCode](https://github.com/tonsky/FiraCode/releases/download/6.2/Fira_Code_v6.2.zip) (i will show you how to install this into Vscode)
---

# Step 2
## Setting up virtual environments
#### Virtual environments are used to prevent packages you are installing into your python project from installing onto your whole system
#### **_Any code `highlighted in grey` is code that should be run in your Terminal/Powershell_**

* ## For Mac/Linux users
  * Install virtualenv `python3 -m pip install --user virtualenv`
  * From inside your project folder run, `python3 -m venv env` "env" being the name u want to use for this environment
  * To activate this environment run, `source env/bin/activate`


* ## For Windows users
  * Install virtualenv `py -m pip install --user virtualenv`
  * From inside your project folder run, `py -m venv env` "env" being the name u want to use for this environment
  * To activate this environment run, `.\env\Scripts\activate`

* to exit and environment use `deactivate`
* while inside an environment you can install packages with Pip and they will only install into that project
* you can save a list of your installed packages with `pip freeze > requirements.txt`
* you can now automatically install all the necessary packages (dependencies) with `pip install -r requirements.txt`
* Using a requirements.txt file means that you no longer have to store all these packages inside your repo and anyone who wants to use your code can install them into their own environment
---

# Step 3
## this will be needed once we start to use more complex tools
* ## For Mac users
  * Install Homebrew by pasting this command into your terminal
  * ```/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"``` 
  * you can now use `brew install [package name]` to install things via your cli
  
* ## For Windows users
  * Install Chocolatey by pasting this command into Powershell (run as administrator)
  * ```Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))```
  * you can now use `choco install [package name]` to install things via your cli
---

# Some Documentation that you might want to read

* [Python Docs](https://www.python.org/doc/) 
* [Learn X in Y minutes](https://learnxinyminutes.com/docs/python/)
* [Python Cheatsheet](https://www.pythoncheatsheet.org/cheatsheet/basics)
* [Python Environments Help](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#:~:text=To%20create%20a%20virtual%20environment,virtualenv%20in%20the%20below%20commands.&text=The%20second%20argument%20is%20the,project%20and%20call%20it%20env%20.)

# Some Youtube videos to get u started
* [Mosh Hamedani's Python Course](https://www.youtube.com/watch?v=kqtD5dpn9C8)
* [Fireship's Github Tutorial](https://www.youtube.com/watch?v=HkdAHXoRtos)
