 node {
        stage('Build') { 
                println "Build" 
                fn = readFile $(env.WORKSPACE)/test.json
                echo fn
        }
        stage('Test') { 
                println "Test" 
        }
        stage('Deploy') { 
                println "Deploy" 
        }
}

