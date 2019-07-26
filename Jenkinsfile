node {
 stage ("get code from SCM") {
   git 'https://github.com/suni278/maven_projects1.git'
 }
 stage ('Comile-packege') {
    // Get maven home path
    def mvnHome = tool name: 'maven-3', type: 'maven'
	sh "${mvnhome}C:\\Program Files\\apache-maven-3.6.0\\bin package"
 }

}
