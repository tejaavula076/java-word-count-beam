# java-word-count-beam
I have used these instructions from this [Website](https://beam.apache.org/get-started/quickstart-java/) to complete this word count
 
**Steps used before Execution**
* Generated a Maven project that contains Beam’s WordCount examples
 mvn archetype:generate `
 -D archetypeGroupId=org.apache.beam `
 -D archetypeArtifactId=beam-sdks-java-maven-archetypes-examples `
 -D archetypeVersion=2.36.0 `
 -D groupId=org.example `
 -D artifactId=word-count-beam `
 -D version="0.1" `
 -D package=org.apache.beam.examples `
 -D interactiveMode=false
* cd .\word-count-beam
* dir
* dir .\src\main\java\org\apache\beam\examples
* converted maven to gradle : gradle init
* Building the project: gradle build

**Execution Command**
* mvn compile exec:
java -D exec.mainClass=org.apache.beam.examples.WordCount `-D exec.args="--inputFile=sample.txt --output=counts" -P direct-runner

