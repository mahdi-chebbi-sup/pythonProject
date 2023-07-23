node {
    stage('build') {
    git branch: 'production', url: 'https://github.com/mahdi-chebbi-sup/pythonProject/'
    }
    stage('Test'){
      sh 'python3 -m pytest -v .'
    }
}
