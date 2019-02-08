node {
    stage('build'){
        echo "abc building"
    }
}
node {
    stage('test'){
        echo "xyz testing"
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
