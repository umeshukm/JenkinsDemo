node{
	stage('Build'){
		echo "Building"
		echo "PATH = ${PATH}"
		bat "dir"
		steps{
			bat 'mvn -BskipTests clean package'
		}
	}
	stage('Test'){
		echo "Testing"
	}
	stage('Deploy'){
		echo "Deploying"
	}
}
