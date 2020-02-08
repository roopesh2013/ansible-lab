
node('ansible-node') {
    git credentialsId: 'git', url: 'https://github.com/roopesh2013/ansible-lab'
    sh label: '', script: '/usr/bin/ansible-playbook /tmp/workspace/ansible-check/update_etc_hosts.yml'
}

