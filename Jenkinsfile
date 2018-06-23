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
node {
    stage('build'){
        echo "building"
    }
}
stage('Deploy approval'){
    input "Deploy to prod?"
}
node {
    stage('deploy to prod'){
        echo "deploying"
    }
}
