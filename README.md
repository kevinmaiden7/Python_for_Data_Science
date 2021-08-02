# Analytics and Data Science Specialization (Universidad de Antioquia) - Python Introductory Course

## Environment Configuration

We are going to use the open-source [Anaconda](https://www.anaconda.com/) ecosystem for working with Python and Jupyter Notebook.

Thus, go to [Anaconda Individual Edition page](https://www.anaconda.com/products/individual), and search for the Anaconda Installers section. Once there, choose the installer according to your operating system and machine specifications.

These are the most common selections:

![](images/anaconda_installers.png?raw=true)

Download it and perform the installation process.

## Check your Installation

### Windows

Click Start, search, or select Anaconda Prompt from the menu:

![](images/verify_windows_1.png?raw=true)

Open it, and then type `conda --version`.

You should see the anaconda version installed appear. For example:

![](images/verify_windows_2.png?raw=true)

You can also type `conda info` to see more information, including the Python version installed.

### Mac

![](images/verify_mac_1.png?raw=true)

Open a terminal and type either `conda --version` or `conda info`.

### Linux

After completing the installation, close your terminal and open a new one. Then, you should be able to init Jupyter Notebook by typing `jupyter notebook`. If you see something like this, everything is OK:

![](images/verify_linux_1.png?raw=true)

Otherwise, if you get the message *“jupyter: command not found”*: run `export PATH=$PATH:/root/anaconda3/bin` (you should verify where you actually installed anaconda, however, this is the default path). Then, type again `jupyter notebook`.

If at this point you get the message *"Running as root is not recommended. Use --allow-root to bypass."*, execute `jupyter notebook --allow-root`.

# Acknowledgments

Some material presented here was extracted and adapted from:

- https://github.com/jdariasl/ML_2020
- https://github.com/UDEA-Esp-Analitica-y-Ciencia-de-Datos/EACD-01-FUNDAMENTOS 
- https://github.com/rramosp/20201.xai4eng
