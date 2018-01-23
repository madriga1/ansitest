pipeline {
  agent {label 'lnx2'}
  node {
    wrap([$class: 'AnsiColorBuildWrapper', colorMapName: "xterm"]) {
        ansiblePlaybook( 
            playbook: 'playbook.yml',
            inventory: 'inventory.ini', 
            credentialsId: 'sample-ssh-key',
            colorized: true) 
    }
  }
}
