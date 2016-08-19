# Simple Scalatra Archetype

An [Apache Maven](http://maven.apache.org/) archetype to generate a simple [Scalatra](http://scalatra.org) webapp. This archetype is based on the [scalatra-maven-prototype](https://github.com/Srirangan/scalatra-maven-prototype).

# Quick Start

0. This archetype has not been published on Maven central repositories hence you need to clone this project and install it in your local repository before using the archetype.
		git clone git://github.com/Srirangan/simple-scalatra-archetype.git simple-scalatra-archetype
		cd simple-scalatra-archetype
		mvn install

1. Generate your Scalatra project
		mvn archetype:generate -DarchetypeArtifactId=simple-scalatra-archetype -DarchetypeGroupId=org.scalatra -DarchetypeVersion=1.0-SNAPSHOT -DgroupId=just.some.group -DartifactId=just-some-artifact

2. Switch to the project directory
		cd just-some-artifact

3. Install your project
		mvn install

4. Run Jetty webserver
		mvn jetty:run
