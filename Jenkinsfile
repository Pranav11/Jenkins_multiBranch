node('built-in') 
{
    stage('Continuous Download_Master') 
	{
    git 'https://github.com/Pranav11/maven.git'
	}
    stage('Continuous Build_Master') 
	{
    sh label: '', script: 'mvn package'
	}    
}