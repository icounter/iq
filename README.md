# IQ
Mac Installation Guide to run IQ-ipython-notebook

### System Requirements
Make sure your system meets these requirements:
  - Operating system: MacOS 10.7 10.8 10.9 10.10 (it has been tested successfully on these)
  - RAM: 2GB.
  - Disk space: 2GB

### Step 1: Install Command Line Tools
  - Open terminal, type “xcode-select --install” in terminal (without quotes)
  - A pop-up windows will appear asking you about install tools, choose install tools, wait install to finish
  
### Step 2: Install Homebrew

  ```
  ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
  brew tap samueljohn/python
  brew tap homebrew/science
  ```

### Step 3: Install Python and its modules
    
  ```
  brew install python
  
  pip install numpy
  pip install scipy
  pip install pandas
  ```

### Step 4: Install IPython notebook

  ```
  pip install ipython
  pip install pyzmq
  pip install jinja2
  pip install tornado
  pip install jsonschema
  ```
     
### Step 5: Download repository 

  Via the button on the right and unzip the zip file.

### Step 6: Open ipython notebook

  ```
  ipython notebook
  ```
    
  Then change directory to `iq/<some_number>` and click on `iq_<some_date>.ipynb` to start it.
