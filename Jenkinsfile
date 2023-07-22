@Library('my-shared-library') _

pipeline{

   agent any

   stages{

     stage('checkout code'){

         steps{
         gitCheckout(
            
           branch: 'main', 
           url: 'https://github.com/Vireshgit/mrdevops_java_app1.git'

         )
         }      
     }

     stage('Unit Test maven'){

         steps{

         mvnTest()

         }
     }
   }
}


