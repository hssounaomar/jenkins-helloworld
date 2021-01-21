node {
    stage('Clone1') {
    git 'https://github.com/hssounaomar/jenkins-helloworld.git'
   }
   stage('Build') {
    bat "javac Main.java"
   }
   stage('Run') {
    bat 'java Main'
    }
}
