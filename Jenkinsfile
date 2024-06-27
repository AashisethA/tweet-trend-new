pipeline {
    agent {
        node{
            label 'maven'
        }
    }
enviroment{
    PATH = "/opt/apache-maven-3.9.8/bin: $PATH"

}
    stages {
       stage("build"){
        step{
            sh 'mvn clean deploy'
        }
       } 
    }
}

