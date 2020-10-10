pipeline {
    agent any
    stages {
        stage('Publish') { 
            steps {
                script {
                    docker.withRegistry("", "indrika123_dockerhub") {
                        def customImage = docker.build("indrika123/swe645-fall2020-hw1")
                        customImage.push()
                    }
                }
            }
        }
		stage('Deploy') {
			steps {
				script {
					rancherRedeploy alwaysPull: true, credential: 'rancher-server', images: 'indrika123/swe645-fall2020-hw1:latest', workload: '<Rancher workload URL>'
				}
			}
		}
    }
}
