pipeline {
  agent {
    label 'ansible-server'
  }
  stages {
    stage('deploy patch playbook'){
      steps{
        dir('/home/ec2-user/ansinle-dev'){
          sh 'ansible-playbook patch.yml'
        }
      }
    }

  }
}
