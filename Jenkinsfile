node{
   stage('SCM Checkout'){
     git 'https://github.com/Arvind-97/arvind_8026'
   }
   stage('Compile-Package'){
      def mvnHome = tool name: 'maven_3_3_9', type: 'maven'
      sh "${mvnHome}/usr/share/maven"
   }
} 
