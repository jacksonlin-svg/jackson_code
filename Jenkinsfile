pipeline {
    agent any
    parameters {
        choice(name: 'ACTION',choices:'create_qmgr\njack\nhello.........',description: 'a secret password')
       
    }
    stages {
        stage('Example') {
            steps {
                echo "$PERSON"
            }
        }
    }
}
