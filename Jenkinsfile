
node {

	stage('sourcecode') {

		git 'https://github.com/sudarsanpidugu/game-of-life.git'


}
	stage('build the code') {

		sh 'mvn clean package'

}
	stage('Archiving and test results') {

		archiveArtifacts artifacts: '**/*.war', followSymlinks: false


}


}
