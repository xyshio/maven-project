
pipeline{
    agent any
    environment {
        M2_HOME = '/usr/local/Cellar/maven/3.5.4/libexec'
        PATH = "$PATH:$M2_HOME/bin"
        //DOCKER_HOME = '/usr/local'
        //PATH = "$PATH:$DOCKER_HOME/bin"



    }
    stages {
        stage('Build'){
            steps{
                
                // sh 'mvn clean package'
                //sh "docker build . -t tomcatwebapp:${env.BUILD_ID}"
                sh 'whoami'
                //sh 'chmod u+x /Applications/Docker.app/Contents/Resources/bin/docker'
                //sh '/Applications/Docker.app/Contents/Resources/bin/docker image ls -a'
                sh 'docker image ls -a'
            }
        }
    }
}
