def workspace;
node
{
    
    stage('checkout')
    {
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/rameshreddy123/school.git']]])
        workspace =pwd()
    }
    stage('Statick Code Analysis')
    {
        echo "static code analysis"
    }
    stage('Build')
    {
        echo "Build the code"
    }
    stage('Unit-Testing')
    {
        echo "Unit-Testing"
    }
    stage('Delivery')
    {
        echo "Delivery"
    }
}
