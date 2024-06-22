pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                sh '/opt/maven -B -DskipTests clean package' 
            }
        }
    }
}
