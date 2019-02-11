node {
    stage('preparation'){
      git 'https://github.com/zeus1091/fleetman-position-tracker.git'
   }
   stage('Build') {
         sh "mvn package"
   }
   stage('Results') {
           archive 'target/*.jar'
   }
    stage('Deploy'){
    }
}
