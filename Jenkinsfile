node{
   stage('SCM Checkout'){
     git 'https://github.com/Arvind-97/arvind_8026'
   }
   stage('Compile-Package'){
      def mvnHome = tool name: 'maven_3_8_3', type: 'maven'
      sh "${mvnHome}/bin/mvn/package"
   }
} 
