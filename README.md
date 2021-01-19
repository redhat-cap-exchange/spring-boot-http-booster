## Spring Boot Sample App

See https://appdev.openshift.io/docs/spring-boot-runtime.html#mission-http-api-spring-boot

### Configure the workspace

```shell
cp /projects/spring-boot-http-booster/.m2/settings.xml /home/jboss/.m2/settings.xml
```

https://github.com/jboss-container-images/openjdk/blob/develop/ubi8-openjdk-11.yaml

https://github.com/jboss-openshift/cct_module/tree/master/jboss/container/jws/s2i/bash/artifacts/usr/local/s2i

https://github.com/jboss-openshift/cct_module/blob/master/jboss/container/maven/s2i/artifacts/opt/jboss/container/maven/s2i/maven-s2i

JBOSS_IMAGE_NAME=ubi8/openjdk-11
JBOSS_CONTAINER_MAVEN_DEFAULT_MODULE=/opt/jboss/container/maven/default/
JBOSS_CONTAINER_JAVA_RUN_MODULE=/opt/jboss/container/java/run
AB_JOLOKIA_PASSWORD_RANDOM=true
HOSTNAME=c3c5217bd6d8
OLDPWD=/home/jboss
JAVA_HOME=/usr/lib/jvm/java-11
JBOSS_CONTAINER_MAVEN_36_MODULE=/opt/jboss/container/maven/36/
JBOSS_CONTAINER_S2I_CORE_MODULE=/opt/jboss/container/s2i/core/
JBOSS_CONTAINER_OPENJDK_JDK_MODULE=/opt/jboss/container/openjdk/jdk
JBOSS_CONTAINER_JOLOKIA_MODULE=/opt/jboss/container/jolokia
JBOSS_CONTAINER_JAVA_S2I_MODULE=/opt/jboss/container/java/s2i
container=oci
AB_PROMETHEUS_JMX_EXPORTER_CONFIG=/opt/jboss/container/prometheus/etc/jmx-exporter-config.yaml
AB_JOLOKIA_HTTPS=true
JAVA_VERSION=11
PWD=/tmp/src
HOME=/home/jboss
JBOSS_CONTAINER_JAVA_JVM_MODULE=/opt/jboss/container/java/jvm
OPENSHIFT_BUILD_SOURCE=https://github.com/redhat-capgemini-exchange/spring-boot-http-booster
JAVA_DATA_DIR=/deployments/data
JBOSS_IMAGE_VERSION=1.3
OPENSHIFT_BUILD_NAME=spring-boot-http-booster-6
AB_JOLOKIA_AUTH_OPENSHIFT=true
TERM=xterm
OPENSHIFT_BUILD_COMMIT=cb9fe93bdc192d8ec62c7956ced59dac037625ce
OPENSHIFT_BUILD_NAMESPACE=user42-lab3
JBOSS_CONTAINER_PROMETHEUS_MODULE=/opt/jboss/container/prometheus
JOLOKIA_VERSION=1.6.2
JAVA_VENDOR=openjdk
SHLVL=2
S2I_SOURCE_DEPLOYMENTS_FILTER=*.jar
MAVEN_VERSION=3.6
JBOSS_CONTAINER_MAVEN_S2I_MODULE=/opt/jboss/container/maven/s2i
PATH=/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/local/s2i
JBOSS_CONTAINER_UTIL_LOGGING_MODULE=/opt/jboss/container/util/logging/
OPENSHIFT_BUILD_REFERENCE=s2i
JBOSS_CONTAINER_JAVA_PROXY_MODULE=/opt/jboss/container/java/proxy
