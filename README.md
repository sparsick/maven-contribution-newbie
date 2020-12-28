# Guide for Maven Contribution Newbies


## Code Style and Convention
The code style and convention is documented in [Maven Developer Centre](http://maven.apache.org/developers/index.html) ([direct link to the code style page](https://maven.apache.org/developers/conventions/code.html)).

## Maven Plugin Development
The follow checklist applies to Maven plugins [that are supported by The Maven Project](https://maven.apache.org/plugins/index.html#supported-by-the-maven-project)

- [ ] Minimum supported Java version is 8
- [ ] Minimum supported Maven version is 3.1.0
- [ ] Use commons-lang or Java native instead of plexus-util
- [ ] Use for logging `AbstractMojo#getLog`