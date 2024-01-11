pipeline {
	agent any
	stages{
	stage('Buils system details'){
		steps{
			sh '''
			echo "system    details"
			uname -a
			'''
		}
}
	stage('Build memomry details'){
                steps{
                        sh '''
                        echo "Memory details"
                        free
			'''
                }
}
	stage('Build CPU details'){
                steps{
                        sh '''
                        echo "CPU       details"
                        lscpu
			'''
                }
}
}
}
