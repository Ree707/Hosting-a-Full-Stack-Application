## Github
Developer will first create a emoty github repository, it will push and commit the code into it. 
The repository will be linked to CircleCi which will be triggered everytime the developer pushes changed to the linked repository. 
## CircleCi
A *.circleci/config.yml* must be present in the root folder so circleCi can read it and excute the two main jobs: build and deploy for both backend and frontend

A clear diagram for the pipline is show in a pipline.jpg file 