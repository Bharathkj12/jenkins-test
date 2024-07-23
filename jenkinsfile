pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                sh '''#!/bin/bash
                 python3 /tmp/1.py
                '''
            }
        }
        stage('Test') { 
            steps {
                sh '''#!/bin/bash
                 python3 /tmp/2.py

                '''            }
        }
        stage('Deploy') { 
            steps {
            sh '''#!/bin/bash
                 python3 /tmp/3.py
                '''            }
        }
    }
}
