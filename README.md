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
  pip install matplotlib
  
  pip install pandas
  pip install scikits.statsmodels
  pip install scikit-learn
  ```

### Step 4: Install IPython notebook

  ```
  pip install ipython
  pip install pyzmq
  pip install jinja2
  pip install tornado
  pip install jsonschema
  ```

### Step 5: Install Github

  1. Download and install the latest version of Git.
  2. Tell Git your name so your commits will be properly labeled.
  
     ``` 
     git config --global user.name "YOUR NAME" 
     ```
     
  3. Tell Git the email address that will be associated with your Git commits.
  
     ```
     git config --global user.email "YOUR EMAIL ADDRESS"
     ```
     
### Step 6: Download repository

    ```
    cd ~
    git clone https://github.com/weiyialanchen/iq.git
    ```

### Step 7: Open ipython notebook
    ```
    ipython notebook
    ```
    then change directory to `iq/<some_number>` and click on `iq_<some_date>.ipynb` to start it.
