# ml-tutorial
Repo containing scripts and dataset for a machine learning tutorial. This read-me contains:
+ Instructions of how to set up a Python development environment from scratch.
+ An outline of the contents of the repository.

## Getting set up
In order to complete access this code and complete these tutorials you will need to install several bits of software:
+ Git
+ Python
+ conda

### Installing git
In order to interact with this code you will need and installation of git. I would recommend also creating a github account github account, though this is optional.

Git can be installed from [here](https://git-scm.com/downloads).

You can create a GitHub account [here](https://github.com/signup)

### Installing Python and conda
Python is available from [here](https://www.python.org/downloads/), version 3.13 is recommended.

Anaconda is available from [here](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html)

### Setting up an environment
Once all of the above is installed open a command line (For example [PowerShell](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file) for Windows, or  [Terminal](https://support.apple.com/en-gb/guide/terminal/apdb66b5242-0d18-49fc-9c47-a2498b7c91d5/mac) on Mac.)

1. Navigate to a suitable folder for working in and run the command  

   ```git clone https://github.com/JoeThorpe94/ml-tutorial.git```  

    This will create a copy of the folder structure and content stored in this repository.  

2. Change directory into the new ```ml-tutorial``` directory. There should be an ```environment.yml``` file in this directory.

3. Run the command ```conda env create -f environment.yml```. This will create a new environment in conda that will let you run any of the code we right during the tutorial.

4. Run the command ```conda activate mlenv```. This will activate the environment we have just created.

5. To test the environment run the command ```jupyter lab```. This should open a browser window to the homepage of your new jupyterlab
