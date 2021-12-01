pipeline {
<<<<<<< HEAD
   agent {
	 docker {
		image 'maven:3.8.1-adoptopenjdk-11' //1
		args '-v /root/.m2:/root/.m2'	    //2
	 }
   }
   stages {
	stage('Build') {			    //3
		steps {
			sh 'mvn -B -DskipTests clean package' //4
		}
	}
   }
}
=======
  agent {
    docker {
      image 'maven:3.5.1-adoptopenjdk-11'
      args '-v /root/.m2:/root/.m2'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'mvn -B -DskipTests clean package'
      }
    }

  }
}
>>>>>>> de727c3c3ceb8f2d6bd7c4ba3f755cd257435c4c
