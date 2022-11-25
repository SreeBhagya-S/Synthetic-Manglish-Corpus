#Synthetic Manglish Corpus of Customer Reviews from Amazon
#How to save large files in git
Follow the commands 
cd {filepath} eg:/home/mca5/anaconda3/lib/python3.7
sudo apt update
sudo apt install git
sudo apt install make libssl-dev libghc-zlib-dev libcurl4-gnutls-dev libexpat1-dev gettext unzip
curl -s https://packagecloud.io/install/repositories/github/git-lfs/script.deb.sh | sudo bash
sudo apt-get install git-lfs
git lfs install
git clone {gitrepo_url} eg: https://github.com/SreeBhagya-S/Datasets.git
git lfs track
git add {filename} eg:amazon_fullReviews.csv # COPY file amazon_fullReviews.csv in this folder
git add {filename} eg:amazon_fullReviews.csv
git commit -m "Add csv file"
git config --global push.default simple
git push

To Create Personal Access Token on GitHub
From your GitHub account, go to Settings => Developer Settings => Personal Access Token => Generate New Token (Give your password) => Fillup the form => 
click Generate token => Copy the generated Token, it will be something like ghp_sFhFsSHhTzMDreGRLjmks4Tzuzgthdvfsrta.
use this token as the password in the git push command
