pipeline {
    agent any
    stages {
        stage("GIT") {
            steps {
               git "https://github.com/gopal-jogi/task_jenkins.git"
            }
        }
        stage("Run") {
            steps {
                sh "java Demo.java"
            }
        }
    }
}
