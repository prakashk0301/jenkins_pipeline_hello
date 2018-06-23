node {
   stage 'dev'
   		echo 'Hello World dev'
   stage 'test'
   		echo 'Hello World test'
   stage 'qa'
   		echo 'Hello World qa'
   stage 'prod'
   		echo 'Hello World prod'
}
stage('Deploy approval 1'){
    input "Deploy to qa?"
}
node {
    stage('deploy to qa'){
        echo "deploying in qa"
    }
}
stage('Deploy approval 2'){
    input "Deploy to prod?"
}
node {
    stage('deploy to prod'){
        echo "deploying in prod"
    }
}
