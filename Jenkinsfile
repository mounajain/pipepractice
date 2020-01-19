pipeline {
agent any
stages {
        stage('All stage') {
            parallel {
		    stage ('Build-check') {
			    steps {
				    echo 'Building ....'
				    sh 'sleep 100'
			    }
		    }
		    stage ('Deploy') {
			    steps {
				    echo 'Deploying to test Environment....'
				    sh 'sleep 100'
			    }
		    }
		    stage ('Test') {
			    steps {
				    echo 'Testing....'
				    sh 'sleep 100'
			    }
		    }
	    }
	}
}
}
