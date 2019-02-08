node {
    stage('build'){
        echo "building"
    }
}
node {
    stage('verify'){
        echo "verify build"
    }
}
node {
    stage('test'){
        echo "testing"
    }
}
stage('Get approval'){
    input "Deploy to qa?"
}
node {
    stage('deploy to qa'){
        echo "deploying"
    }
}
