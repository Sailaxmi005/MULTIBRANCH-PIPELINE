pipeline {
    agent any

    stages {
        stage('Main Branch') {
            when{
                branch 'main'
            }
            steps {
                git 'https://github.com/Sailaxmi005/MULTIBRANCH-PIPELINE.git'
                echo 'main Branch'
            }
        }
       stage('development Branch') {
            when{
                branch 'development'
            }
            steps {
                git 'https://github.com/Sailaxmi005/MULTIBRANCH-PIPELINE.git'
                echo 'development Branch'
            }
        }
        stage('testing Branch') {
            when{
                branch 'testing'
            }
            steps {
                git 'https://github.com/Sailaxmi005/MULTIBRANCH-PIPELINE.git'
                echo 'testing Branch'
            }
        }
      stage('sailaxmi Branch') {
            when{
                branch 'sailaxmi'
            }
            steps {
                git 'https://github.com/Sailaxmi005/MULTIBRANCH-PIPELINE.git'
                echo 'sailaxmi Branch'
            }
        }
    }
}
