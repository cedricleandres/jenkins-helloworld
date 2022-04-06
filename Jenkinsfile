node {
    stage('clone') {
    git credentialsId: 'e0c10a1f-f0fb-4e26-bdbb-01425f73c104', url: 'https://github.com/cedricleandres/jenkins-helloworld'
        
    }
    stage('Build') {
    bat 'javac Main.java'   
    }
    stage('Run') {
    bat 'java Main'   
    }
}
