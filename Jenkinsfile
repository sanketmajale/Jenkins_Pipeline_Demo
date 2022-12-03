pipeline {
    agent {
        label 'node'
    }
    stages {
        stage ('Compile Stage') {

            steps {
                
                    sh 'mvn clean compile'
            }
        }
        stage ('Testing Stage') {

            steps {
                     echo 'Test done'
                   // sh 'mvn test'
            }
        }
        stage ('Install Stage') {
            steps {
                    echo 'Done'
                    //sh 'mvn install'
            }
        }
    }
}
