node(){
    stage('GIT'){
        git 'https://github.com/Sharathchandratelakapally/simplejava.git'
    }
    stage('PACK'){
        sh 'mvn package'
    }
    stage('upload'){
        sh '/var/lib/jenkins/upload.sh'
        
    }
}

