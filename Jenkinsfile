node {



stages {
stage ('checkout') {
steps {

	checkout scm
     }
}

stage ('compiling') {
steps {
	bat 'mvn install'
     }

}
}

post {
always {
echo 'I will always say Hello'
}
}	
}  

