
//Jenkins Pipeline (or simply "Pipeline") is a suite of plugins which supports implementing and integrating continuous delivery pipelines into Jenkins. ... The definition of a Jenkins Pipeline is typically written into a text file (called a Jenkinsfile ) which in turn is checked into a project's source control repository.

pipeline {
         agent any
         stages {
                 stage('One') {
                 steps {
                     echo 'Hi, this is ARVIND VAISHNAVI'
                 }
                 }
                 stage('Two') {
                 steps {
                    input('Do you want to proceed?')
                 }
                 }
                 stage('Three') {
                 when {
                       not {
                            branch "master"
                       }
                 }
                 steps {
                       echo "Hello"
                 }
                 }
                  node{
    stage('SCM CHECKOUT'){
      git 'https://github.com/Arvind-97/test'
    }
    stage('Compile-Package'){
     def mvnHome = tool name: 'Maven 3.3.9', type: 'maven'
        sh "${Mavenhome}/usr/share/maven package"
    }
 
}

                
                           
                           
              }
}
