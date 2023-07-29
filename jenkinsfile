pipeline {
	agent any

	stages {

		stage("Git Checkout") {
			steps {
				sh "echo checking out..."
			}
		}

		stage("Build") {
			steps{
				sh "echo building"
			}
		}

		stage("Authenticate") {
			steps{
				sh "echo authenticating..."
			}
		}


		stage("Push to Registry") {
			steps{
				sh "echo pushing..."
			}
		}

		stage("Cleanup") {
			steps{
				sh "echo cleanup..."
			}
		}


	}
}