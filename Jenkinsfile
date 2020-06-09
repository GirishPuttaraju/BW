def gv
node{
	stage('Initialize pipeline'){
			echo 'Initialize pipeline'
		}
	stage('Clean Up Workspace and Checkout SCM'){
			gv = load "master.groovy"
		}
		
	stage('Build'){
			gv.buildMaven()
		}
}