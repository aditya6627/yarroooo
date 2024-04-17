pipeline
{
    agent any
    stages
    {
        stage('ContinuousDownload')
        {
            steps
            {
                git 'https://github.com/intelliqittrainings/maven.git'
            }
        i}
        stage('ContinuousBuild')
        {
            steps
            {
                sh 'mvn package'
            }
    
        }
   }
}
