# TychoProjectTemplate
Template for creating Eclipse plugin and RCP projects using Maven and Tycho.

## Content
* **bundles**:
This folder contains eclipse plugin projects.

* **features**:
This folder contains eclipse feature projects.

* **product**:
This folder contains a product project as well as an update site project.

* **releng**:
This folder contains the pom.xml file that describes how the project is released.

* **tests**:
This folder eventually contains test plugins.

![structure-tree](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/mraleborg/TychoProjectTemplate/master/structure.iuml)


## Build the project
``` 
mvn clean verify 
```