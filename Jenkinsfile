pipeline{

   agent {
      label 'ansible'
   }
     stages {

        stage('Hello') {
        steps{
         echo 'Hello WORLD'
      }
    }
   }

   post {
      always{
         echo "sendingmail"
      }   }


}


