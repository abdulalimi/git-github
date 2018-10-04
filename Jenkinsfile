pipeline {
	agent any
	stages {
			stage ('one') {
					steps {
						echo 'Hi, this is a declaration pipeline demo'
					}
			}
			stage ('two') {
					steps {
						input('Do you want to proceed?')
					}
			}
			stage ('three') {
					when {
							not { branch 'master'
							}
					steps {
							echo 'hello'
					}
					}
	}
}
