# Log4jForSelenium
Log 4j Yaml file for adding and saving logs to Selenium Framework 

# For GRADLE. In Build.Gradle include the following Dependencies:
    # For Log4j
    testCompile (group: 'org.apache.logging.log4j', name: 'log4j-core', version: '2.11.1')
    testCompile (group: 'org.apache.logging.log4j', name: 'log4j-api', version: '2.11.1')
    # For Yml dependency
    compile (group: 'com.fasterxml.jackson.dataformat', name: 'jackson-dataformat-yaml', version: '2.9.8')
    compile (group: 'com.fasterxml.jackson.core', name: 'jackson-databind', version: '2.9.8')
    
# For Maven. In POM.XML use the following:
    # For log4j dependency
    <dependency>
      <groupId>org.apache.logging.log4j</groupId>
      <artifactId>log4j-core</artifactId>
      <version>2.11.1</version>
    </dependency>
    <dependency>
      <groupId>org.apache.logging.log4j</groupId>
      <artifactId>log4j-api</artifactId>
      <version>2.11.1</version>
    </dependency>
    # For Yml dependency
    <dependency>
      <groupId>com.fasterxml.jackson.dataformat</groupId>
      <artifactId>jackson-dataformat-yaml</artifactId>
      <version>2.9.8</version>
    </dependency>
    <dependency>
      <groupId>com.fasterxml.jackson.core</groupId>
      <artifactId>jackson-databind</artifactId>
      <version>2.9.8</version>
    </dependency>
    
    # Where to Place?
      Create the log4j2-test.yml file in the Selenium Framework
      Path: src > test > resources
