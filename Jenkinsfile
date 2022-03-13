node {
	stage('SCM Clone') {
		git 'https://github.com/Leela-Prasad/JenkinsTestProject.git'
	}
	stage('Build') {
		 bat "mvn clean package"
	}
}