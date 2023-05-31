node{
	stage('Build'){
		echo "Building"
		echo "PATH = ${PATH}"
		bat "dir"
		steps{
			bat 'mvn clean package'
		}
	}
	stage('Test'){
		echo "Testing"
	}
	stage('Deploy'){
		echo "Deploying"
	}
}
