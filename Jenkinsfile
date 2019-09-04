pipeline {
	agent any
		stages {
			stage ('Build'){
				steps {
					script{
						echo 'hello'
						GIT_LOGCMD = sh "git log -n --pretty=format:" + "%h%x09%an%x09%ad%x09%s"
				}
			}
		}
	}
}

