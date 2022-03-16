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
2. Run tensorboard --logdir=research_env/logs/fit




