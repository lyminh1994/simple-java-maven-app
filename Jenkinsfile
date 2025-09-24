pipeline {
    agent any
    tools {
        jdk "jdk-17"
        maven "maven-3.9.11"
    }
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}