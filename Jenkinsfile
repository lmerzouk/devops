import jenkins.model.*
node {
    stage('Build') {
	    def thr = Thread.currentThread()
        def build = thr?.executable
	    println (build.displayName)
        echo 'Building....'
    }
    stage('Test') {
        echo 'Building....'
    }
    stage('Deploy') {
        echo 'Deploying....'
    }
}