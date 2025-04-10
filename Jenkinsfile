pipeline {
    agent any

    parameters {
        string(name: 'GREETING', defaultValue: 'Hello', description: 'What to say?')
        string(name: 'USERNAME', defaultValue: 'Ken Chen", description: 'Who's talking?')
    }

    stages {
        stage('Say Something') {
            steps {
                echo "${params.GREETING}, Jenkins! ${params.USERNAME} said to you"
            }
        }
    }
}
