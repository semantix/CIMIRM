# CIMIRM (model-rm-opencimi)
An implementation of miniCIMI Reference Model
=============================================
This project creates Java classes from miniCIMI Reference Model.
The miniCIMI Reference Model (version 3.0.4) is in an XML schema
CIMI_RM3.0.4.xsd
This project depends on adl2-core project from OpenEHR.
https://github.com/openEHR/adl2-core

The ADL2 implementation already contains OpenEHR Referece Model 
in the parent project.

This project (CIMIRM) generates classes which augment adl2-core project with 
CIMI Reference model.

This project is dependent on OpenEHR adl2-core libraries at:
https://repo1.maven.org/maven2/org/openehr/adl2-core/

It uses "adl2-core", "model-rm" and "model-rm-openehr" modules.

```
Dependency Information:

       <dependency>
            <groupId>org.openEHR.adl2core</groupId>
            <artifactId>model-rm-opencimi</artifactId>
            <version>1.2.2</version>
        </dependency>
```
This project can be included in your Maven project using jitpack.io or using Mayo Clinic's Maven Repository
```
      <repository>
            <id>edu.informatics.maven.thirdparty</id>
            <name>Informatics Maven ThirdParty Repository</name>
            <url>http://informatics.mayo.edu/maven/content/repositories/thirdparty</url>
            <releases>
                <enabled>true</enabled>
            </releases>
            <snapshots>
                <enabled>false</enabled>
            </snapshots>
        </repository>
```

