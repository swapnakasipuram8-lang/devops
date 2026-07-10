pipeline {

    agent any

    stages {

        stage('Compile') {

            steps {

                bat 'javac pg.java'

            }

        }

        stage('Run') {

            steps {

                bat 'java pg'

            }

        }

    }
}
