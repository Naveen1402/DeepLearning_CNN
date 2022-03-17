# DeepLearning
DeepLearning

Added env/ at the bottom of gitignore file to ignore the env settings 

#### Setup the Github repo to local system
create folder to save the github  repo, open terminal and run below command

cd /Users/mac/Desktop/Ineuron/CNN/DogCatClassification/CNN_CLassifier
git clone https://github.com/Naveen1402/DeepLearning_CNN.git

open directory to code editor like vs code and pycharm and create the environment

conda create --prefix ./env python=3.7 -y && conda activate ./env

#### Also Keep on adding the library inside the requirement.txt files 

pip install -r requirements.txt

to start jupyter notebook jupyter-notebook

Keep commit and push changes to the github using pycharm and vscode git commit options

do not puch the data to git as its huge, to avoid that add datafile_name.zip into gitignore file


#### to view the data log into tensor board  
1. open new terminal conda activate ./env
2. Run tensorboard --logdir=research_env/logs/fit/. 
OR use %load_ext tensorboard in the jupyter notebook and type %tensorboard --logdir research_env/logs/fit/


# MLFLOW: MLOPS
unde our root directory we have src and under src we have lot of other folder
1. Get Data : data gathering
2. BASE model archeive : model preparation
3. Prepare callbacks: tensor board, check points

All above 3 connect and create train and there we also have utils folder which is outside of train. and generally handle all utility files.

4. config folder : config.yaml, secret keys: token id, keys, password, parameter.yaml : hyperparameter like epochs, weight bias etc, setup.py file.

5. ML Project files : decide how above all are connect altogether
6. conda.yaml : conda settings and environement
7. requirement.txt : all the required library.




