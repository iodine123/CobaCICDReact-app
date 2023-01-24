pipeline {
    agent any
    stages {
        stage("Cek normal"){
            steps {
                sh "echo 'Hello World'"
            }
        }
        stage("ssh"){
            steps{
                sh "ssh neta@172.16.100.95"
                sh "ls -a"
            }
        }
    }
}