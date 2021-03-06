# Lightning-Training
Training materials for lightning

## Initial Setup

Install Nodejs
https://nodejs.org/en/download/

Install Git
https://git-scm.com/downloads

Go to terminal/command prompt and execute the commands listed below,

Install gulp globally (Mac users might need sudo in front of the command)
``` 
npm i -g gulp 
```

Clone the repository
``` 
git clone https://github.com/victorabraham/Lightning-Training.git
```

Navigate to the folder and install dependencies
``` 
cd Lightning-Training
npm i
```

## Deploying Updates to code

Open terminal/command prompt and navigate to Lightning-Training folder and Pull latest code from repository
``` 
cd Lightning-Training
git pull
```

Set environment variables and deploy sample code to sandbox

Mac Users
```
SF_USERNAME=yourUsernameHere SF_PASSWORD=yourPasswordAndSecurityTokenHere gulp deployToSF
```

Windows Users
```
SET SF_USERNAME=yourUsernameHere 
SET SF_PASSWORD=yourPasswordAndSecurityTokenHere 
gulp deployToSF
```
