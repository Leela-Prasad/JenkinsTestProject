node {
	stage('SCM Clone') {
		git 'https://github.com/Leela-Prasad/JenkinsTestProject.git'
	}
	stage('Build') {
		 bat "C:\\Leela\\softwares\\apache-maven-3.8.4-bin\\apache-maven-3.8.4\\bin\\mvn clean package"
	}
}