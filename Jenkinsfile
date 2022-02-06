
pipeline{

    agent {label "maven-agent"}
      stages{
        stage("prep"){
          echo "hello world"
            git "https://github.com/Purushothrr/Purushothrr.git"
          sh "mvn clean deploy" 
       }
        stage('build'){
            echo "building applications"
        }
        stage('deploy'){
            echo "building applications"
        }
    }   

}


