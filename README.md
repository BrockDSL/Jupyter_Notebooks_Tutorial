![DSL Logo][dsllogo]  ![Jupyter Logo][jupyterlogo]


# Jupyter Notebooks

Jupyter notebooks are incredibly powerful tools for both writing and sharing code.  They combine the functionality of an integrated development environment with the aesthetic feel and functionality of a markdown enabled notepad!  This tool makes an excellent environment for working with code but is also an excellent tool for presenting your findings in a procedural (and repeatable!) manner.

The purpose of this tutorial is to demonstrate each of the functions included in Jupyter and to give you a chance to give them a try.


## Setup
This tutorial will focus on using Jupyter online via the Syzygy platform.  Unfortunately at present Jupyter Notebooks online require a brock login (with e-mail) to access.  This does not mean that you can't access it locally on your own machine or using a guest login on a campus computer.  For more information on getting and using Jupyter Notebooks without a brock login feel free to stop by the Digital Scholarship Lab in the Rankin Family Pavilion, or e-mail us at DSL@Brocku.ca.

1. Navigate to https://brocku.syzygy.ca
2. Click the red login house at the bottom of the screen and login using your brock login on the next page


## Navigating Jupyter - File Directory
Welcome to Jupyter Notebooks!  When you first login you will be taken to your file directory.  This is the storage space for any and all files that you will interact with using your code.  To add new files to your directory click the "Upload" button on the right.  Once you have your files to work with, make a new notebook using the "New" drop down menu and picking the programming language that you want to work in.

![Jupyter Start Page][jupyter1]

Once you have created your new Notebook an .ipynb file will be created in your file directory and your new Notebook will automatically open for you in a new tab (or window depending on your settings).

## Navigating Jupyter - The Notebook

Your new notebook is now ready to go!  Let's take a look at the different aspects of a Notebook!

### Cells

Notebooks are made up of two main types of cells: Code and Markdown.  

Code cells are where you type your code and run it.  By default new cells that you make using the "+" button will be code cells.  To change a cell to a different type, select the cell and use the dropdown menu to select the new cell type.  The programming language recognized by code cells is the language you chose when creting the new notebook. Once you have typed some code into a code cell you can run that code either by clicking the "Run" button at the top of the screen while that cell is selected or by pressing CTRL+ENTER on the keyboard.

![Notebook Layout][jupyter2]

### Saving, Naming, and Checkpoints

To change the name of your Notebook, click on the current name at the top of the page ("Untitled" is the default name) and type in your new name.  Beside the name of your notebook you will see a status telling you when the last checkpoint was created as well as if there are unsaved changes.  Jupyter Notebooks will automatically save your work to your .ipynb file every two minutes or whenever the notebook is closed (there is no "do you want to save your changes?" dialog.  It just does it).  In addition to the autosave feature Jupyter allows you to manually save the current state of the notebook into what is called a checkpoint.  By clicking on the save button on the top menu your .ipynb file will be saved as normal but a second file in a hidden folder called .ipynb_checkpoints will also be created.  You can only ever have one checkpoint at a time for each notebook and making a new checkpoint overwrites the old one.  To revert to your checkpoint go to File->Revert To Checkpoit->Click on your checkpoint.

![Checkpoints and Status][jupyter3]

### Downloading Your Notebook

Once you are happy with your notebook you can download it in a great deal of forms from Syzygy.  If you want to take what you are working on and work on it off campus on your own instance of jupyter (perhaps through an Anaconda launcher) then you can download the .ipynb file.  If you have come up with a great bit of Python code that you want to start using but don't want to copy each bit over individually you can save the notebook as a .py file that converts all of the markdown cells into comments in a Python script.  If you want a nice static view of your notebook for your website you can download a .html file.  There are a large number of ways to download your work so try them out and see what best suits your needs!

![Jupyter Notebook Download Options][jupyter4]

[dsllogo]: dsl_logo.png
[jupyterlogo]: jupyter_logo.jpg
[jupyter1]: Jupytermain.png
[jupyter2]: notebooklayout.png
[jupyter3]: Jupyterchecks.png
[jupyter4]: Jupyterdownload.png
