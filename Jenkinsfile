node('built-in') 
{
    stage('Continuous Download_Loans') 
	{
    git 'https://github.com/Pranav11/maven.git'
	}
    stage('Continuous Build_Loans') 
	{
    sh label: '', script: 'mvn package'
	}
}
