pipeline {
    agent any

    stages {    
        stage('Main Branch') {
          when{
              branch 'main'
          }
            steps {
              echo 'Checkout code from Main'
               git 'https://github.com/Sailaxmi005/MULTIBRANCH-PIPELINE.git'
            }
        }
        stages {    
        stage('sailaxmi Branch') {
          when{
              branch 'sailaxmi'
          }
            steps {
              echo 'Checkout code from sailaxmi'
               git 'https://github.com/Sailaxmi005/MULTIBRANCH-PIPELINE.git'
            }
        }
        stage('development Branch') {
            when{
              branch 'development'
          }
            steps {
              echo 'Checkout code from development'
               git 'https://github.com/Sailaxmi005/MULTIBRANCH-PIPELINE.git'
            }
        }
       stage('testing Branch') {
            when{
              branch 'testing'
          }
            steps {
              echo 'Checkout code from testing'
               git 'https://github.com/Sailaxmi005/MULTIBRANCH-PIPELINE.git'
            }
        }
    }
}
