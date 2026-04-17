pipeline {
    agent any
    stages {
        stage('Stage1') {
            steps {
                script {
                    def num = 10  // or params.NUMBER
                    def result = (num % 2 == 0) ? 'Even' : 'Odd'
                    echo "Number ${num} is ${result}"
                }
            }
        }
    }
}
