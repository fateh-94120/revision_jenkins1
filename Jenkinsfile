node {
    stage('clone') {
    git 'https://github.com/fateh-94120/revision_jenkins1.git'
    }
    stage('Build') {
    sh label: '', script: 'javac Main.java'
    }
    stage('Run') {
    sh label: '', script: 'java Main'
    }
}
