<<<<<<< HEAD
pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('checkout') {
=======

pipeline {

    agent any
//     tools {
//         maven 'Maven_3.5.2' 
//     }
    stages {
          stage('Checkout') {
>>>>>>> 28ddc04ba4f421d8643f6626402ef0c1cfc6003e
            steps {
                 checkout scm
            }
        }
<<<<<<< HEAD
        stage('build') {
            steps {
                sh 'mvn clean test'
            }
        }
    }
}
=======
        stage('Compile stage') {
            steps {
                sh "mvn clean compile" 
        }
    }

         stage('testing stage') {
             steps {
                sh "mvn test"
        }
    }

  }

}
>>>>>>> 28ddc04ba4f421d8643f6626402ef0c1cfc6003e
