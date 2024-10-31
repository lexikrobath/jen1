node {
	stage 'Checkout'
	checkout scm
	
	stage 'Build'
	sh 'echo "About to build Java app"'
	sh 'javac HelloWorld.java'
	
	stage 'Test'
	sh 'echo "Checking application works"'
	sh 'java HelloWorld | grep Hello'
}
