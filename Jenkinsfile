node {
   stage('Preparation') {
      git 'https://github.com/dan393/SimpleWebApp.git'
   }
   stage('Build') {
      sh "./gradlew clean test"
   }
}