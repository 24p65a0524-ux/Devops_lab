pipeline {
    agent any
    
        stages {
        
            stage("Compile") {
            steps {
                sh 'javac helloworld.java'
            }
        }

        stage("Run") {
            steps {
                sh 'java helloworld'
            }
        }
    }
}
