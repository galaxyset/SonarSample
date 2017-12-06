# SonarSample

https://www.vultr.com/docs/how-to-install-sonarqube-on-ubuntu-16-04


https://www.howtoforge.com/tutorial/how-to-install-sonarqube-on-ubuntu-1604/


https://www.voyalab.com/2016/10/06/install-sonarqube-ubuntu/


Download Sonar scanner here:
https://sonarsource.bintray.com/Distribution/sonar-scanner-cli/

Unzip the download and set environment variable 

Navigate to conf properties from sonar scanner and set the analysis properties

sonar.projectKey=DemoProject
sonar.projectName=DemoProject
sonar.projectVersion=1.0
sonar.sources=C:/workspace/demo/src

Go to Sonar Qube and start the server- hit http://localhost:9000

Now go to source code C:/workspace/demo/src in command promt and run:- sonar-runner.bat

Go to SonarQube dash to see the report.

Resolve if any issues and re-run the scan.


