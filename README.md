
# stackFinal Integration instructions

## android-app
This is the android app for favorite places...
### local
To run this project locally on an emulator, press the play-button from
Android studio.
### remote
n/a


## mongoDb
This is the persistence layer for favorite places...
### local
Run in a docker container:
docker run -ti --rm -p 27017:27017 mongo:4.0

### remote
Deploy to a docker container on Lightsail....


&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&

In order to add submodules, run the following command where <<your-git-repo>> is the clone path to your repo on github.
//git submodule add -b master <<your-git-repo-clone-address>>

//for example, the command would look something like this (but please don't add beers_quarks_kotlin as a submodule to 
your stackFinal project):
//git submodule add -b master git@github.com:agerber/beers_quarkus_kotlin.git

Repeat for all your subprojects. 

&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&



