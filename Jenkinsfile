
node('ansible-node') {
    git credentialsId: 'git', url: 'https://github.com/roopesh2013/ansible-lab'
    ansiblePlaybook installation: 'ansible', inventory: '/etc/ansible/hosts', playbook: 'update_etc_hosts.yml'
}

