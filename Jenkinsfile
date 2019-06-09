pipeline {
    agent any 
    stages('---Clean---') {
            steps {
                sh "mvn clean"
            }
        }
        stage('---Test---') { 
            steps {
                sh "mvn test" 
            }
        }
        stage('---Deploy---') { 
            steps {
                sh "mvn package" 
            }
        }
    }
}
