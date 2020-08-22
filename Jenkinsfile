node{
    stage('SCM Checkout'){
        git 'https://github.com/Arvind-97/arvind_8026'
    }
    stage('Compile-Package'){
       def mavenHome = tool name: 'maven-3.3.9', type: 'maven'
        sh "${mavenHome}/usr/share/maven package"
    }
    
 
}
