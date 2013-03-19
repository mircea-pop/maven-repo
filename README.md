maven-repo
==========

ePages public maven repository

Usage
======
Include one of the next URLs in your Maven dependency:<br>

Releases:   http://epages-de.github.com/maven-repo/releases<br>
Snapshots:  http://epages-de.github.com/maven-repo/snapshots

<ul>Example: (Gradle) </ul>
```groovy
repositories {  
    maven { url "http://epages-de.github.com/maven-repo/releases" }
    }
```
Next you can define the dependencies like you would normally do for a Maven Repository.

<ul>Example: (Gradle)</ul> 
```groovy
dependencies {
    classpath(group: 'com.epages.plugins', name: 'migration', version: '0.1')
    }
```

