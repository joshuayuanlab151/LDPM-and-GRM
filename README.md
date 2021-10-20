# LDPM-and-GRM
Machine learning models for light distribution pattern  and growth rate predictions  
1. Dependencies
Windows 10
Python 3.8.2
Ipython 7.13.0
Jupyter notebook 6.0.3
numpy 1.18.2
scikit-learn 0.23.1
pandas 1.0.3

2. Installation of all required packages (it takes a couple of minutes for each pachage being installed)
1) download python from https://www.python.org/downloads/ and install the software as instructions;
2) install pip with get-pip.py as descibed in https://pip.pypa.io/en/stable/installing/;
3) install ipython by entering 'pip install ipython' in commamd prompt;
4) install Jupyter notebook by entering 'pip install jupyter' in commamd prompt;
5) install numpy by entering 'pip install numpy' in commamd prompt;
6) install scikit-learn by entering 'pip install scikit-learn' in commamd prompt;
7) install pandas by entering 'pip install pandas' in commamd prompt;

3. Instructions for running codes in notebook
1) open the notebook:
   enter 'jupyter notebook' in command prompt, a web browser will be opened . --> select the directory where 'Codes for LDPM and GRM.ipynb' located.
   --> open the ipynb file by clicking the file name.

2) run codes in cells by clicking 'run' button or 'shift + enter'. Codes need to be run in order. 
   All codes were explained with Markdown inside the notebook.

3) Runtime: it takes ~ 3 min for training on one pixel and about 36 hours for taining on a whole image (720 pixels) during LDPM training;
            For testing pourpose, the code provied only train a model at pixel (0,0), the most upper-left pixel. So it only takes about 3 min.
	    Please see the notebook for details about how to adapt the codes for complete prediction on 720 pixels.  

 
