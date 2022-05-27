node{
    stage('Clone') {
        checkout scm
    }
    stage('Ansible') {
      ansiblePlaybook (
          colorized: true,          
          playbook: 'deploiement-lamp.yml'
      )
    }
}
