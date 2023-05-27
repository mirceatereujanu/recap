node{
    agent{
        agent1
    }
    stage('checkout'){
        def scmVars = checkout scm
        print("-----------------")
        print(scmVars.dump())
    }
    stage('Example'){
        sh "printenv"
    }
}