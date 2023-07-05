pipeline{
  agent any
    stages{
        stage("git checkout"){
          steps{
            git branch: 'main', url: 'https://github.com/Ngshrdd/chatGPT.git'
                }
        }
         stage("mavane package"){
           steps{
             sh'mvn clean package'
           }
         }
              }
             }
          
              
