	TASK 8 — Run a Simple Java Maven Build Job in Jenkins
	
			Objective: Learn how to use Jenkins to build a simple Java application with Maven.
			 Purpose of This Project: Run a Simple Java Maven Build in Jenkins
 
	🔹 1. Goal / Objective
			The main purpose is to learn how Continuous Integration (CI) works — by making Jenkins automatically build a simple Java application using Maven.
			
			This project teaches:
		•	How Jenkins automates a Java build (no manual javac or mvn in terminal).
		•	How Maven manages dependencies and compiles your app.
		•	How Jenkins pipelines or jobs can detect, build, and verify code.

	Deliverables
		•	A basic Java HelloWorld app (src/main/java/HelloWorld.java) and pom.xml
			•	A Jenkins Freestyle job configured to build the project
		•	Screenshot of successful build console output

	Prerequisites
		•	Docker (optional) or a local Jenkins installation
		•	Java JDK 8 or 11 installed on the Jenkins agent (or controller if running builds there)
		•	Maven (will be configured in Jenkins Global Tool Configuration)
		•	Git (optional: if you store the repo in Git)

	Repository layout (sample):
			hello-java-maven/
			├─ app/
			    └─pom.xml
			└─ src/
			└─ main/java/
			└─ HelloWorld.java

