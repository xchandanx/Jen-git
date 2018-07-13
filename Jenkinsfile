node {
    stage ('Get Code') {
       //  git 'https://github.com/awsdevopsssp/Jen-git.git'
       checkout scm
    }
    stage ('Run Script')
    {
        sh 'sh first.sh'
    }
    stage ('notify'){
        sh 'echo "Script ran successfully" '
    }
}
