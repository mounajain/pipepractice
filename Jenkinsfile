pipeline {
agent any
stages {
        stage('All stage') {
            parallel {
		    stage ('Build-check') {
			    steps {
				    input ('Press yes to continue')
				    echo 'Building ....'
				    sh 'sleep 10'
			    }
		    }
		    stage ('Deploy') {
			    steps {
				    echo 'Deploying to test Environment....'
				    sh 'sleep 10'
			    }
		    }
		    stage ('Test') {
			    steps {
				    echo 'Testing....'
				    sh 'sleep 10'
			    }
		    }
	    }
	}
}
}
