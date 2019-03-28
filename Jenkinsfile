node{
	stage('Hello'){
		sh "echo 'Hello'"
	}
	stage('Build'){
		sh "echo 'Master'"
	}
	stage('Added Branch'){
		sh "git branch deploy"
		sh "git checkout deploy"
		sh "git tag -a v1.3"
		sh "git commit -m 'Added Tag v1.3'"
		sh "git checkout master"
	}
}
