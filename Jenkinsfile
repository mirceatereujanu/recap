node{
    agent{
        additional_node
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