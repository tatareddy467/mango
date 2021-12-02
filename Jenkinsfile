node {
    stage ('Git Clone') {
        git 'https://github.com/tatareddy467/jenkins'
        }
    stage ('Maven Clean') {
      sh 'mvn clean'
    }
    stage ('Maven Validate') {
      sh 'mvn validate'
    }            
    stage ('Maven Compile') {
      sh 'mvn compile'
    }
    stage ('Maven test') {
      sh 'mvn test'
    }
    stage ('Maven Package') {
      sh 'mvn package'
    }        
}           
