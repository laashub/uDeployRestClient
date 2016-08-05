# IBM UrbanCode uDepoyRestClient Project
---

### License
This plugin is protected under the [Apache Version 2.0 License](https://www.apache.org/licenses/LICENSE-2.0.txt)

### Compatibility
	The uDeployRestClient is used to interact with IBM UrbanCode Deploy v6.0 or later and
    implemented through a plugin or script. It provides wrapper functionality, through the
    REST client, with various UCD objects such as: Applications, Components, and Processes. 
    
### Installation
	Download the .jar file from our Releases tab or use retreive it as a Maven Repository dependency.
    Once the download is configured, set the jar file on the classpath so you can access the classes within your code.

### History
    Version 1.0
        Community GitHub Release
 
### Compiling Source
`gradle`

The Gradle .jar file can be found in build/libs once the project has been built, under the Releases tab, or as an artifact on Maven Repository. To add the uDeployRestClient project as a dependency in another Gradle project, add the following lines:
```
dependencies {
    compile 'com.ibm.urbancode.plugins:uDeployRestClient:1.0'
}
```

To add the uDeployRestClient project as a dependency in another Ant Ivy project, add the following line:
```
<dependency org="com.ibm.urbancode.plugins" name="uDeployRestClient" rev="1.0"/>
```

To compile the project locally, four additional jar files are required: CommonsUtil.jar, commons-web.jar, HttpComponents-Util.jar , and udclient.jar.
Place these jars in uDeployRestClient project's 'lib' folder located in the root directory. These jars can be found within IBM UrbanCode Deploy's installation directory.