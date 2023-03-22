pipeline { 
        agent any

              stages {  
                       stage(git fetch ){ 
                          steps { 
                              sh 'git fetch'
}
}
                        stage(git pull ){ 
                          steps { 
                              sh 'git pull origin master'
}
}
                         stage(git log ){ 
                          steps { 
                              sh 'git log --oneline'
}
}
                        stage(git status ){ 
                          steps { 
                              sh 'git status'
}
}
}
}
