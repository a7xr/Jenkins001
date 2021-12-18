node {
    stage('Clone') {
        git branch: 'main', url: 'https://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@github.com/a7xr/Jenkins001.git'
    }
    stage('Build') {
        sh 'javac Main.java'
    }
    stage('Run') {
        sh 'java Main'
    }
}
