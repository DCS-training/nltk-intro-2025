# Introduction to Text Analysis with NLTK
Analyzing unstructured data (text) with Python's Natural Language Toolkit, along with a little RegEx, Pandas (for tabular data), and Altair (for bar charts)

Material created by Lucy Havens and updated by Xandra Dave Cochran (2025) and Joy Lan (2026)for the [Centre for Data, Culture, & Society](http://cdcs.ed.ac.uk)

Folder contents:
* Slides: PDF documents
* Notebooks: Jupyter Notebooks demoing content from the slides and completing the assignments
* Assignments: PDF document linking to external resources

The material in this repo is licensed under [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

## How to use the Jupyter Notebooks

### 1.  Run the notebook in Noteable

If you are part of the University of Edinburgh you can use [Noteable](https://noteable.edina.ac.uk/) the cloud-based computational notebook system that works on your browser from any device.

Getting started:

#### Start Noteable
1.  Open the following link in a new tab:  [https://noteable.edina.ac.uk/login](https://noteable.edina.ac.uk/login)
2.  Login with your EASE credentials
3.  Under 'Standard Notebook' click 'Start'
   
#### Import the Repository
1.  From the Noteable home page, click on the 'Git' button in the top bar
2.  Now click 'Cone a Repository' button to copy the content of this repository
3.  Enter the link to this repository [https://github.com/DCS-training/nltk-intro-2025](https://github.com/DCS-training/nltk-intro-2025)
4.  leave 'Include submodules' checked and 'Download the repository' unchecked
5.  Click on Clone
6.  On the left-hand side you can now see a folder named as this repo containing all the material
7.  Click on it, then on 'Notebooks', and then select the.ipynb file you want to use 


### 2. Run the notebooks via GoogleColab

Open Google Colab: [https://colab.research.google.com](https://colab.research.google.com)
If you are not already logged you will be prompted to log-in via Gmail

#### Upload the Notebook to Google Colab
1. Go to the GitHub header and copy and paste the link to this repo and select the notebook you want to use and press enter

### Using the Notebook
The Notebook contains paragraphs of explanatory text interspersed with grey cells containing code blocks. To run a code block and see the result:

1.  Place your cursor within the cell
2.  Click the 'Run' button on the top menu
4.  The results of running this code will appear below
5.  If the results don't appear immediately, check the icon in the browser tab. AN egg-timer icon indicates it is processing the code.
6.  It is best to follow the Notebook from top to bottom as some code blocks will depend on results from previous cells
7.  You can edit code blocks yourself and run them to see the results of your changes
### Clearing the cells
To clear the results and run the code again you can use the 'Cell' menu on the top menu bar

1.  To clear the results of the current cell:  **Cell > Current Outputs > Clear**
2.  To clear the results of all cells:  **Cell > All Output > Clear**



### 3.Installing Python via Anaconda

[Python][python] is great for general-purpose programming and is a popular language for scientific computing as well. Installing all of the packages required for this lessons individually can be a bit difficult, however, so we recommend the all-in-one installer [Anaconda][anaconda].

Regardless of how you choose to install it, please make sure you install Python version 3.x (preferably Python 3.11 or higher). 

#### Windows - [Video tutorial][video-windows]

1. Open [anaconda.com/download][anaconda-dl] with your web browser.

2. Download the Python 3 installer for Windows.

3. Double-click the executable and install Python 3 using _MOST_ of the default settings. The only exception is to check the **Make Anaconda the default Python** option.

#### macOS - [Video tutorial][video-mac]

1. Open [anaconda.com/download][anaconda-dl] with your web browser.

2. Download the Python 3 installer for macOS.

3. Install Python 3 using all of the defaults for installation.

#### Starting Python
To start Jupyter Notebook Open the Anaconda Navigator and Launch Jupyter Notebook.

If you wish, you can create a Python virtual environment and install all dependencies for the course by navigating to the course folder in the terminal and running `sh setup.sh`.

#### Upload the Notebook
1. Download the notebook on your machine
2. Go to Upload
3. Navigate to where you have downloaded your file
4. Select Upload again
5. Double-click on the uploaded file



[anaconda]: https://www.anaconda.com/distribution
[anaconda-dl]: https://www.anaconda.com/download/
[python]: https://python.org
[jupyter]: https://jupyter.org/index.html
[jupyter-install]: https://jupyter.org/install.html
[video-mac]: https://www.youtube.com/watch?v=TcSAln46u9U
[video-windows]: https://www.youtube.com/watch?v=xxQ0mzZ8UvA
