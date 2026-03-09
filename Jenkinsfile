node{
stage('DEV')
stage('QA')
{
input "QA Deploy?"
}
stage('Deploy TO PROD")
{
bat 'xcopy git_jenkins.html C:\\apache-tomcat-9.0.115-windows-x64\\apache-tomcat-9.0.115\\webapps\\myapp /E /I /Y'
}

}
