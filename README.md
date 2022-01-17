# API Mocker
## About Poject
This is an API Mocker for the weather service openweathermap.org. 
## URL for API mocker on EC2 instance
http://3.88.169.107:7878/data/2.5/weather
## Prerequisites
### Procedure
#### 1)Node version manager (nvm) is installed by typing the following at the command line.
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.34.0/install.sh | bash
#### 2)nvm is activated by typing the following at the command line.
 . ~/.nvm/nvm.sh
 #### 3)Use nvm to install the latest version of Node.js by typing the following at the command line.
  nvm install node
#### 4)The apimocker should be installed using the npm.
node -e "console.log('Running Node.js ' + process.version)"
#### 5)git is installed using
 sudo yum install git   
 #### 6)api mocker is installed
  npm install -g apimocker
## Clone the git repository
git clone https://github.com/pkurapaty7/assignment_2.git
## run the APImocker service
 apimocker -c Config.json.
