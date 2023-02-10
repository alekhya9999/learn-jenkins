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


