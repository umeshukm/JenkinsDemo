node{
	stage('Build'){
		echo "Building"
		echo "PATH = ${PATH}"
		bat "dir"
		bat "git clone https://github.com/umeshukm/JenkinsDemo.git"
		bat "mvn clean package"
	}
	stage('Test'){
		echo "Testing"
	}
	stage('Deploy'){
		echo "Deploying"
	}
}
