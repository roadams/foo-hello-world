node {
    stage('clone') {
        git branch: 'main', url: 'https://github.com/roadams/foo-hello-world.git'
    }
    stage('build') {
        sh 'javac Main.java'
    }
    stage('run') {
        sh 'java Main'
    }
}
