
node('ansible-node') {
    git credentialsId: 'git', url: 'https://github.com/roopesh2013/ansible-lab'
    ansiblePlaybook  disableHostKeyChecking: true, installation: 'ansible', playbook: 'update_etc_hosts.yml'
}

