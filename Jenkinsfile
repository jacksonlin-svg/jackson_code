pipeline {
  agent any
  stages {
    stage('Example') {
      steps {
        echo "$PERSON"
      }
    }

  }
  parameters {
    choice(name: 'PERSON', choices: '''create_qmgr
jack
hello.........''', description: 'a secret password')
  }
}