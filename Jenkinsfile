node{
    stage('SCM Checkout'){
      git 'https://github.com/Arvind-97/arvind_8026'
    }
    stage('Compile-Package'){
       def mvnHome = tool name: 'maven-3.3.9', type: 'maven'
       sh "${mvnHome}/usr/share/mvn package"
    }
    
 
}
