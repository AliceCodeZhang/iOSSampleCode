pipeline {
  agent {
    node {
      label 'mac'
    }
    
  }
  stages {
    stage('perpare') {
      steps {
        sh 'echo prepared'
        git(url: 'https://github.com/AliceCodeZhang/iOSSampleCode.git', branch: 'v1.0', changelog: true, poll: true)
      }
    }
  }
}