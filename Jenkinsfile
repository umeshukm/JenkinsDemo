node{
	stage('Build'){
		echo "Building"
		echo "PATH = ${PATH}"
		bat "dir"
		bat "git clone https://github.com/umeshukm/JenkinsDemo.git"
		bat "cd JenkinsDemo && mvn clean"
	}
	stage('Test'){
		echo "Testing"
	}
	stage('Deploy'){
		echo "Deploying"
	}
}
