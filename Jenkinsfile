node {
    stage 'checkout'
    checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/akshathanv/normalpipeline.git']]])
    
    stage 'build'
    build '/var/lib/jenkins/jobs/normalpipeline/workspace/EmployeeManagementSystem.sln'
    }



