pipeline {
    agent { label 'master' }

    options {
        timestamps()
        timeout(time:1, unit: 'HOURS')
    }

    environment {
        IMAGE_REPO_ADDR = "registry.cn-shanghai.aliyuncs.com"
        IMAGE_REPO_SPACE = "liyihang"
        GIT_REPO_ADDR = "gitee.com"
        SERVICE_RELEASE_GIT_REPO = "service-release"
        CREDENTIALS_ID = "80d14623-bb8c-486d-89b8-1d74ada52dfa"
        DATE = sh(script: "echo `date +%Y-%m-%d' && '%H:%M:%S`", returnStdout: true).trim()

    }

    stages {
        stage('build code') {
            steps {
                sh 'echo "ssss"'
            }
        }
    }
}
