pipeline {
  agent any
   stages {
    stage("Git Checkout"){
            steps{
                git branch: "master", credentialsId: 'git2', url: 'https://github.com/rajrex205/maven-project.git'
            }
        }
    stage{
      continuous_integration{
        build
        static_code_analysis
      }
     }
   }
  }
