# BizAnalytics-ML-Assessment-Solution
Successfully established a machine learning model which is able to detect whether a particular email belongs to spam or ham catogory.

## Setup Instructions

### Global setup:
  Download and install Git
  git config --global user.email EMAIL_ADDRESS
  
### Next steps:
  mkdir email_spam_classification
  cd email_spam_classification
  git init
  touch README
  git add README
  git commit -m 'first commit'
  git remote add origin git@github.com:SayamAlt/BizAnalytics-ML-Assessment-Solution.git
  git push origin master
  
You may also want to track the master branch for easy pull/push
<ul>
  <li>git config branch.master.merge refs/heads/master</li>
  <li>git config branch.master.remote origin</li>
</ul>

## Execution Intructions

You can clone this repository in your local system by using the following command.
git clone https://github.com/SayamAlt/BizAnalytics-ML-Assessment-Solution

Once the repository is installed, you can run the Jupyter Notebook through the Anaconda3 Jupyter Notebook Environment. 

There are several libraries which need to be installed for successful execution of this project that are given below. 

<table>
  <tr>
    <th>Library</th>
    <th>Installation Command</th>
  </tr>
  <tr>
    <td>Numpy</td>
    <td>conda install -c conda-forge numpy</td>
  </tr>
  <tr>
    <td>Sklearn</td>
    <td>conda install -c conda-forge sklearn</td>
  </tr>
  <tr>
    <td>URL Extract</td>
    <td>pip install urlextract</td>
  </tr>
  <tr>
    <td>Scipy</td>
    <td>conda install -c anaconda scipy</td>
  </tr>
  <tr>
    <td>Imbalanced Learn</td>
    <td>conda install -c conda-forge imblearn</td>
  </tr>
  <tr>
    <td>XG Boost</td>
    <td>conda install -c conda-forge xgboost</td>
  </tr>
  <tr>
    <td>Collections</td>
    <td>pip install collections</td>
  </tr>
  <tr>
    <td>HTML</td>
    <td>conda install -c auto html</td>
  </tr>
  <tr>
    <td>NLTK</td>
    <td>conda install -c anaconda nltk</td>
  </tr>
</table>

You can install all these required libraries for this project by executing the above mentioned commands on the Anaconda Command Prompt.

## Miscellaneous supporting information

<p>For creating a virtual environment for this project, you can execute the following command:</p>

````
python -m venv PROJECT PATH 
````

<p>To have a look at all the files present in the project directory, you can use the following command:</p>

````
pip list
````

<p>For storing all the information related to the installed Python's libraries and others including their names and versions, you can execute the command given below:</p>

````
pip freeze > requirement.txt
````

<p>For deactivating the virtual environment, you can run the following the command:</p>

````
deactivate
````

<p>For installing Jupyter notebook through the Anaconda command prompt, you can execute the following command:</p>

````
conda install jupyter
````

<p>For running Jupyter Notebook through the Anaconda command prompt, you can type the following command:</p>

````
jupyter notebook
````

<p>In your base environment you need to install nb_conda_kernels (just one time), which automatically creates a new kernel for each virtual environment you create, provided you’ve installed jupyter in it.</p>

````
conda install -n base nb_conda_kernels
````
