node{
   stage('SCM Checkout'){
     git 'https://github.com/smuvw/my-app'
   }
   stage('Compile-Package'){
    
      def mvnHome =  tool name: 'MAVEN_HOME', type: 'maven'   
      bat "${mvnHome}/bin/mvn package"
   }
  
 }
