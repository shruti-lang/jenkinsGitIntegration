pipeline {
    agent any

    stages {
        stage('Stage One') {
            steps {
                echo 'Hello Stage One - Step 1'
				echo 'Hello Stage One - Step 1' 
				build job : "groovyJob"
            }
        }
		stage('Stage Two') {
            steps {
                echo 'Hello Stage Two - Step 1'
				echo 'Hello Stage Two - Step 1'
				build job: "jenkinsGitIntegration"
            }
        }
		stage('Stage Three') {
            steps {
                echo 'Hello Stage Three - Step 1'
				echo 'Hello Stage Three - Step 1'
				build job: "mavenProject"
            }
        }
    }
}
