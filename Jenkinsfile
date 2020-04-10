node{
    stage('scm checkout')
    {
        git 'https://github.com/sathish0496/1004MavenProject'
    }
    stage('compile package')
    {
        def mvnHome = tool name: 'Maven 3.6.3', type: 'maven'
        sh "${mvnHome}/bin/mvn clean"
    }
}
