node {
    stage('preparation'){
      git 'https://github.com/zeus1091/fleetman-webapp.git'
   }
   stage('Build') {
         sh "mvn package"
   }
   stage('Results') {
           archive 'target/*.jar'
   }
}
