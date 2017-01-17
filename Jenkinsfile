node {
    stage 'build'
        echo 'Hello World (build)'
        openshiftBuild(buildConfig: 'insults', showBuildLogs: 'true')
    stage 'deploy'
        echo 'Hello World (deploy)'
}
