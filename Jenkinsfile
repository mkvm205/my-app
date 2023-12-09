node{
    stage('SCM Checkout'){
        git 'https://github.com/mkvm205/my-app.git'
    }
    stage('Compile package'){
        //GET MAVEN HOME PATH
        def mvnHOME = tool name: 'maven-3', type: 'maven'
        sh "${mvnHOME}/bin/mvn package"
    }
}
