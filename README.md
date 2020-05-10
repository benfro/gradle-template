# gradle-template
Template 'quick start' project
- Java
- Guava
- commons-lang3
- commons-io
- Gradle 6.4
- JUnit5
- Mockito  

### Setup

1. Change to your preferred name in file 'settings-gradle'

        rootProject.name = 'gradle-template'
    
2. Change group entry in 'build.gradle'

        group 'net.benfro'
    
3. Change to your preferred package stucture 
    in 'src/main/java' and 'src/test/java'
    
4. Run from command prompt (or IDEA's gradle tab)
    
        gradle init
    
    
TIP:
    If you run IDEA and want to create project setups for it:
    
    // id 'idea' <== uncomment this in file 'build.gradle'
    and run 'gradle idea'

### Resources

Gradle documentation: https://docs.gradle.org/current/userguide/userguide.html
