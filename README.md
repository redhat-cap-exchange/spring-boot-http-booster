## Spring Boot Sample App

See https://appdev.openshift.io/docs/spring-boot-runtime.html#mission-http-api-spring-boot

### Configure the workspace

```shell
cp /projects/spring-boot-http-booster/.m2/settings.xml /home/jboss/.m2/settings.xml
```

### Lab 5

```shell
oc new-project userXXX-lab5

oc create -f secrets.yaml

oc create -f build.yaml

oc create -f deploy.yaml

```

