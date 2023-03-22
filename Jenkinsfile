pipeline { 
        agent {
    node {
        label "built-in"
        customWorkspace "/home/ec2-user/git/github-jenkins"
    }
}

              stages {  
                       stage('git fetch' ) { 
                          steps { 
                              sh 'git fetch'
}
}
                        stage('git pull' ) { 
                          steps { 
                              sh 'git pull origin master'
}
}
                         stage('git log' ) { 
                          steps { 
                              sh 'git log --oneline'
}
}
                        stage('git status' ) { 
                          steps { 
                              sh 'git status'
}
}
}
}
