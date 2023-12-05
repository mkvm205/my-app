node{
    stage('SCM Checkout'){
        git 'https://github.com/mkvm205/my-app.git'
    }
    stage('Compile package'){
        sh 'mvn package'
    }
}