pipeline {
    agent any
    
        stages {
        
            stage ("build") {
            steps {
                sh 'javac Helloworld.java'
            }
        }

        stage ("test") {
            steps {
                sh 'java Helloworld'
            }
        }
    }
}
