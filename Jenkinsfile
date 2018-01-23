node {
    wrap([$class: 'AnsiColorBuildWrapper', colorMapName: "xterm"]) {
        ansiblePlaybook( 
            playbook: 'playbook.yml',
            inventory: 'inventory', 
            credentialsId: 'sample-ssh-key',
            colorized: true) 
    }
  }
