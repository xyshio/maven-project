env.M2_HOME = '/usr/local/Cellar/maven/3.5.4/libexec'
env.PATH = $PATH:$M2_HOME + '/bin'
pipeline{
    agent any
    stages {
        stage('Build'){
            steps{
                
                sh 'mvn clean package'
                
            }
        }
    }
}