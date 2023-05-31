node{
	stage('Build'){
		echo "Building"
		sh 'git clone https://github.com/umeshukm/JenkinsDemo.git'
		mvn clean install
	}
	stage('Test'){
		echo "Testing"
	}
	stage('Deploy'){
		echo "Deploying"
	}
}
