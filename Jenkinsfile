pipeline{
    agent any
    tools{
        maven 'maven2'
    }
        stages{
            stage("build"){
                steps{
                sh 'mvn -B -DskipTests clean install package'
                }

            
        }
    }
}
