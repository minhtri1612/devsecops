pipeline {
  agent any
  tools { 
        maven 'Maven'  
    }
   stages{
    stage('CompileandRunSonarAnalysis') {
            steps {	
		sh 'mvn clean verify sonar:sonar -Dsonar.projectKey=minhtri16122004 -Dsonar.organization=minhtri16122004 -Dsonar.host.url=https://sonarcloud.io -Dsonar.token=dbcf762b9370c37807a11a7ac391d507cd584d66'
			}
        } 
  }
}
