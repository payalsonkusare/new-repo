# new-repo
# new-repo
234
new updates
again give the changes
changes 3345
hyyyer4v


pipeline {
    agent {
        node {
            label 'built-in'
            customWorkspace '/mnt/jenkins'
        }
    }
	stages {
        stage('new_folder') {
            steps {
                sh 'mkdir Dee'
            }
        }
		
    }
}
