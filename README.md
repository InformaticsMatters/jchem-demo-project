# Demo project showing how to use ChemAxon libs from gradle.

To run this create/edit gradle.properties and add these three properties:

* cxnMavenUser
* cxnMavenPassword
* cxnMavenRepositoryUrl

Instructions for this can be found [here](https://docs.chemaxon.com/display/docs/Public+Repository#PublicRepository-HowtoCongfigureYourProject), though they are slighly garbled.

Then try:

```sh
$ ./gradlew execute
:compileJava
:processResources UP-TO-DATE
:classes
:execute
JChem version: 17.15.0

BUILD SUCCESSFUL
```

You should see the JChem version reported as shown above.

