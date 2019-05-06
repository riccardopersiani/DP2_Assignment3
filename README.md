## __Distributed Programming II A.Y. 2016-17__

### Assignment n. 3 - Part B

This archive includes:

- README            	This file
- `Assignment3a.pdf`   	The text of Assignment 3 - Part a
- `Assignment3b.pdf`   	The text of Assignment 3 - Part b
- `build.xml`				The ant script for this assignment
- `tomcat-build.xml`		The ant script for tomcat-related targets (included by build.xml)
- `custom`				The location of custom files
- `doc`               	The folder where you have to put the documentation of your design.
- `lib`					The location of the jar files necessary for this assignment
- `lib-src`				The location of library sources (to be attached to the
						corresponding lib jar files in eclipse)
- `src`					The location of source files
- `WebContent`			The folder including the files used for the deployment to Tomcat
- `war`					The location of the .war file of the Neo4JXML service and of the
						.war file that will be generated
- `xsd`					The location of your schema files

Setting the work environment for the project
--------------------------------------------
After Tomcat installation, set the Tomcat-related properties in `tomcat-build.xml`.

You can create a single eclipse java project for this package and then add the
jars under lib to the build path. It is also suggested to attach the sources
available in lib-src to the corresponding jar library.
DO NOT USE `tomcat-build.xml` directly. Instead use the `build.xml` (which imports it).

Start tomcat by running the start-tomcat target
(from `build.xml`).
The other instructions for using build.xml are included in the assignment text.
