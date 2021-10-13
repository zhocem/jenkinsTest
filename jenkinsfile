node {
    stage('clone') {
        git branch: 'main', url: 'https://github.com/zhocem/jenkinsTest.git'
    }
    stage('build') {
        sh label: '', script: '''ls
        javac Main.java'''
    }
    stage('run') {
        sh '''ls
        java Main'''
    }
}
