pipeline {
    agent any
    
        stages {
        
            stage ("build") {
            steps {
                sh 'javac helloworld.java'
            }
        }

        stage ("test") {
            steps {
                sh 'java helloworld'
            }
        }
    }
}
