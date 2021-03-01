# README for developers

We use `venv` to create virtual environments and manage module dependencies in python scripts or Jupyter Notebooks.  
To create a virtual environment execute the command `python3 -m venv <environment name>` in the root directory.  
I typically name my environment `.env` or `venv`, and configure `.gitignore` to ignore both `.env` and `venv` files. This prevents the environment libraries from being uploaded to the repository.  

After the environment is created, run the following commands from your terminal:
1. First, execute the command `source <environment name>/bin/activate` to enter/activate the environment (e.g., `source .env/bin/activate`).
2. Second, execute the command  `pip install -r requirements.txt` in order to install the dependencies. This will probably generate a message that `pip` is out of date. You can either ignore this message, or update `pip` by executing the command `pip install --upgrade pip`.

Other packages can be installed using the `pip install <package>` command. After a new package is installed, remember to add the package to the `requirements.txt` file in order to include the package as part of the project.

You exit the virtual environment with command `deactivate` in the terminal.