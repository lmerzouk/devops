pipeline {
    agent any

    stages {
        stage('Build') {
		     
            steps {
			  println (build.displayName)
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}