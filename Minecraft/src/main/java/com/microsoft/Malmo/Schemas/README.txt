This folder will be populated with java files generated by xjc (JAXB) from XML Schema files, 
driven by the jaxb task in build.gradle.

WARNING: Any .java files in this folder will be deleted as part of the build!

NOTE: Currently if the xsd files change the java files are not automatically regenerated as
      part of the build in Eclipse. As a workaround, manually run 'msbuild' or 'gradlew build'
      from the command line when the xsd changes. The remote builds are unaffected because they
      use msbuild.