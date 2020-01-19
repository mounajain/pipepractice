pipeline {
agent any
stages {
		stage ('Build-check') {
			    steps {
				    input ('Press yes to continue')
				    echo 'Building ....'
				    sh 'sleep 10'
			    }
		    }
	stage ('Deploy') { 
	paralle {
			    steps {
				     input ('Press yes to continue')
				    echo 'Deploying to test Environment....'
				    sh 'sleep 10'
			    }
		    }
}
	stage ('Test') { 
	parallel {
			    steps {
				    echo 'Testing....'
				    sh 'sleep 10'
			    }
	}
		    }
	    }
	}
