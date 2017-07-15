# Demo project showing how to use ChemAxon libs from gradle.

**NOTE**: this does not currently work - trying to establish why not.

To run this create/edit gradle.properties and add these three properties:

* cxnMavenUser
* cxnMavenPassword
* cxnMavenRepositoryUrl

Instructions for this can be found [here](https://docs.chemaxon.com/display/docs/Public+Repository#PublicRepository-HowtoCongfigureYourProject), though they are slighly garbled.

Then try:

```sh
./gradlew build
```

