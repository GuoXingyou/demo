#### mvn clean deploy -P dev -Dmaven.test.skip
#### mvn versions:set -DnewVersion=your new version

mvn clean archetype:create-from-project -Darchetype.properties=./archetype.properties

mvn archetype:generate -B -DarchetypeGroupId=com.ecommerce -DarchetypeArtifactId=demo-archetype -DarchetypeVersion=1.0.0-SNAPSHOT -DgroupId=com.ecommerce -DartifactId=mytest -Dversion=1.0.0-SNAPSHOT