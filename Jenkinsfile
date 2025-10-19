pipeline {
    agent any
    stages {
        stage('Welcome Page for Test') {
            steps {
                echo "Hello World to Test"
            }
        }
        stage('Permission') {
            steps {
                input(
                    message: "Are you Approve", 
                    ok: 'Accept', 
                    submitter: '',     // optional: allow any user
                    submitterParameter: '', // optional
                    id: 'Approval'    // optional unique ID
                )
            }
        }
    }
}
