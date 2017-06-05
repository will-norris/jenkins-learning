#!/usr/bin/env groovy

pipeline {
    agent any

    stages {
	stage('Build') {
            steps {
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
                echo 'Deploying..'
            }
	}
        stage('Cleanup') {
            steps {
		echo "Trying to create a file...." > file.txt
                echo 'Cleaning up..'
            }
	}
    }
}

