node('master') 
{
    stage('continous download') 
{
   git credentialsId: '68866377-de52-4caa-81ef-14e13dd5a5f6', url: 'https://github.com/caithan/mavenjenkins.git'
}  
    stage('continous build')
     {
     sh 'mvn package'
      }
}
