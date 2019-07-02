node("docker") {
    
    stage("Git checkout") {
        commit_details = checkout scm
        version = commit_details.GIT_COMMIT
        sh "echo $commit_details"
         // git credentialsId: 'github_external', url: 'https://github.com/stenyjames/maven-project.git'
        
    }
    
}
