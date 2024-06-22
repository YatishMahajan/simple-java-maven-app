pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                source /etc/profile.d/maven.sh
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}
