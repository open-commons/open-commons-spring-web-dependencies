[2025/02/21]
Apply 'Maven Central Deployment'

- Update
  + <deploymentManagement>
    + Release: Maven Central (https://central.sonatype.com)
  + 'open.commons' dependencies 
    + groupId: io.github.open-commons
  + springdoc-openapi-ui.version: 1.8.0
- Add
  + <build>
    + org.sonatype.central:central-publishing-maven-plugin
    + org.apache.maven.plugins:maven-gpg-plugin