# Accelerator Log

## Options
```json
{
  "projectName" : "hello-world",
  "deploymentType" : "workload",
  "message" : "World"
}
```
## Log
```
┏ engine (Chain)
┃  Info Running Chain(GeneratorValidationTransform, UniquePath)
┃ ┏ ┏ engine.transformations[0].validated (Combo)
┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ engine.transformations[0].validated.delegate (Chain)
┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃  Info Running Merge(Combo, Combo, Combo, Combo, Combo, Combo, Combo)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].sources[0].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, Exclude)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[0].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**]
┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug cloudfoundry/DEPLOYING.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug cloudfoundry/manifest.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug tap/DEPLOYING.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug tap/catalog-info.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug tap/workload.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.jar matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/hello/HelloWorldApplication.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/hello/HelloWorldController.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┗ Debug src/test/java/com/example/hello/HelloWorldApplicationTests.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[0].delegate.transformations[1] (Exclude)
┃ ┃ ┃ ┃ ┃ ┃  Info Will exclude [pom.xml, README.md, cloudfoundry/**, tap/**, .github/workflows/**]
┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [pom.xml, README.md, cloudfoundry/**, tap/**, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [pom.xml, README.md, cloudfoundry/**, tap/**, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [pom.xml, README.md, cloudfoundry/**, tap/**, .github/workflows/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [pom.xml, README.md, cloudfoundry/**, tap/**, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [pom.xml, README.md, cloudfoundry/**, tap/**, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml matched [pom.xml, README.md, cloudfoundry/**, tap/**, .github/workflows/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug cloudfoundry/DEPLOYING.md matched [pom.xml, README.md, cloudfoundry/**, tap/**, .github/workflows/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug cloudfoundry/manifest.yml matched [pom.xml, README.md, cloudfoundry/**, tap/**, .github/workflows/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tap/DEPLOYING.md matched [pom.xml, README.md, cloudfoundry/**, tap/**, .github/workflows/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tap/catalog-info.yaml matched [pom.xml, README.md, cloudfoundry/**, tap/**, .github/workflows/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tap/workload.yaml matched [pom.xml, README.md, cloudfoundry/**, tap/**, .github/workflows/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.jar didn't match [pom.xml, README.md, cloudfoundry/**, tap/**, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [pom.xml, README.md, cloudfoundry/**, tap/**, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.properties didn't match [pom.xml, README.md, cloudfoundry/**, tap/**, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/hello/HelloWorldApplication.java didn't match [pom.xml, README.md, cloudfoundry/**, tap/**, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/hello/HelloWorldController.java didn't match [pom.xml, README.md, cloudfoundry/**, tap/**, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┗ ┗ Debug src/test/java/com/example/hello/HelloWorldApplicationTests.java didn't match [pom.xml, README.md, cloudfoundry/**, tap/**, .github/workflows/**] -> included
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].sources[1].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[1].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [pom.xml]
┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml matched [pom.xml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug cloudfoundry/DEPLOYING.md didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug cloudfoundry/manifest.yml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tap/DEPLOYING.md didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tap/catalog-info.yaml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tap/workload.yaml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.jar didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.properties didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/hello/HelloWorldApplication.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/hello/HelloWorldController.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug src/test/java/com/example/hello/HelloWorldApplicationTests.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[1].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┗ ┗  Info Will replace [hello-world->hello-world]
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[2] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#deploymentType == 'none') evaluated to false
┃ ┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[3] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#deploymentType == 'manifest') evaluated to false
┃ ┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[4] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#deploymentType == 'workload') evaluated to true
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].sources[4].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText, RewritePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[4].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [tap/catalog-info.yaml]
┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [tap/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [tap/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [tap/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [tap/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [tap/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [tap/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug cloudfoundry/DEPLOYING.md didn't match [tap/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug cloudfoundry/manifest.yml didn't match [tap/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tap/DEPLOYING.md didn't match [tap/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tap/catalog-info.yaml matched [tap/catalog-info.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug tap/workload.yaml didn't match [tap/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.jar didn't match [tap/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [tap/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.properties didn't match [tap/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/hello/HelloWorldApplication.java didn't match [tap/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/hello/HelloWorldController.java didn't match [tap/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug src/test/java/com/example/hello/HelloWorldApplicationTests.java didn't match [tap/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[4].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [hello-world->hello-world]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[4].delegate.transformations[2] (RewritePath)
┃ ┃ ┃ ┃ ┗ ┗ Debug Path 'tap/catalog-info.yaml' matched '^(?<folder>.*/)?(?<filename>([^/]+?|)(?=(?<ext>\.[^/.]*)?)$)' with groups {ext=.yaml, folder=tap/, filename=catalog-info.yaml, g0=tap/catalog-info.yaml, g1=tap/, g2=catalog-info.yaml, g3=catalog-info.yaml, g4=.yaml} and was rewritten to 'catalog/catalog-info.yaml'
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[5] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#deploymentType == 'workload') evaluated to true
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].sources[5].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText, RewritePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[5].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [tap/workload.yaml]
┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug cloudfoundry/DEPLOYING.md didn't match [tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug cloudfoundry/manifest.yml didn't match [tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tap/DEPLOYING.md didn't match [tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tap/catalog-info.yaml didn't match [tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tap/workload.yaml matched [tap/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.jar didn't match [tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.properties didn't match [tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/hello/HelloWorldApplication.java didn't match [tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/hello/HelloWorldController.java didn't match [tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug src/test/java/com/example/hello/HelloWorldApplicationTests.java didn't match [tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[5].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [hello-world->hello-world, World->World]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[5].delegate.transformations[2] (RewritePath)
┃ ┃ ┃ ┃ ┗ ┗ Debug Path 'tap/workload.yaml' matched '^(?<folder>.*/)?(?<filename>([^/]+?|)(?=(?<ext>\.[^/.]*)?)$)' with groups {ext=.yaml, folder=tap/, filename=workload.yaml, g0=tap/workload.yaml, g1=tap/, g2=workload.yaml, g3=workload.yaml, g4=.yaml} and was rewritten to 'config/workload.yaml'
┃ ┃ ┃ ┃ ┏ README (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ README.delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┃ ┏ README.delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Merge(Combo, Combo, Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┏ README.delegate.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ README.delegate.transformations[0].sources[0].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ README.delegate.transformations[0].sources[0].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [README.md]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug cloudfoundry/DEPLOYING.md didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug cloudfoundry/manifest.yml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug tap/DEPLOYING.md didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug tap/catalog-info.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug tap/workload.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.jar didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.properties didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/hello/HelloWorldApplication.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/hello/HelloWorldController.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug src/test/java/com/example/hello/HelloWorldApplicationTests.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ README.delegate.transformations[0].sources[0].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗  Info Will replace [hello-world->hello-world]
┃ ┃ ┃ ┃ ┃ ┃ ┏ README.delegate.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#deploymentType == 'manifest') evaluated to false
┃ ┃ ┃ ┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┃ ┃ ┃ ┏ README.delegate.transformations[0].sources[2] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#deploymentType == 'workload') evaluated to true
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ README.delegate.transformations[0].sources[2].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText, RewritePath)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ README.delegate.transformations[0].sources[2].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [tap/DEPLOYING.md]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug cloudfoundry/DEPLOYING.md didn't match [tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug cloudfoundry/manifest.yml didn't match [tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug tap/DEPLOYING.md matched [tap/DEPLOYING.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug tap/catalog-info.yaml didn't match [tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug tap/workload.yaml didn't match [tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.jar didn't match [tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.properties didn't match [tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/hello/HelloWorldApplication.java didn't match [tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/hello/HelloWorldController.java didn't match [tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug src/test/java/com/example/hello/HelloWorldApplicationTests.java didn't match [tap/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ README.delegate.transformations[0].sources[2].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [hello-world->hello-world]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ README.delegate.transformations[0].sources[2].delegate.transformations[2] (RewritePath)
┃ ┃ ┃ ┃ ┃ ┗ ┗ ┗ Debug Path 'tap/DEPLOYING.md' matched '^(?<folder>.*/)?(?<filename>([^/]+?|)(?=(?<ext>\.[^/.]*)?)$)' with groups {ext=.md, folder=tap/, filename=DEPLOYING.md, g0=tap/DEPLOYING.md, g1=tap/, g2=DEPLOYING.md, g3=DEPLOYING.md, g4=.md} and was rewritten to 'README.md'
┃ ┃ ┃ ┃ ┃ ┏ README.delegate.transformations[1] (UniquePath)
┃ ┃ ┃ ┗ ┗ ┗ Debug Multiple representations for path 'README.md', will concatenate them together
┃ ┗ ┗ ╺ engine.transformations[0].validated.delegate.transformations[1] (UniquePath)
┗ ╺ engine.transformations[1] (UniquePath)
```
