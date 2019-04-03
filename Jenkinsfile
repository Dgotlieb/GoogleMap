pipeline {
    agent any
    stages {
        stage('Git'){
            steps{
                script {
                    properties([pipelineTriggers([pollSCM('* * * * *')])])
                }
                git 'https://github.com/Dgotlieb/GoogleMap.git'
            }
        }
        stage('Run By Me'){
            steps{
                echo 'ssss'
            }
        }
        stage('Build') {

            steps {

                echo 'Build'

            }}

       stage('Deploy') {

            steps {
                echo 'deploy'
            }}
    }
}
