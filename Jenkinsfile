#!/usr/bin/env groovy
pipeline {
    agent any

    stages {
        stage('Build') { 
            steps { 
                sh 'first step' 
            }
        }
        stage('Test'){
            steps {
                sh 'second step' 
            }
        }
        stage('Deploy') {
            steps {
                sh 'third step'
            }
        }
    }
}
