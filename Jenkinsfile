pipeline {
agent any
stages {
	stage ('All stages') {
	parameters {
		string (var1:parameter 1,.....) 
	}
		parallel {
			stage ('Build-check')
			steps {
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
