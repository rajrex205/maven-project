pipeline {
  agent any
   stages {
    stage("Git Checkout"){
            steps{
                git branch: "master", credentialsId: 'git2', url: 'https://github.com/rajrex205/maven-project.git'
            }
        }
	}
}
compile()
static_code_analysis()
