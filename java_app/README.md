#hadoop-job

Maven archetype for creating a standard java app.

1. Install it in your local Maven (just the first time):
		
		$ cd java_app
		$ mvn clean install

2. Creating a project from the archetype.

		$ mvn archetype:generate -Dfilter=JavaApp

3. Select the archetype number under the list, and then proceed to answer the questions. It will create a directory with your maven project. 
4. Compiling and running:

		$ mvn clean package
