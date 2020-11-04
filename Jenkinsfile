pipeline {
    agent any
    parameters {
        choice(name: 'PERSON',choices:'create_qmgr\njack\nhello.........',description: 'a secret password')
       
    }
    stages {
        stage('Example') {
            steps {
                echo "$PERSON"
            }
        }
    }
}
