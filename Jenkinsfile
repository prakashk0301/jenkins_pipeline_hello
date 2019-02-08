node {
    stage('build'){
        echo "shounak building"
    }
}
node {
    stage('test'){
        echo "sj testing"
    }
}
stage('Get approval'){
    input "sj Deploy to qa?"
}
node {
    stage('deploy to qa'){
        echo "sj deploying"
    }
}
