pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                sh 'sudo /opt/maven -B -DskipTests clean package' 
            }
        }
    }
}
