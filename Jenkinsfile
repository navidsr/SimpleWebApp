node {
   stage('Preparation') {
      git 'https://github.com/navidsr/SimpleWebApp.git'
   }
   stage('Build') {
      sh "./gradlew clean test"
   }
}