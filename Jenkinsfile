env.M2_HOME = '/usr/local/Cellar/maven/3.5.4/libexec'
pipeline{
    agent any
    stages {
        stage('Build'){
            steps{
                
                sh 'export PATH=$PATH:$M2_HOME/bin; mvn clean package'
                //sh 'mvn clean package'
            }
        }
    }
}