pipeline{
    agent any
    stages {
        stage('Build'){
            steps{
                sh 'export M2_HOME=/usr/local/Cellar/maven/3.5.4/libexec ; export PATH=$PATH:$M2_HOME/bin; mvn clean package'
            }
        }
    }
}