pipeline {
	agent any
	stages {
		stage('One') {
			steps {
				echo 'Hi, this is Brendan'
			}
		}
		
		stage('Two') {
			steps {
				input('Do you want to proceed?')
			}
		}
		
		stage('Build') {
            steps {
                echo 'Hi, this is stage 3'
            }
        }
        
        stage('Test') {
            steps {
                echo 'Hi, this is test stage'
            }
        }
        
        stage('Check') {
            steps {
                echo 'Hi, this is check stage'
            }
        }




        
		
		stage('Five') {
			steps {
				echo 'Finished'
			}
		}		
	}
}