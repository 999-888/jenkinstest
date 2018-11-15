 node {
        stage('Build') { 
                println "Build" 
                fn = readFile $(evn.WORKSPACE)/test.json
                echo fn
        }
        stage('Test') { 
                println "Test" 
        }
        stage('Deploy') { 
                println "Deploy" 
        }
}

