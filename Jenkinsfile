pipeline {
    agent any
    stages {
        stage('Disk Usage') {
            steps {
               sh 'du -kh'
            }
        }
        stage('Memory') {
            steps {
               sh 'free -g'
            }
        }
        stage('Cpu') {
            steps {
               sh 'lscpu'
            }
        }
    }
}
