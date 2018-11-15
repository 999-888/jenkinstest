 node {
        stage('Build') { 
                println "Build" 
                fl = "${env.WORKSPACE}/test.json"
                fn = readFile fl
                echo fn
        }
        stage('Test') { 
                println "Test" 
        }
        stage('Deploy') { 
                println "Deploy" 
        }
}

