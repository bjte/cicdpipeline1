node {
    stage 'build'
        echo 'Hello World (build)'
        openshiftBuild(namespace: 'insults', buildConfig: 'insults', showBuildLogs: 'true')
    stage 'deploy'
        echo 'Hello World (deploy)'
}
