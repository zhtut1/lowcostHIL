pipeline {
    agent any

    stages{
        stage ('Alpha Stage'){
            steps{
                withMaven(maven: 'maven_3_9_6'){
                    bat 'mvn clean compile'
                }
            }
        }
        stage ('Beta Stage'){
            steps{
                withMaven(maven: 'maven_3_9_6'){
                    bat 'mvn test'
                }
            }
        }
        stage ('Production Stage'){
            steps{
                withMaven(maven: 'maven_3_9_6'){
                    bat 'mvn test'
                }
            }
        }
                }
            }
        }
    }
}
