pipeline {
	agent any

  environment {
		VERSION = '1.0.0'
	}

	stages {
		stage('Deploy') {
			steps {
        // wget o curl
				bat C:\\Users\\E19766\\.m2\\repository\\bootcamp\\jenkins\\' + env.VERSION + '\\war-example-' + env.VERSION + '.war D:\\devenv\\CURSOJENKINS\\ambientes\\tomcat1\\apache-tomcat-9.0.96\\webapps\\ROOT.war'
			}
		}
	}
}
