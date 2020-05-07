how to use:
add repo to settings.xml
http://10.240.2.45:9999/nexus/content/repositories/userManagment
To generate a new project from this archetype, type:
mvn archetype:generate -DarchetypeGroupId=rzd.pktbcdt.maven.archetypes
 -DarchetypeArtifactId=web-mgmt-j2ee-simple-archetype
  -DarchetypeVersion=1.0
   -DartifactId=module
   -Dproject-name=testProject
   -Daudit_id=32543
   -Dsystem_id=-1
    -X
