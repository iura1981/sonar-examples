This example demonstrates how to analyze C# projects with the Sonar Runner or Maven.

Prerequisites
=============
* [Sonar](http://www.sonarsource.org/downloads/) 2.11 or higher
* [Sonar Runner](http://docs.codehaus.org/display/SONAR/Installing+and+Configuring+Sonar+Runner) 1.3 or higher or Maven 2.2.1 or higher
* [Sonar C# Plugin](http://docs.codehaus.org/display/SONAR/C%23+Plugins+Ecosystem) 1.3 or higher

Usage
=====
* Download the project sample from [https://github.com/SonarCommunity/sonar-dotnet/tree/master/tools/dotnet-tools-commons/src/test/resources/solution/Example](https://github.com/SonarCommunity/sonar-dotnet/tree/master/tools/dotnet-tools-commons/src/test/resources/solution/Example)
* Compile it:

        mvn clean install
		
		
* Analyze it with Sonar using the Sonar Runner:

        sonar-runner
		
* Or analyze it with Sonar using Maven:

        mvn sonar:sonar
