node {
    stage('clone') {
        git branch: 'main', url: 'https://github.com/elfantiss/jenkins-hello.git'
}
    stage('Build') {
        sh 'javac Main.java'
}
    stage('Run') {
        sh 'java Main'
}
}
