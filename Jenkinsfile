@library('jenkins-shared-library-demo') _

pipeline{
    agent any{}
    stage('Demo'){
        steps{
            welcome("Jack Bauer")

            script(){
                calculator.add(25,75)
                calculator.mul(24,10)
            }
        }
    }
}