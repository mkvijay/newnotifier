#!groovy
@Library(my-shared-library@master) _

pipeline {
    agent any

    stages {
        stage ('Compile Stage') {
            steps {
                echo 'Hello first'
            }
        }
        stage ('Testing Stage') {
            
            steps {
                echo 'Hello Second'
            }
        }
        stage ('Deployment Stage') {
            steps {
                echo 'Hello Third'
            }
        }
    }
}
