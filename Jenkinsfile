pipeline{

   agent {
      label 'ansible'
   }
         stages {
          stage('Build') {
            steps {
           echo 'how are you'
        }
      }
   }

       stage('Hello') {
        steps{
         echo 'Hello WORLD'
      }
    }


   post {
      always{
         echo "sendingmail"
      }   }


}


