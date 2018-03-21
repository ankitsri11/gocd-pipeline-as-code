# gocd-json-config-example
Example Go configuration repository with json configuration

## Server configuration

In order to import this configuration in your Go server.
1. Install json.config.plugin
2. Add this to your cruise-config.xml configuration:
```xml
<config-repos>
   <config-repo plugin="json.config.plugin">
     <git url="https://github.com/ankitsri11/gocd-pipeline-as-code.git" />
   </config-repo>
</config-repos>
```
