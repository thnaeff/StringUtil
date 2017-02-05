# StringUtil
String utility methods


---


[![License](http://img.shields.io/badge/License-Apache v2.0-802879.svg)](http://www.apache.org/licenses/LICENSE-2.0.html)
[![Java Version](http://img.shields.io/badge/Java-1.6%2B-2E6CB8.svg)](https://java.com)
[![Apache Maven ready](http://img.shields.io/badge/Apache Maven ready-3.3.9%2B-FF6804.svg)](https://maven.apache.org/)


---


##Features
* equals
	* Null-save equals method. Left in this library for compatibility (simply uses Objects.equals now)
* clipString right/left/center/center left/center right
	* Clips a string if the string exceeds a certain number of characters. The clipping location 
	can be defined with various types
* contains
	* Various methods to check if a pattern is contained in a string
* matches/matchesCount
	* Various methods to check if a string matches the pattern
* removeAll/replaceAll
	* Pattern remove and replace methods
* getMatching/getMatchingFirst
	* Methods which return all or just the first pattern match 
* rangesExtract/rangeExpand/rangesExpand/rangesReplace
	* Methods for range (e.g. "[a-zA-Z0-9]") operations. 
* randomString
	* Random string generation


---


<img src="http://maven.apache.org/images/maven-logo-black-on-white.png" alt="Built with Maven" width="150">

This project can be built with Maven

Maven command:
```
$ mvn clean install
```

pom.xml entry in your project:
```
<dependency>
	<groupId>ch.thn</groupId>
	<artifactId>stringutil</artifactId>
	<version>0.0.1-SNAPSHOT</version>
</dependency>
```

---
