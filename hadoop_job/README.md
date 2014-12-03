#hadoop-job

Maven archetype for creating a Hadoop 2.5.1 job which
includes all its dependencies.

1. Install it in your local Maven (just the first time):
		
		$ cd hadoop_job
		$ mvn clean install

2. Creating a project from the archetype.

		$ mvn archetype:generate -Dfilter=hadoop

3. Select the archetype number under the list, and then proceed to answer the questions. It will create a directory with your maven project. 
4. Compiling and running:

		$ mvn clean package
		$ hadoop jar target/something-job.jar args

References
----------

  * [Blog article](http://blog.mafr.de/2010/07/24/maven-hadoop-job/) that
    explains the packaging setup

