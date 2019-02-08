node {
    stage('build'){
        echo "building"
    }
}
stage('Get build approval'){
    input "build a project?"
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
