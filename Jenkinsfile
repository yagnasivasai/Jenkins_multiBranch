node('master') 
{
    stage('Continuous Download_LOANS') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_LOANS') 
	{
    sh label: '', script: 'mvn package'
	}
}
