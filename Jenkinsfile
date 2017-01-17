node {
    stage 'build'
        echo 'Hello World (build)'
        openShiftBuild(buildConfig: 'insults', showBuildLogs: 'true')
    stage 'deploy'
        echo 'Hello World (deploy)'
}
