##PIP

PIP is the preferred installer program which is a package manager for Python packages.
Normally pip is already installed  with Python 3.4 and above.
Here are few commands(for cmd) to get started with PIP
1.  To check if pip is installed

      ```python -m ensurepip –default-pip```
2.	To see default version
      
      ```pip -V```  
      or
      
      ```pip –version```
3.	To upgrade pip

      ```python -m pip install --upgrade pip```
4.	To install python lib

      ```python -m pip install lib_name```
      
      ```example: python -m pip install numpy```
5.	To upgrade any package

     ```python -m pip install --upgrade package_name```
     
     ```python -m pip install --upgrade package_name==2.0.1```	#for specific purpose

##CONDA

CONDA is the package manager of Anaconda which handle library dependencies outside of the Python packages as well as the Python packages themselves.
1.	To see default version

      ```conda update conda```
2.	To install package

      ```conda install PACKAGENAME```
3.	To update package

      ```conda update PACKAGENAME```

Conda cheat-sheet link:- https://conda.io/docs/_downloads/conda-cheatsheet.pdf

CONDA-FORGE  is a github organization containing repositories of conda recipes. It is an additional channel from which packages may be installed, which can be used to install non-mainstream packages also.
To configure conda-forge channel

      ```conda config --add channels conda-forge```
      
After configuring conda-forge channel whenever you install any package from command conda install <package_name> it will be installed from conda-forge channel.

There are three main reasons to use the conda-forge channel instead of the default channel maintained by Anaconda:
1.	Packages on conda-forge may be more up-to-date than those on the defaults channel
2.	There are packages on the conda-forge channel that aren't available from defaults
3.	If you are installing a package that requires a compiled library (e.g., a C extension or a wrapper around a C library), it may reduce the chance of incompatibilities if you install all of the packages in an environment from a single channel due to binary compatibility of the base C library (but this advice may be out of date/change in the future).


#jupyter notebook

The Jupyter Notebook is an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text. Uses include: data cleaning and transformation, numerical simulation, statistical modeling, data visualization, machine learning, and much more.
1.	To launch jupyter notebook using cmd

     ``` jupyter notebook```
      
2.	Creating new python 3 file

      ```Click New->Python 3```
      
3.  Types of cell in notebook

      ..*	Code – This is self-explanatory; it is where you type your code

      ..*	Markdown – This is where you type your text. You can add your conclusions after running a code, add comments, etc.

      ..*	Raw NBConvert – It’s a command line tool to convert your notebook into another format (like HTML)

      ..*	Heading – This is where you add Headings to separate sections and make your notebook look tidy and neat. This has now been          converted into the Markdown option itself. Add a ‘##’ to ensure that whatever you type after that will be taken as a heading


4.  Few shortcuts for notebook

      ..*	Toggle between edit and command mode with Esc and Enter, respectively.

      ..*	Once in command mode:

      ..*	Scroll up and down your cells with your Up and Down keys.

      ..*	Press A or B to insert a new cell above or below the active cell.

      ..*	M will transform the active cell to a Markdown cell.

      ..*	Y will set the active cell to a code cell.

      ..*	D + D (D twice) will delete the active cell.

      ..*	Z will undo cell deletion.

      ..*	Hold Shift and press Up or Down to select multiple cells at once.

      ..*	With multple cells selected, Shift + M will merge your selection.

      ..*	Ctrl + Shift + -, in edit mode, will split the active cell at the cursor.

      ..*	You can also click and Shift + Click in the margin to the left of your cells to select them.


5.  To save notebook
      ```File->Download As-> choose the format in which you want to save.```
