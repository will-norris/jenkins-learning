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
		touch file.txt
                echo 'Cleaning up..'
            }
	}
    }
}

