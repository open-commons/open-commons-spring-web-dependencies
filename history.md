[2026/04/22]
- 추가
  + 'org.apache.logging.log4j' 하위 artifact에 ${log4j2.version} 설정
  + 'open-commons-spring-web' 추가
  + Validation 관련 기능 추가
    + 'jakarata-validation'
  + Annotation 관련 기능 추가
    + 'jakarata-annotation'
    + 'org.jspecity'

[2025/07/24]
- Dependencies
  + 추가
    + com.google.code.findbugs:jsr305:3.0.2
    
[2025/02/21]
Apply 'Maven Central Deployment'

- 갱신
  + <deploymentManagement>
    + Release: Maven Central (https://central.sonatype.com)
  + 'open.commons' dependencies 
    + groupId: io.github.open-commons
  + springdoc-openapi-ui.version: 1.8.0
- 추가
  + <build>
    + org.sonatype.central:central-publishing-maven-plugin
    + org.apache.maven.plugins:maven-gpg-plugin