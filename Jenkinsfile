pipeline {
    agent any
    stages {
        stage("GIT") {
            steps {
               "https://github.com/gopal-jogi/task_jenkins.git"
            }
        }
        stage("Run") {
            steps {
                sh "java Demo.java"
            }
        }
    }
}
