pipeline
	agent any
	stages{
	stage('Buils system details'){
		steps{
			sh ...
			echo "system details"
			uname -a
		}
}
	stages('Build memomry details'){
                steps{
                        sh ...
                        echo "Memory details"
                        free
                }
}
	stages('Build CPU details'){
                steps{
                        sh ...
                        echo "CPU details"
                        lscpu
                }
}
}
