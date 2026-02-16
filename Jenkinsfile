pipeline {
    agent any

    tools {
        jdk 'JDK17'
    }

    stages {

        stage('Checkout') {
            steps {
                git url: 'https://github.com/24p65a0524-ux/Devops_lab.git', branch: 'main'
            }
        }

        stage('Compile') {
            steps {
                sh 'javac Helloworld.java'
            }
        }

        stage('Run') {
            steps {
                sh 'java Helloworld'
            }
        }
    }
}
