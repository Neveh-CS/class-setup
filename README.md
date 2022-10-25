# Welcome to Python
### heres what ya gottta do

* ## Make a github acoount
  * This is a tool for storing and collaborating on code
  * its also used together with Git for version control (i will explain all of this) 

* ## Install Git
  * Download Python from [Git](https://git-scm.com/)


* ## Install Python
  * Download Python from [Python.org](https://www.python.org/downloads/)
  * this will also install Pip which we will use to install packages into our python projects


* ## Install Vscode
  * This will be your main text editor/IDE 
  * Download Vscode from [VisualStudioCode](https://code.visualstudio.com/?wt.mc_id=DX_841432)
  * Install it
  * Sign into your github account
  * Install the extensions we will need for Python into vscode from [here](https://marketplace.visualstudio.com/items?itemName=donjayamanne.python-extension-pack)

## Setting up virtual environments

* ## For Mac/Linux users
  * Install virtualenv `python3 -m pip install --user virtualenv`
  * From inside your project folder run, `python3 -m venv env` "env" being the name u want to use for this environment
  * To activate this environment run, `source env/bin/activate`


* ## For Windows users
  * Install virtualenv `py -m pip install --user virtualenv`
  * From inside your project folder run, `py -m venv env` "env" being the name u want to use for this environment
  * To activate this environment run, `.\env\Scripts\activate`







# Step 2
## this will be needed once we start to use more complex tools
* ## For Mac users
  * Install Homebrew by pasting this command into your terminal
  * ```/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"``` 
  * you can now use `brew install [package name]` to install things via your cli
  
* ## For Windows users
  * Install Chocolatey by pasting this command into Powershell (run as administrator)
  * ```Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))```
  * you can now use `choco install [package name]` to install things via your cli

