pipeline{
    agent any
    stages {
        stage('Build'){
            steps{
                sh 'export M2_HOME=/usr/local/Cellar/maven/3.5.4/libexec'// # your Mavan home path
                sh 'export PATH=$PATH:$M2_HOME/bin'
                sh 'mvn clean package'
            }
        }
    }
}