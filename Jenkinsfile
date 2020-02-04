
node('ansible-node') {
    ansiblePlaybook credentialsId: 'ansible', disableHostKeyChecking: true, installation: 'ansible', playbook: 'create_users.yml'
}

