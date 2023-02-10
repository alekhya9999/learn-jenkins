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
      stages {

           stage('Hello1') {
           steps{
            echo 'Hello universe'
        }
      }
   }
          stages {

              stage('Hello2') {
              steps{
               echo 'Hello galaxy'
           }
        }
     }
   post {
      always{
         echo "sendingmail"
      }   }


}


