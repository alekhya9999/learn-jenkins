// pipeline{
//
//    agent {
//       label 'ansible'
//    }
//     stages {
//           stage('Build') {
//             steps {
//            echo 'how are you'
//         }
//       }
//         stage ('Test') {
//           steps{
//           echo 'Hello WORLD'
//       }
//     }
//          stage ('Integration') {
//            steps{
//            echo 'Hello universe'
//           }
//         }
// }
//
//    post {
//       always{
//          echo "sendingmail"
//    }   }
// }
//
//

@Library('roboshop') _
 pipeline{
  agent any
   stages{
     stage('test'){
       steps{
         script {
            def abc = "Hello"
            def xyz = 10

            print "abc = ${abc}"
            print "xyz = ${xyz}"

            print abc



         }
       }
     }
   }

 }