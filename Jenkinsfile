node {
    wrap([$class: 'AnsiColorBuildWrapper', colorMapName: "xterm"]) {
        print "Workspace: ${WORKSPACE}"
        ansiblePlaybook( 
            playbook: 'playbook.yml',
            inventory: 'inventory', 
            credentialsId: 'sample-ssh-key',
            colorized: true) 
    }
  }
