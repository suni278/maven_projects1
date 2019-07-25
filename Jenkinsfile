node {
 stage ("get code from SCM") {
   git 'https://github.com/suni278/maven_projects1.git'
 }
 stage ('Comile-packege') {
    // Get maven home path
    def mvnHome = tool name: 'maven-3', type: 'maven'
	sh "${mvnhome}/bin/mvn package"
 }

}
