node {
	stage('SCM Clone') {
		git 'https://github.com/Leela-Prasad/JenkinsTestProject.git'
	}
	stage('Build') {
		 sh "mvn clean package"
	}
}