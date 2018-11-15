 node {
        stage('Build') { 
                git 'https://github.com/999-888/jenkinstest.git'
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

