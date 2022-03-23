@library('jenkins-shared-library-demo')

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