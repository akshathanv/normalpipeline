node {
    stage 'checkout'
    withCredentials([[$class: 'UsernamePasswordMultiBinding',
                      credentialsId: '34761a89-1402-47d7-96e2-aec22ffdc50b',
                      usernameVariable: 'USERNAME', passwordVariable: 'PASSWORD']]) {
        sh "svn co https://trac.nci.org.au/svn/cable/branches/$SVN_BRANCH --username $USERNAME --password $PASSWORD cable_branch"
    }
}
