pipeline{
agent any
stage('Build') {
steps{
	bat 'mvn -B -DskipTests clean package'
	}
}