
node('ansible-node') {
    ansiblePlaybook credentialsId: 'root', disableHostKeyChecking: true, installation: 'ansible', playbook: 'create_users.yml'
}

