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
        stage ('Test') {
          steps{
          echo 'Hello WORLD'
      }
    }
         stage ('Integration') {
           steps{
           echo 'Hello universe'
          }
        }




}

   post {
      always{
         echo "sendingmail"
      }   }


}


