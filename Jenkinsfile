node {
    stage('clone') {
git 'git \'https://github.com/cedricleandres/jenkins-helloworld/\''
        
    }
    stage('Build') {
    sh 'javac Main.java'   
    }
    stage('Run') {
    sh 'java Main'   
    }
}
