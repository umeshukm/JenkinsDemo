node{
	stage('Build'){
		echo "Building"
		echo "PATH = ${PATH}"
		bat "dir"
		bat "cd C:\Users\ukmah\Desktop\demo\JenkinsDemo" 
		bat "mvn clean package"
	}
	stage('Test'){
		echo "Testing"
	}
	stage('Deploy'){
		echo "Deploying"
	}
}
