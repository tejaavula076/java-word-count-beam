# java-word-count-beam
It is an intial example that i have started working on


Execution command : 
Running WordCount Using Maven
mvn compile exec:java -D exec.mainClass=org.apache.beam.examples.WordCount `-D exec.args="--inputFile=sample.txt --output=counts" -P direct-runner

Run WordCount Using Gradle
gradle clean execute -DmainClass=org.apache.beam.examples.WordCount \ -Dexec.args="--inputFile=sample.txt --output=counts" -Pdirect-runner
