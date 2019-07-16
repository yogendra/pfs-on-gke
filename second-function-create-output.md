---
# Second Function - Output
```
Applied default --image="gcr.io/pa-yrampuria/uppercase"
Waiting for LatestCreatedRevisionName
Waiting on function creation: function creation incomplete: service status unknown: RevisionMissing
LatestCreatedRevisionName available: uppercase-vkfb5
default/uppercase-btpf4-pod-d4639b[build-step-git-source-0]: {"level":"info","ts":1563257338.318488,"logger":"fallback-logger","caller":"git-init/main.go:101","msg":"Successfully cloned \"https://github.com/projectriff-samples/java-boot-uppercase.git\" @ \"master\" in path \"/workspace\"","commit":"4fc8663"}
default/uppercase-btpf4-pod-d4639b[build-step-analyze]: WARNING: image 'gcr.io/pa-yrampuria/uppercase' not found or requires authentication to access
default/uppercase-btpf4-pod-d4639b[build-step-analyze]: WARNING: image 'gcr.io/pa-yrampuria/uppercase' has incompatible 'io.buildpacks.lifecycle.metadata' label
default/uppercase-btpf4-pod-d4639b[build-step-build]: -----> Cloud Foundry OpenJDK Buildpack 1.0.0-M5
default/uppercase-btpf4-pod-d4639b[build-step-build]: -----> OpenJDK JDK 11.0.2: Contributing to layer
default/uppercase-btpf4-pod-d4639b[build-step-build]:        Reusing cached download from buildpack
default/uppercase-btpf4-pod-d4639b[build-step-build]:        Expanding to /layers/org.cloudfoundry.openjdk/openjdk-jdk
default/uppercase-btpf4-pod-d4639b[build-step-build]:        Writing JAVA_HOME to build
default/uppercase-btpf4-pod-d4639b[build-step-build]:        Writing JDK_HOME to build
default/uppercase-btpf4-pod-d4639b[build-step-build]: -----> OpenJDK JRE 11.0.2: Contributing to layer
default/uppercase-btpf4-pod-d4639b[build-step-build]:        Reusing cached download from buildpack
default/uppercase-btpf4-pod-d4639b[build-step-build]:        Expanding to /layers/org.cloudfoundry.openjdk/openjdk-jre
default/uppercase-btpf4-pod-d4639b[build-step-build]:        Writing JAVA_HOME to shared
default/uppercase-btpf4-pod-d4639b[build-step-build]:
default/uppercase-btpf4-pod-d4639b[build-step-build]: -----> Cloud Foundry Build System Buildpack 1.0.0-M5
default/uppercase-btpf4-pod-d4639b[build-step-build]: -----> Using wrapper
default/uppercase-btpf4-pod-d4639b[build-step-build]:        Linking Cache to /home/pack/.m2
default/uppercase-btpf4-pod-d4639b[build-step-build]: -----> Compiled Application: Contributing to layer
default/uppercase-btpf4-pod-d4639b[build-step-build]:        Running /workspace/mvnw -Dmaven.test.skip=true package
default/uppercase-btpf4-pod-d4639b[build-step-build]: [INFO] Scanning for projects...
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/boot/spring-boot-starter-parent/2.1.0.RELEASE/spring-boot-starter-parent-2.1.0.RELEASE.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/boot/spring-boot-starter-parent/2.1.0.RELEASE/spring-boot-starter-parent-2.1.0.RELEASE.pom (12 kB at 13 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/boot/spring-boot-dependencies/2.1.0.RELEASE/spring-boot-dependencies-2.1.0.RELEASE.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/boot/spring-boot-dependencies/2.1.0.RELEASE/spring-boot-dependencies-2.1.0.RELEASE.pom (142 kB at 125 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-dependencies/Greenwich.M3/spring-cloud-dependencies-Greenwich.M3.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-dependencies/Greenwich.M3/spring-cloud-dependencies-Greenwich.M3.pom (8.3 kB at 15 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-dependencies-parent/2.1.0.RC2/spring-cloud-dependencies-parent-2.1.0.RC2.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-dependencies-parent/2.1.0.RC2/spring-cloud-dependencies-parent-2.1.0.RC2.pom (6.5 kB at 12 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-commons-dependencies/2.1.0.M2/spring-cloud-commons-dependencies-2.1.0.M2.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-commons-dependencies/2.1.0.M2/spring-cloud-commons-dependencies-2.1.0.M2.pom (3.5 kB at 7.0 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-netflix-dependencies/2.1.0.M3/spring-cloud-netflix-dependencies-2.1.0.M3.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-netflix-dependencies/2.1.0.M3/spring-cloud-netflix-dependencies-2.1.0.M3.pom (16 kB at 28 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-stream-dependencies/Fishtown.RC2/spring-cloud-stream-dependencies-Fishtown.RC2.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-stream-dependencies/Fishtown.RC2/spring-cloud-stream-dependencies-Fishtown.RC2.pom (7.1 kB at 14 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-task-dependencies/2.1.0.M1/spring-cloud-task-dependencies-2.1.0.M1.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-task-dependencies/2.1.0.M1/spring-cloud-task-dependencies-2.1.0.M1.pom (2.7 kB at 5.7 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-config-dependencies/2.1.0.M3/spring-cloud-config-dependencies-2.1.0.M3.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-config-dependencies/2.1.0.M3/spring-cloud-config-dependencies-2.1.0.M3.pom (3.7 kB at 8.0 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-function-dependencies/2.0.0.RC2/spring-cloud-function-dependencies-2.0.0.RC2.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-function-dependencies/2.0.0.RC2/spring-cloud-function-dependencies-2.0.0.RC2.pom (3.1 kB at 3.9 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-gateway-dependencies/2.1.0.M3/spring-cloud-gateway-dependencies-2.1.0.M3.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-gateway-dependencies/2.1.0.M3/spring-cloud-gateway-dependencies-2.1.0.M3.pom (3.0 kB at 6.1 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-consul-dependencies/2.1.0.M2/spring-cloud-consul-dependencies-2.1.0.M2.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-consul-dependencies/2.1.0.M2/spring-cloud-consul-dependencies-2.1.0.M2.pom (4.3 kB at 8.7 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-sleuth-dependencies/2.1.0.M2/spring-cloud-sleuth-dependencies-2.1.0.M2.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-sleuth-dependencies/2.1.0.M2/spring-cloud-sleuth-dependencies-2.1.0.M2.pom (4.4 kB at 5.2 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-vault-dependencies/2.1.0.M2/spring-cloud-vault-dependencies-2.1.0.M2.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-vault-dependencies/2.1.0.M2/spring-cloud-vault-dependencies-2.1.0.M2.pom (3.7 kB at 6.5 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-zookeeper-dependencies/2.1.0.M1/spring-cloud-zookeeper-dependencies-2.1.0.M1.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-zookeeper-dependencies/2.1.0.M1/spring-cloud-zookeeper-dependencies-2.1.0.M1.pom (5.2 kB at 11 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-dependencies-parent/2.1.0.M2/spring-cloud-dependencies-parent-2.1.0.M2.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-dependencies-parent/2.1.0.M2/spring-cloud-dependencies-parent-2.1.0.M2.pom (6.5 kB at 13 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-security-dependencies/2.1.0.M1/spring-cloud-security-dependencies-2.1.0.M1.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-security-dependencies/2.1.0.M1/spring-cloud-security-dependencies-2.1.0.M1.pom (3.1 kB at 6.7 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-cloudfoundry-dependencies/2.1.0.M1/spring-cloud-cloudfoundry-dependencies-2.1.0.M1.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-cloudfoundry-dependencies/2.1.0.M1/spring-cloud-cloudfoundry-dependencies-2.1.0.M1.pom (3.2 kB at 6.4 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-bus-dependencies/2.1.0.M2/spring-cloud-bus-dependencies-2.1.0.M2.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-bus-dependencies/2.1.0.M2/spring-cloud-bus-dependencies-2.1.0.M2.pom (2.7 kB at 5.5 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-contract-dependencies/2.1.0.M2/spring-cloud-contract-dependencies-2.1.0.M2.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-contract-dependencies/2.1.0.M2/spring-cloud-contract-dependencies-2.1.0.M2.pom (7.5 kB at 15 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-aws-dependencies/2.0.1.RELEASE/spring-cloud-aws-dependencies-2.0.1.RELEASE.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-aws-dependencies/2.0.1.RELEASE/spring-cloud-aws-dependencies-2.0.1.RELEASE.pom (7.0 kB at 14 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-dependencies-parent/2.0.4.RELEASE/spring-cloud-dependencies-parent-2.0.4.RELEASE.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-dependencies-parent/2.0.4.RELEASE/spring-cloud-dependencies-parent-2.0.4.RELEASE.pom (6.5 kB at 13 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/com/amazonaws/aws-java-sdk-bom/1.11.415/aws-java-sdk-bom-1.11.415.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/com/amazonaws/aws-java-sdk-bom/1.11.415/aws-java-sdk-bom-1.11.415.pom
Downloaded from central: https://repo.maven.apache.org/maven2/com/amazonaws/aws-java-sdk-bom/1.11.415/aws-java-sdk-bom-1.11.415.pom (31 kB at 36 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/com/amazonaws/aws-java-sdk-pom/1.11.415/aws-java-sdk-pom-1.11.415.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/com/amazonaws/aws-java-sdk-pom/1.11.415/aws-java-sdk-pom-1.11.415.pom
Downloaded from central: https://repo.maven.apache.org/maven2/com/amazonaws/aws-java-sdk-pom/1.11.415/aws-java-sdk-pom-1.11.415.pom (14 kB at 38 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-openfeign-dependencies/2.1.0.M2/spring-cloud-openfeign-dependencies-2.1.0.M2.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-openfeign-dependencies/2.1.0.M2/spring-cloud-openfeign-dependencies-2.1.0.M2.pom (5.1 kB at 9.3 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-kubernetes-dependencies/1.0.0.M2/spring-cloud-kubernetes-dependencies-1.0.0.M2.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-kubernetes-dependencies/1.0.0.M2/spring-cloud-kubernetes-dependencies-1.0.0.M2.pom (6.8 kB at 14 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/io/fabric8/kubernetes-client-bom/3.1.10/kubernetes-client-bom-3.1.10.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/io/fabric8/kubernetes-client-bom/3.1.10/kubernetes-client-bom-3.1.10.pom
Downloaded from central: https://repo.maven.apache.org/maven2/io/fabric8/kubernetes-client-bom/3.1.10/kubernetes-client-bom-3.1.10.pom (3.6 kB at 10 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-gcp-dependencies/1.1.0.M3/spring-cloud-gcp-dependencies-1.1.0.M3.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-gcp-dependencies/1.1.0.M3/spring-cloud-gcp-dependencies-1.1.0.M3.pom (6.5 kB at 10 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/com/google/cloud/google-cloud-bom/0.71.0-alpha/google-cloud-bom-0.71.0-alpha.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/com/google/cloud/google-cloud-bom/0.71.0-alpha/google-cloud-bom-0.71.0-alpha.pom
Downloaded from central: https://repo.maven.apache.org/maven2/com/google/cloud/google-cloud-bom/0.71.0-alpha/google-cloud-bom-0.71.0-alpha.pom (46 kB at 89 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/com/google/api/gax-bom/1.35.0/gax-bom-1.35.0.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/com/google/api/gax-bom/1.35.0/gax-bom-1.35.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/com/google/api/gax-bom/1.35.0/gax-bom-1.35.0.pom (2.7 kB at 7.7 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/com/fasterxml/jackson/jackson-bom/2.9.7/jackson-bom-2.9.7.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/jackson-bom/2.9.7/jackson-bom-2.9.7.pom
Downloaded from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/jackson-bom/2.9.7/jackson-bom-2.9.7.pom (12 kB at 35 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/com/fasterxml/jackson/jackson-parent/2.9.1.1/jackson-parent-2.9.1.1.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/jackson-parent/2.9.1.1/jackson-parent-2.9.1.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/jackson-parent/2.9.1.1/jackson-parent-2.9.1.1.pom (8.0 kB at 23 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/com/fasterxml/oss-parent/33/oss-parent-33.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/com/fasterxml/oss-parent/33/oss-parent-33.pom
Downloaded from central: https://repo.maven.apache.org/maven2/com/fasterxml/oss-parent/33/oss-parent-33.pom (22 kB at 49 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/io/netty/netty-bom/4.1.29.Final/netty-bom-4.1.29.Final.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/io/netty/netty-bom/4.1.29.Final/netty-bom-4.1.29.Final.pom
Downloaded from central: https://repo.maven.apache.org/maven2/io/netty/netty-bom/4.1.29.Final/netty-bom-4.1.29.Final.pom (7.9 kB at 23 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/sonatype/oss/oss-parent/7/oss-parent-7.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/sonatype/oss/oss-parent/7/oss-parent-7.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/sonatype/oss/oss-parent/7/oss-parent-7.pom (4.8 kB at 14 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/io/projectreactor/reactor-bom/Californium-SR2/reactor-bom-Californium-SR2.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/io/projectreactor/reactor-bom/Californium-SR2/reactor-bom-Californium-SR2.pom
Downloaded from central: https://repo.maven.apache.org/maven2/io/projectreactor/reactor-bom/Californium-SR2/reactor-bom-Californium-SR2.pom (3.6 kB at 10 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/apache/logging/log4j/log4j-bom/2.11.1/log4j-bom-2.11.1.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/logging/log4j/log4j-bom/2.11.1/log4j-bom-2.11.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/logging/log4j/log4j-bom/2.11.1/log4j-bom-2.11.1.pom (6.1 kB at 17 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/apache/logging/logging-parent/1/logging-parent-1.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/logging/logging-parent/1/logging-parent-1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/logging/logging-parent/1/logging-parent-1.pom (3.2 kB at 9.1 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/apache/apache/18/apache-18.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/apache/18/apache-18.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/apache/18/apache-18.pom (16 kB at 45 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/eclipse/jetty/jetty-bom/9.4.12.v20180830/jetty-bom-9.4.12.v20180830.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/eclipse/jetty/jetty-bom/9.4.12.v20180830/jetty-bom-9.4.12.v20180830.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/eclipse/jetty/jetty-bom/9.4.12.v20180830/jetty-bom-9.4.12.v20180830.pom (18 kB at 50 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/glassfish/jersey/jersey-bom/2.27/jersey-bom-2.27.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/glassfish/jersey/jersey-bom/2.27/jersey-bom-2.27.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/glassfish/jersey/jersey-bom/2.27/jersey-bom-2.27.pom (22 kB at 61 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/net/java/jvnet-parent/4/jvnet-parent-4.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/net/java/jvnet-parent/4/jvnet-parent-4.pom
Downloaded from central: https://repo.maven.apache.org/maven2/net/java/jvnet-parent/4/jvnet-parent-4.pom (7.8 kB at 22 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/junit/junit-bom/5.3.1/junit-bom-5.3.1.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/junit/junit-bom/5.3.1/junit-bom-5.3.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/junit/junit-bom/5.3.1/junit-bom-5.3.1.pom (4.1 kB at 6.9 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/spring-framework-bom/5.1.2.RELEASE/spring-framework-bom-5.1.2.RELEASE.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/spring-framework-bom/5.1.2.RELEASE/spring-framework-bom-5.1.2.RELEASE.pom (5.3 kB at 7.9 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/data/spring-data-releasetrain/Lovelace-SR2/spring-data-releasetrain-Lovelace-SR2.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/data/spring-data-releasetrain/Lovelace-SR2/spring-data-releasetrain-Lovelace-SR2.pom (4.6 kB at 9.6 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/data/build/spring-data-build/2.1.2.RELEASE/spring-data-build-2.1.2.RELEASE.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/data/build/spring-data-build/2.1.2.RELEASE/spring-data-build-2.1.2.RELEASE.pom (6.6 kB at 12 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/integration/spring-integration-bom/5.1.0.RELEASE/spring-integration-bom-5.1.0.RELEASE.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/integration/spring-integration-bom/5.1.0.RELEASE/spring-integration-bom-5.1.0.RELEASE.pom (8.7 kB at 18 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/security/spring-security-bom/5.1.1.RELEASE/spring-security-bom-5.1.1.RELEASE.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/security/spring-security-bom/5.1.1.RELEASE/spring-security-bom-5.1.1.RELEASE.pom (5.0 kB at 10 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/session/spring-session-bom/Bean-RELEASE/spring-session-bom-Bean-RELEASE.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/session/spring-session-bom/Bean-RELEASE/spring-session-bom-Bean-RELEASE.pom (3.0 kB at 6.3 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: [INFO]
default/uppercase-btpf4-pod-d4639b[build-step-build]: [INFO] ------------------< io.projectriff.samples:uppercase >------------------
default/uppercase-btpf4-pod-d4639b[build-step-build]: [INFO] Building uppercase 0.0.1-SNAPSHOT
default/uppercase-btpf4-pod-d4639b[build-step-build]: [INFO] --------------------------------[ jar ]---------------------------------
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/springframework/boot/spring-boot-maven-plugin/2.1.0.RELEASE/spring-boot-maven-plugin-2.1.0.RELEASE.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/springframework/boot/spring-boot-maven-plugin/2.1.0.RELEASE/spring-boot-maven-plugin-2.1.0.RELEASE.pom (4.8 kB at 13 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/springframework/boot/spring-boot-tools/2.1.0.RELEASE/spring-boot-tools-2.1.0.RELEASE.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/springframework/boot/spring-boot-tools/2.1.0.RELEASE/spring-boot-tools-2.1.0.RELEASE.pom (1.8 kB at 5.1 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/springframework/boot/spring-boot-parent/2.1.0.RELEASE/spring-boot-parent-2.1.0.RELEASE.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/springframework/boot/spring-boot-parent/2.1.0.RELEASE/spring-boot-parent-2.1.0.RELEASE.pom (1.8 kB at 5.1 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/springframework/boot/spring-boot-dependencies/2.1.0.RELEASE/spring-boot-dependencies-2.1.0.RELEASE.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/springframework/boot/spring-boot-dependencies/2.1.0.RELEASE/spring-boot-dependencies-2.1.0.RELEASE.pom (0 B at 0 B/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/springframework/spring-framework-bom/5.1.2.RELEASE/spring-framework-bom-5.1.2.RELEASE.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/springframework/spring-framework-bom/5.1.2.RELEASE/spring-framework-bom-5.1.2.RELEASE.pom (0 B at 0 B/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/springframework/data/spring-data-releasetrain/Lovelace-SR2/spring-data-releasetrain-Lovelace-SR2.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/springframework/data/spring-data-releasetrain/Lovelace-SR2/spring-data-releasetrain-Lovelace-SR2.pom (0 B at 0 B/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/springframework/data/build/spring-data-build/2.1.2.RELEASE/spring-data-build-2.1.2.RELEASE.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/springframework/data/build/spring-data-build/2.1.2.RELEASE/spring-data-build-2.1.2.RELEASE.pom (0 B at 0 B/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/springframework/integration/spring-integration-bom/5.1.0.RELEASE/spring-integration-bom-5.1.0.RELEASE.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/springframework/integration/spring-integration-bom/5.1.0.RELEASE/spring-integration-bom-5.1.0.RELEASE.pom (0 B at 0 B/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/springframework/security/spring-security-bom/5.1.1.RELEASE/spring-security-bom-5.1.1.RELEASE.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/springframework/security/spring-security-bom/5.1.1.RELEASE/spring-security-bom-5.1.1.RELEASE.pom (0 B at 0 B/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/springframework/session/spring-session-bom/Bean-RELEASE/spring-session-bom-Bean-RELEASE.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/springframework/session/spring-session-bom/Bean-RELEASE/spring-session-bom-Bean-RELEASE.pom (0 B at 0 B/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/springframework/boot/spring-boot-maven-plugin/2.1.0.RELEASE/spring-boot-maven-plugin-2.1.0.RELEASE.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/springframework/boot/spring-boot-maven-plugin/2.1.0.RELEASE/spring-boot-maven-plugin-2.1.0.RELEASE.jar (68 kB at 130 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-resources-plugin/3.1.0/maven-resources-plugin-3.1.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-resources-plugin/3.1.0/maven-resources-plugin-3.1.0.pom (7.2 kB at 21 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-plugins/31/maven-plugins-31.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-plugins/31/maven-plugins-31.pom (10 kB at 30 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-parent/31/maven-parent-31.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-parent/31/maven-parent-31.pom (43 kB at 121 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/apache/19/apache-19.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/apache/19/apache-19.pom (15 kB at 44 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-resources-plugin/3.1.0/maven-resources-plugin-3.1.0.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-resources-plugin/3.1.0/maven-resources-plugin-3.1.0.jar (32 kB at 89 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-compiler-plugin/3.8.0/maven-compiler-plugin-3.8.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-compiler-plugin/3.8.0/maven-compiler-plugin-3.8.0.pom (12 kB at 35 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-plugins/32/maven-plugins-32.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-plugins/32/maven-plugins-32.pom (11 kB at 29 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-parent/32/maven-parent-32.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-parent/32/maven-parent-32.pom (43 kB at 122 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/apache/20/apache-20.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/apache/20/apache-20.pom (16 kB at 45 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-compiler-plugin/3.8.0/maven-compiler-plugin-3.8.0.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-compiler-plugin/3.8.0/maven-compiler-plugin-3.8.0.jar (62 kB at 176 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-surefire-plugin/2.22.1/maven-surefire-plugin-2.22.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-surefire-plugin/2.22.1/maven-surefire-plugin-2.22.1.pom (5.0 kB at 14 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire/2.22.1/surefire-2.22.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire/2.22.1/surefire-2.22.1.pom (26 kB at 74 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-parent/33/maven-parent-33.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-parent/33/maven-parent-33.pom (44 kB at 127 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/apache/21/apache-21.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/apache/21/apache-21.pom (17 kB at 49 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-surefire-plugin/2.22.1/maven-surefire-plugin-2.22.1.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-surefire-plugin/2.22.1/maven-surefire-plugin-2.22.1.jar (41 kB at 118 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-jar-plugin/3.1.0/maven-jar-plugin-3.1.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-jar-plugin/3.1.0/maven-jar-plugin-3.1.0.pom (6.6 kB at 19 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-jar-plugin/3.1.0/maven-jar-plugin-3.1.0.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-jar-plugin/3.1.0/maven-jar-plugin-3.1.0.jar (27 kB at 76 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/boot/spring-boot-starter-web/2.1.0.RELEASE/spring-boot-starter-web-2.1.0.RELEASE.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/boot/spring-boot-starter-web/2.1.0.RELEASE/spring-boot-starter-web-2.1.0.RELEASE.pom (3.2 kB at 6.6 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/boot/spring-boot-starters/2.1.0.RELEASE/spring-boot-starters-2.1.0.RELEASE.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/boot/spring-boot-starters/2.1.0.RELEASE/spring-boot-starters-2.1.0.RELEASE.pom (1.8 kB at 2.7 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/boot/spring-boot-starter/2.1.0.RELEASE/spring-boot-starter-2.1.0.RELEASE.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/boot/spring-boot-starter/2.1.0.RELEASE/spring-boot-starter-2.1.0.RELEASE.pom (3.1 kB at 6.5 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/boot/spring-boot/2.1.0.RELEASE/spring-boot-2.1.0.RELEASE.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/boot/spring-boot/2.1.0.RELEASE/spring-boot-2.1.0.RELEASE.pom (14 kB at 28 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/spring-core/5.1.2.RELEASE/spring-core-5.1.2.RELEASE.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/spring-core/5.1.2.RELEASE/spring-core-5.1.2.RELEASE.pom (3.6 kB at 7.4 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/spring-jcl/5.1.2.RELEASE/spring-jcl-5.1.2.RELEASE.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/spring-jcl/5.1.2.RELEASE/spring-jcl-5.1.2.RELEASE.pom (1.9 kB at 4.1 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/spring-context/5.1.2.RELEASE/spring-context-5.1.2.RELEASE.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/spring-context/5.1.2.RELEASE/spring-context-5.1.2.RELEASE.pom (5.7 kB at 12 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/spring-aop/5.1.2.RELEASE/spring-aop-5.1.2.RELEASE.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/spring-aop/5.1.2.RELEASE/spring-aop-5.1.2.RELEASE.pom (2.5 kB at 5.2 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/spring-beans/5.1.2.RELEASE/spring-beans-5.1.2.RELEASE.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/spring-beans/5.1.2.RELEASE/spring-beans-5.1.2.RELEASE.pom (2.7 kB at 5.8 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/spring-expression/5.1.2.RELEASE/spring-expression-5.1.2.RELEASE.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/spring-expression/5.1.2.RELEASE/spring-expression-5.1.2.RELEASE.pom (1.7 kB at 3.6 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/boot/spring-boot-autoconfigure/2.1.0.RELEASE/spring-boot-autoconfigure-2.1.0.RELEASE.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/boot/spring-boot-autoconfigure/2.1.0.RELEASE/spring-boot-autoconfigure-2.1.0.RELEASE.pom (34 kB at 46 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/boot/spring-boot-starter-logging/2.1.0.RELEASE/spring-boot-starter-logging-2.1.0.RELEASE.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/boot/spring-boot-starter-logging/2.1.0.RELEASE/spring-boot-starter-logging-2.1.0.RELEASE.pom (2.5 kB at 5.3 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/ch/qos/logback/logback-classic/1.2.3/logback-classic-1.2.3.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/ch/qos/logback/logback-classic/1.2.3/logback-classic-1.2.3.pom
Downloaded from central: https://repo.maven.apache.org/maven2/ch/qos/logback/logback-classic/1.2.3/logback-classic-1.2.3.pom (13 kB at 38 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/ch/qos/logback/logback-parent/1.2.3/logback-parent-1.2.3.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/ch/qos/logback/logback-parent/1.2.3/logback-parent-1.2.3.pom
Downloaded from central: https://repo.maven.apache.org/maven2/ch/qos/logback/logback-parent/1.2.3/logback-parent-1.2.3.pom (18 kB at 50 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/ch/qos/logback/logback-core/1.2.3/logback-core-1.2.3.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/ch/qos/logback/logback-core/1.2.3/logback-core-1.2.3.pom
Downloaded from central: https://repo.maven.apache.org/maven2/ch/qos/logback/logback-core/1.2.3/logback-core-1.2.3.pom (4.2 kB at 12 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/slf4j/slf4j-api/1.7.25/slf4j-api-1.7.25.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/slf4j/slf4j-api/1.7.25/slf4j-api-1.7.25.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/slf4j/slf4j-api/1.7.25/slf4j-api-1.7.25.pom (3.8 kB at 11 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/slf4j/slf4j-parent/1.7.25/slf4j-parent-1.7.25.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/slf4j/slf4j-parent/1.7.25/slf4j-parent-1.7.25.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/slf4j/slf4j-parent/1.7.25/slf4j-parent-1.7.25.pom (14 kB at 39 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/apache/logging/log4j/log4j-to-slf4j/2.11.1/log4j-to-slf4j-2.11.1.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/logging/log4j/log4j-to-slf4j/2.11.1/log4j-to-slf4j-2.11.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/logging/log4j/log4j-to-slf4j/2.11.1/log4j-to-slf4j-2.11.1.pom (7.2 kB at 21 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/apache/logging/log4j/log4j/2.11.1/log4j-2.11.1.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/logging/log4j/log4j/2.11.1/log4j-2.11.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/logging/log4j/log4j/2.11.1/log4j-2.11.1.pom (59 kB at 171 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/apache/logging/log4j/log4j-api/2.11.1/log4j-api-2.11.1.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/logging/log4j/log4j-api/2.11.1/log4j-api-2.11.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/logging/log4j/log4j-api/2.11.1/log4j-api-2.11.1.pom (14 kB at 39 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/slf4j/jul-to-slf4j/1.7.25/jul-to-slf4j-1.7.25.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/slf4j/jul-to-slf4j/1.7.25/jul-to-slf4j-1.7.25.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/slf4j/jul-to-slf4j/1.7.25/jul-to-slf4j-1.7.25.pom (986 B at 2.8 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/javax/annotation/javax.annotation-api/1.3.2/javax.annotation-api-1.3.2.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/javax/annotation/javax.annotation-api/1.3.2/javax.annotation-api-1.3.2.pom
Downloaded from central: https://repo.maven.apache.org/maven2/javax/annotation/javax.annotation-api/1.3.2/javax.annotation-api-1.3.2.pom (14 kB at 41 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/net/java/jvnet-parent/3/jvnet-parent-3.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/net/java/jvnet-parent/3/jvnet-parent-3.pom
Downloaded from central: https://repo.maven.apache.org/maven2/net/java/jvnet-parent/3/jvnet-parent-3.pom (4.8 kB at 14 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/yaml/snakeyaml/1.23/snakeyaml-1.23.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/yaml/snakeyaml/1.23/snakeyaml-1.23.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/yaml/snakeyaml/1.23/snakeyaml-1.23.pom (38 kB at 109 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/boot/spring-boot-starter-json/2.1.0.RELEASE/spring-boot-starter-json-2.1.0.RELEASE.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/boot/spring-boot-starter-json/2.1.0.RELEASE/spring-boot-starter-json-2.1.0.RELEASE.pom (3.1 kB at 5.7 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/spring-web/5.1.2.RELEASE/spring-web-5.1.2.RELEASE.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/spring-web/5.1.2.RELEASE/spring-web-5.1.2.RELEASE.pom (12 kB at 22 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/com/fasterxml/jackson/core/jackson-databind/2.9.7/jackson-databind-2.9.7.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/core/jackson-databind/2.9.7/jackson-databind-2.9.7.pom
Downloaded from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/core/jackson-databind/2.9.7/jackson-databind-2.9.7.pom (6.3 kB at 18 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/com/fasterxml/jackson/jackson-base/2.9.7/jackson-base-2.9.7.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/jackson-base/2.9.7/jackson-base-2.9.7.pom
Downloaded from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/jackson-base/2.9.7/jackson-base-2.9.7.pom (5.4 kB at 15 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/com/fasterxml/jackson/core/jackson-annotations/2.9.0/jackson-annotations-2.9.0.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/core/jackson-annotations/2.9.0/jackson-annotations-2.9.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/core/jackson-annotations/2.9.0/jackson-annotations-2.9.0.pom (1.9 kB at 5.6 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/com/fasterxml/jackson/jackson-parent/2.9.0/jackson-parent-2.9.0.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/jackson-parent/2.9.0/jackson-parent-2.9.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/jackson-parent/2.9.0/jackson-parent-2.9.0.pom (7.8 kB at 21 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/com/fasterxml/oss-parent/28/oss-parent-28.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/com/fasterxml/oss-parent/28/oss-parent-28.pom
Downloaded from central: https://repo.maven.apache.org/maven2/com/fasterxml/oss-parent/28/oss-parent-28.pom (20 kB at 58 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/com/fasterxml/jackson/core/jackson-core/2.9.7/jackson-core-2.9.7.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/core/jackson-core/2.9.7/jackson-core-2.9.7.pom
Downloaded from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/core/jackson-core/2.9.7/jackson-core-2.9.7.pom (4.1 kB at 12 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/com/fasterxml/jackson/datatype/jackson-datatype-jdk8/2.9.7/jackson-datatype-jdk8-2.9.7.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/datatype/jackson-datatype-jdk8/2.9.7/jackson-datatype-jdk8-2.9.7.pom
Downloaded from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/datatype/jackson-datatype-jdk8/2.9.7/jackson-datatype-jdk8-2.9.7.pom (1.9 kB at 5.5 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/com/fasterxml/jackson/module/jackson-modules-java8/2.9.7/jackson-modules-java8-2.9.7.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/module/jackson-modules-java8/2.9.7/jackson-modules-java8-2.9.7.pom
Downloaded from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/module/jackson-modules-java8/2.9.7/jackson-modules-java8-2.9.7.pom (2.8 kB at 8.0 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/com/fasterxml/jackson/datatype/jackson-datatype-jsr310/2.9.7/jackson-datatype-jsr310-2.9.7.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/datatype/jackson-datatype-jsr310/2.9.7/jackson-datatype-jsr310-2.9.7.pom
Downloaded from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/datatype/jackson-datatype-jsr310/2.9.7/jackson-datatype-jsr310-2.9.7.pom (4.3 kB at 12 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/com/fasterxml/jackson/module/jackson-module-parameter-names/2.9.7/jackson-module-parameter-names-2.9.7.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/module/jackson-module-parameter-names/2.9.7/jackson-module-parameter-names-2.9.7.pom
Downloaded from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/module/jackson-module-parameter-names/2.9.7/jackson-module-parameter-names-2.9.7.pom (3.7 kB at 11 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/boot/spring-boot-starter-tomcat/2.1.0.RELEASE/spring-boot-starter-tomcat-2.1.0.RELEASE.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/boot/spring-boot-starter-tomcat/2.1.0.RELEASE/spring-boot-starter-tomcat-2.1.0.RELEASE.pom (3.0 kB at 6.1 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/apache/tomcat/embed/tomcat-embed-core/9.0.12/tomcat-embed-core-9.0.12.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/tomcat/embed/tomcat-embed-core/9.0.12/tomcat-embed-core-9.0.12.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/tomcat/embed/tomcat-embed-core/9.0.12/tomcat-embed-core-9.0.12.pom (1.6 kB at 4.5 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/apache/tomcat/embed/tomcat-embed-el/9.0.12/tomcat-embed-el-9.0.12.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/tomcat/embed/tomcat-embed-el/9.0.12/tomcat-embed-el-9.0.12.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/tomcat/embed/tomcat-embed-el/9.0.12/tomcat-embed-el-9.0.12.pom (1.3 kB at 3.9 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/apache/tomcat/embed/tomcat-embed-websocket/9.0.12/tomcat-embed-websocket-9.0.12.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/tomcat/embed/tomcat-embed-websocket/9.0.12/tomcat-embed-websocket-9.0.12.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/tomcat/embed/tomcat-embed-websocket/9.0.12/tomcat-embed-websocket-9.0.12.pom (1.6 kB at 4.6 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/apache/tomcat/tomcat-annotations-api/9.0.12/tomcat-annotations-api-9.0.12.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/tomcat/tomcat-annotations-api/9.0.12/tomcat-annotations-api-9.0.12.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/tomcat/tomcat-annotations-api/9.0.12/tomcat-annotations-api-9.0.12.pom (1.3 kB at 3.8 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/hibernate/validator/hibernate-validator/6.0.13.Final/hibernate-validator-6.0.13.Final.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/hibernate/validator/hibernate-validator/6.0.13.Final/hibernate-validator-6.0.13.Final.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/hibernate/validator/hibernate-validator/6.0.13.Final/hibernate-validator-6.0.13.Final.pom (15 kB at 42 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/hibernate/validator/hibernate-validator-parent/6.0.13.Final/hibernate-validator-parent-6.0.13.Final.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/hibernate/validator/hibernate-validator-parent/6.0.13.Final/hibernate-validator-parent-6.0.13.Final.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/hibernate/validator/hibernate-validator-parent/6.0.13.Final/hibernate-validator-parent-6.0.13.Final.pom (60 kB at 173 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/jboss/arquillian/arquillian-bom/1.1.11.Final/arquillian-bom-1.1.11.Final.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/jboss/arquillian/arquillian-bom/1.1.11.Final/arquillian-bom-1.1.11.Final.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/jboss/arquillian/arquillian-bom/1.1.11.Final/arquillian-bom-1.1.11.Final.pom (11 kB at 30 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/jboss/shrinkwrap/shrinkwrap-bom/1.2.3/shrinkwrap-bom-1.2.3.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/jboss/shrinkwrap/shrinkwrap-bom/1.2.3/shrinkwrap-bom-1.2.3.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/jboss/shrinkwrap/shrinkwrap-bom/1.2.3/shrinkwrap-bom-1.2.3.pom (4.0 kB at 12 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/jboss/shrinkwrap/resolver/shrinkwrap-resolver-bom/2.2.0/shrinkwrap-resolver-bom-2.2.0.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/jboss/shrinkwrap/resolver/shrinkwrap-resolver-bom/2.2.0/shrinkwrap-resolver-bom-2.2.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/jboss/shrinkwrap/resolver/shrinkwrap-resolver-bom/2.2.0/shrinkwrap-resolver-bom-2.2.0.pom (5.3 kB at 15 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/jboss/shrinkwrap/descriptors/shrinkwrap-descriptors-bom/2.0.0-alpha-8/shrinkwrap-descriptors-bom-2.0.0-alpha-8.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/jboss/shrinkwrap/descriptors/shrinkwrap-descriptors-bom/2.0.0-alpha-8/shrinkwrap-descriptors-bom-2.0.0-alpha-8.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/jboss/shrinkwrap/descriptors/shrinkwrap-descriptors-bom/2.0.0-alpha-8/shrinkwrap-descriptors-bom-2.0.0-alpha-8.pom (5.2 kB at 15 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/javax/validation/validation-api/2.0.1.Final/validation-api-2.0.1.Final.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/javax/validation/validation-api/2.0.1.Final/validation-api-2.0.1.Final.pom
Downloaded from central: https://repo.maven.apache.org/maven2/javax/validation/validation-api/2.0.1.Final/validation-api-2.0.1.Final.pom (12 kB at 34 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/jboss/logging/jboss-logging/3.3.2.Final/jboss-logging-3.3.2.Final.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/jboss/logging/jboss-logging/3.3.2.Final/jboss-logging-3.3.2.Final.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/jboss/logging/jboss-logging/3.3.2.Final/jboss-logging-3.3.2.Final.pom (6.4 kB at 18 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/jboss/jboss-parent/15/jboss-parent-15.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/jboss/jboss-parent/15/jboss-parent-15.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/jboss/jboss-parent/15/jboss-parent-15.pom (32 kB at 89 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/com/fasterxml/classmate/1.4.0/classmate-1.4.0.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/com/fasterxml/classmate/1.4.0/classmate-1.4.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/com/fasterxml/classmate/1.4.0/classmate-1.4.0.pom (5.9 kB at 17 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/com/fasterxml/oss-parent/24/oss-parent-24.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/com/fasterxml/oss-parent/24/oss-parent-24.pom
Downloaded from central: https://repo.maven.apache.org/maven2/com/fasterxml/oss-parent/24/oss-parent-24.pom (19 kB at 56 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/spring-webmvc/5.1.2.RELEASE/spring-webmvc-5.1.2.RELEASE.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/spring-webmvc/5.1.2.RELEASE/spring-webmvc-5.1.2.RELEASE.pom (9.4 kB at 17 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-function-web/2.0.0.RC2/spring-cloud-function-web-2.0.0.RC2.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-function-web/2.0.0.RC2/spring-cloud-function-web-2.0.0.RC2.pom (5.5 kB at 11 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-function-context/2.0.0.RC2/spring-cloud-function-context-2.0.0.RC2.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-function-context/2.0.0.RC2/spring-cloud-function-context-2.0.0.RC2.pom (5.8 kB at 11 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-function-core/2.0.0.RC2/spring-cloud-function-core-2.0.0.RC2.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-function-core/2.0.0.RC2/spring-cloud-function-core-2.0.0.RC2.pom (4.6 kB at 8.2 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/io/projectreactor/reactor-core/3.2.2.RELEASE/reactor-core-3.2.2.RELEASE.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/io/projectreactor/reactor-core/3.2.2.RELEASE/reactor-core-3.2.2.RELEASE.pom
Downloaded from central: https://repo.maven.apache.org/maven2/io/projectreactor/reactor-core/3.2.2.RELEASE/reactor-core-3.2.2.RELEASE.pom (3.1 kB at 8.8 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/reactivestreams/reactive-streams/1.0.2/reactive-streams-1.0.2.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/reactivestreams/reactive-streams/1.0.2/reactive-streams-1.0.2.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/reactivestreams/reactive-streams/1.0.2/reactive-streams-1.0.2.pom (1.2 kB at 3.3 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/spring-messaging/5.1.2.RELEASE/spring-messaging-5.1.2.RELEASE.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/spring-messaging/5.1.2.RELEASE/spring-messaging-5.1.2.RELEASE.pom (3.0 kB at 6.1 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/boot/spring-boot-starter-test/2.1.0.RELEASE/spring-boot-starter-test-2.1.0.RELEASE.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/boot/spring-boot-starter-test/2.1.0.RELEASE/spring-boot-starter-test-2.1.0.RELEASE.pom (4.4 kB at 8.9 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/boot/spring-boot-test/2.1.0.RELEASE/spring-boot-test-2.1.0.RELEASE.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/boot/spring-boot-test/2.1.0.RELEASE/spring-boot-test-2.1.0.RELEASE.pom (7.1 kB at 15 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/boot/spring-boot-test-autoconfigure/2.1.0.RELEASE/spring-boot-test-autoconfigure-2.1.0.RELEASE.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/boot/spring-boot-test-autoconfigure/2.1.0.RELEASE/spring-boot-test-autoconfigure-2.1.0.RELEASE.pom (9.9 kB at 19 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/com/jayway/jsonpath/json-path/2.4.0/json-path-2.4.0.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/com/jayway/jsonpath/json-path/2.4.0/json-path-2.4.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/com/jayway/jsonpath/json-path/2.4.0/json-path-2.4.0.pom (2.6 kB at 7.6 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/net/minidev/json-smart/2.3/json-smart-2.3.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/net/minidev/json-smart/2.3/json-smart-2.3.pom
Downloaded from central: https://repo.maven.apache.org/maven2/net/minidev/json-smart/2.3/json-smart-2.3.pom (9.0 kB at 26 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/net/minidev/minidev-parent/2.3/minidev-parent-2.3.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/net/minidev/minidev-parent/2.3/minidev-parent-2.3.pom
Downloaded from central: https://repo.maven.apache.org/maven2/net/minidev/minidev-parent/2.3/minidev-parent-2.3.pom (8.5 kB at 24 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/net/minidev/accessors-smart/1.2/accessors-smart-1.2.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/net/minidev/accessors-smart/1.2/accessors-smart-1.2.pom
Downloaded from central: https://repo.maven.apache.org/maven2/net/minidev/accessors-smart/1.2/accessors-smart-1.2.pom (12 kB at 34 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/ow2/asm/asm/5.0.4/asm-5.0.4.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm/5.0.4/asm-5.0.4.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm/5.0.4/asm-5.0.4.pom (1.9 kB at 5.6 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/ow2/asm/asm-parent/5.0.4/asm-parent-5.0.4.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-parent/5.0.4/asm-parent-5.0.4.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-parent/5.0.4/asm-parent-5.0.4.pom (5.5 kB at 16 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/ow2/ow2/1.3/ow2-1.3.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/ow2/ow2/1.3/ow2-1.3.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/ow2/ow2/1.3/ow2-1.3.pom (9.5 kB at 28 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/junit/junit/4.12/junit-4.12.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/junit/junit/4.12/junit-4.12.pom
Downloaded from central: https://repo.maven.apache.org/maven2/junit/junit/4.12/junit-4.12.pom (24 kB at 69 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/hamcrest/hamcrest-core/1.3/hamcrest-core-1.3.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/hamcrest/hamcrest-core/1.3/hamcrest-core-1.3.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/hamcrest/hamcrest-core/1.3/hamcrest-core-1.3.pom (766 B at 2.2 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/hamcrest/hamcrest-parent/1.3/hamcrest-parent-1.3.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/hamcrest/hamcrest-parent/1.3/hamcrest-parent-1.3.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/hamcrest/hamcrest-parent/1.3/hamcrest-parent-1.3.pom (2.0 kB at 5.7 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/assertj/assertj-core/3.11.1/assertj-core-3.11.1.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/assertj/assertj-core/3.11.1/assertj-core-3.11.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/assertj/assertj-core/3.11.1/assertj-core-3.11.1.pom (14 kB at 39 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/assertj/assertj-parent-pom/2.2.1/assertj-parent-pom-2.2.1.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/assertj/assertj-parent-pom/2.2.1/assertj-parent-pom-2.2.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/assertj/assertj-parent-pom/2.2.1/assertj-parent-pom-2.2.1.pom (15 kB at 44 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/junit/junit-bom/5.2.0/junit-bom-5.2.0.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/junit/junit-bom/5.2.0/junit-bom-5.2.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/junit/junit-bom/5.2.0/junit-bom-5.2.0.pom (4.2 kB at 12 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/mockito/mockito-core/2.23.0/mockito-core-2.23.0.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/mockito/mockito-core/2.23.0/mockito-core-2.23.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/mockito/mockito-core/2.23.0/mockito-core-2.23.0.pom (17 kB at 48 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/net/bytebuddy/byte-buddy/1.9.3/byte-buddy-1.9.3.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/net/bytebuddy/byte-buddy/1.9.3/byte-buddy-1.9.3.pom
Downloaded from central: https://repo.maven.apache.org/maven2/net/bytebuddy/byte-buddy/1.9.3/byte-buddy-1.9.3.pom (10 kB at 29 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/net/bytebuddy/byte-buddy-parent/1.9.3/byte-buddy-parent-1.9.3.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/net/bytebuddy/byte-buddy-parent/1.9.3/byte-buddy-parent-1.9.3.pom
Downloaded from central: https://repo.maven.apache.org/maven2/net/bytebuddy/byte-buddy-parent/1.9.3/byte-buddy-parent-1.9.3.pom (34 kB at 98 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/net/bytebuddy/byte-buddy-agent/1.9.3/byte-buddy-agent-1.9.3.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/net/bytebuddy/byte-buddy-agent/1.9.3/byte-buddy-agent-1.9.3.pom
Downloaded from central: https://repo.maven.apache.org/maven2/net/bytebuddy/byte-buddy-agent/1.9.3/byte-buddy-agent-1.9.3.pom (6.0 kB at 17 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/objenesis/objenesis/2.6/objenesis-2.6.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/objenesis/objenesis/2.6/objenesis-2.6.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/objenesis/objenesis/2.6/objenesis-2.6.pom (2.8 kB at 8.0 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/objenesis/objenesis-parent/2.6/objenesis-parent-2.6.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/objenesis/objenesis-parent/2.6/objenesis-parent-2.6.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/objenesis/objenesis-parent/2.6/objenesis-parent-2.6.pom (17 kB at 48 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/hamcrest/hamcrest-library/1.3/hamcrest-library-1.3.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/hamcrest/hamcrest-library/1.3/hamcrest-library-1.3.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/hamcrest/hamcrest-library/1.3/hamcrest-library-1.3.pom (820 B at 2.4 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/skyscreamer/jsonassert/1.5.0/jsonassert-1.5.0.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/skyscreamer/jsonassert/1.5.0/jsonassert-1.5.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/skyscreamer/jsonassert/1.5.0/jsonassert-1.5.0.pom (5.2 kB at 15 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/com/vaadin/external/google/android-json/0.0.20131108.vaadin1/android-json-0.0.20131108.vaadin1.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/com/vaadin/external/google/android-json/0.0.20131108.vaadin1/android-json-0.0.20131108.vaadin1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/com/vaadin/external/google/android-json/0.0.20131108.vaadin1/android-json-0.0.20131108.vaadin1.pom (2.8 kB at 8.1 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/spring-test/5.1.2.RELEASE/spring-test-5.1.2.RELEASE.pom
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/spring-test/5.1.2.RELEASE/spring-test-5.1.2.RELEASE.pom (9.9 kB at 20 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/xmlunit/xmlunit-core/2.6.2/xmlunit-core-2.6.2.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/xmlunit/xmlunit-core/2.6.2/xmlunit-core-2.6.2.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/xmlunit/xmlunit-core/2.6.2/xmlunit-core-2.6.2.pom (2.7 kB at 7.8 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/xmlunit/xmlunit-parent/2.6.2/xmlunit-parent-2.6.2.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/xmlunit/xmlunit-parent/2.6.2/xmlunit-parent-2.6.2.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/xmlunit/xmlunit-parent/2.6.2/xmlunit-parent-2.6.2.pom (18 kB at 52 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/javax/xml/bind/jaxb-api/2.3.1/jaxb-api-2.3.1.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/javax/xml/bind/jaxb-api/2.3.1/jaxb-api-2.3.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/javax/xml/bind/jaxb-api/2.3.1/jaxb-api-2.3.1.pom (20 kB at 58 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/javax/xml/bind/jaxb-api-parent/2.3.1/jaxb-api-parent-2.3.1.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/javax/xml/bind/jaxb-api-parent/2.3.1/jaxb-api-parent-2.3.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/javax/xml/bind/jaxb-api-parent/2.3.1/jaxb-api-parent-2.3.1.pom (8.1 kB at 23 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/net/java/jvnet-parent/5/jvnet-parent-5.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/net/java/jvnet-parent/5/jvnet-parent-5.pom
Downloaded from central: https://repo.maven.apache.org/maven2/net/java/jvnet-parent/5/jvnet-parent-5.pom (8.9 kB at 26 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/javax/activation/javax.activation-api/1.2.0/javax.activation-api-1.2.0.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/javax/activation/javax.activation-api/1.2.0/javax.activation-api-1.2.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/javax/activation/javax.activation-api/1.2.0/javax.activation-api-1.2.0.pom (4.9 kB at 14 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/com/sun/activation/all/1.2.0/all-1.2.0.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/com/sun/activation/all/1.2.0/all-1.2.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/com/sun/activation/all/1.2.0/all-1.2.0.pom (18 kB at 51 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/net/java/jvnet-parent/1/jvnet-parent-1.pom
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/net/java/jvnet-parent/1/jvnet-parent-1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/net/java/jvnet-parent/1/jvnet-parent-1.pom (4.7 kB at 14 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/boot/spring-boot-starter-web/2.1.0.RELEASE/spring-boot-starter-web-2.1.0.RELEASE.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/boot/spring-boot/2.1.0.RELEASE/spring-boot-2.1.0.RELEASE.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/boot/spring-boot-autoconfigure/2.1.0.RELEASE/spring-boot-autoconfigure-2.1.0.RELEASE.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/boot/spring-boot-starter/2.1.0.RELEASE/spring-boot-starter-2.1.0.RELEASE.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/boot/spring-boot-starter-logging/2.1.0.RELEASE/spring-boot-starter-logging-2.1.0.RELEASE.jar
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/boot/spring-boot-starter-logging/2.1.0.RELEASE/spring-boot-starter-logging-2.1.0.RELEASE.jar (423 B at 810 B/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/ch/qos/logback/logback-classic/1.2.3/logback-classic-1.2.3.jar
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/boot/spring-boot-starter/2.1.0.RELEASE/spring-boot-starter-2.1.0.RELEASE.jar (413 B at 760 B/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/ch/qos/logback/logback-core/1.2.3/logback-core-1.2.3.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/boot/spring-boot-starter-web/2.1.0.RELEASE/spring-boot-starter-web-2.1.0.RELEASE.jar (420 B at 772 B/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/apache/logging/log4j/log4j-to-slf4j/2.11.1/log4j-to-slf4j-2.11.1.jar
Downloading from spring-milestones: https://repo.spring.io/milestone/org/apache/logging/log4j/log4j-api/2.11.1/log4j-api-2.11.1.jar
Downloading from spring-milestones: https://repo.spring.io/milestone/org/slf4j/jul-to-slf4j/1.7.25/jul-to-slf4j-1.7.25.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/javax/annotation/javax.annotation-api/1.3.2/javax.annotation-api-1.3.2.jar
Downloading from spring-milestones: https://repo.spring.io/milestone/org/yaml/snakeyaml/1.23/snakeyaml-1.23.jar
Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/boot/spring-boot-starter-json/2.1.0.RELEASE/spring-boot-starter-json-2.1.0.RELEASE.jar
Downloading from spring-milestones: https://repo.spring.io/milestone/com/fasterxml/jackson/core/jackson-databind/2.9.7/jackson-databind-2.9.7.jar
Downloading from spring-milestones: https://repo.spring.io/milestone/com/fasterxml/jackson/core/jackson-annotations/2.9.0/jackson-annotations-2.9.0.jar
Downloading from spring-milestones: https://repo.spring.io/milestone/com/fasterxml/jackson/core/jackson-core/2.9.7/jackson-core-2.9.7.jar
Progress (3): 679/955 kB | 0.6/1.3 MB | 420 B-build]: Progress (3): 419/955 kB | 0.4/1.3 MB | 420 B
Downloading from spring-milestones: https://repo.spring.io/milestone/com/fasterxml/jackson/datatype/jackson-datatype-jdk8/2.9.7/jackson-datatype-jdk8-2.9.7.jar
Downloading from spring-milestones: https://repo.spring.io/milestone/com/fasterxml/jackson/datatype/jackson-datatype-jsr310/2.9.7/jackson-datatype-jsr310-2.9.7.jar
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/boot/spring-boot/2.1.0.RELEASE/spring-boot-2.1.0.RELEASE.jar (955 kB at 526 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/com/fasterxml/jackson/module/jackson-module-parameter-names/2.9.7/jackson-module-parameter-names-2.9.7.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/boot/spring-boot-starter-tomcat/2.1.0.RELEASE/spring-boot-starter-tomcat-2.1.0.RELEASE.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/apache/tomcat/embed/tomcat-embed-core/9.0.12/tomcat-embed-core-9.0.12.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/boot/spring-boot-autoconfigure/2.1.0.RELEASE/spring-boot-autoconfigure-2.1.0.RELEASE.jar (1.3 MB at 653 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/apache/tomcat/embed/tomcat-embed-el/9.0.12/tomcat-embed-el-9.0.12.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/apache/tomcat/embed/tomcat-embed-websocket/9.0.12/tomcat-embed-websocket-9.0.12.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/hibernate/validator/hibernate-validator/6.0.13.Final/hibernate-validator-6.0.13.Final.jar
Downloading from spring-milestones: https://repo.spring.io/milestone/javax/validation/validation-api/2.0.1.Final/validation-api-2.0.1.Final.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/boot/spring-boot-starter-tomcat/2.1.0.RELEASE/spring-boot-starter-tomcat-2.1.0.RELEASE.jar (422 B at 184 B/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/jboss/logging/jboss-logging/3.3.2.Final/jboss-logging-3.3.2.Final.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/com/fasterxml/classmate/1.4.0/classmate-1.4.0.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/spring-web/5.1.2.RELEASE/spring-web-5.1.2.RELEASE.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/spring-beans/5.1.2.RELEASE/spring-beans-5.1.2.RELEASE.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/spring-webmvc/5.1.2.RELEASE/spring-webmvc-5.1.2.RELEASE.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/spring-aop/5.1.2.RELEASE/spring-aop-5.1.2.RELEASE.jar
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/boot/spring-boot-starter-json/2.1.0.RELEASE/spring-boot-starter-json-2.1.0.RELEASE.jar (420 B at 162 B/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/spring-context/5.1.2.RELEASE/spring-context-5.1.2.RELEASE.jar
Progress (5): 0.1/1.4 MB | 73/671 kB | 52/799 kB | 37/369 kB | 0.1/1.1 MB MB
Progress (5): 0.2/1.4 MB | 139/671 kB | 96/799 kB | 66/369 kB | 0.1/1.1 MB8/369 kB | 0.1/1.1 MB
Progress (5): 0.3/1.4 MB | 207/671 kB | 137/799 kB | 103/369 kB | 0.2/1.1 MB kB | 96/799 kB | 66/369 kB | 0.1/1.1 MB
Progress (5): 0.3/1.4 MB | 278/671 kB | 180/799 kB | 140/369 kB | 0.3/1.1 MB 208/671 kB | 137/799 kB | 103/369 kB | 0.2/1.1 MB
Progress (5): 0.4/1.4 MB | 348/671 kB | 226/799 kB | 177/369 kB | 0.3/1.1 MB
Progress (5): 0.5/1.4 MB | 417/671 kB | 264/799 kB | 208/369 kB | 0.4/1.1 MB/1.1 MB
Progress (5): 0.6/1.4 MB | 492/671 kB | 325/799 kB | 245/369 kB | 0.5/1.1 MB 209/369 kB | 0.4/1.1 MB
Progress (5): 0.7/1.4 MB | 566/671 kB | 378/799 kB | 279/369 kB | 0.5/1.1 MB | 246/369 kB | 0.5/1.1 MB
Progress (5): 0.8/1.4 MB | 602/671 kB | 432/799 kB | 328/369 kB | 0.6/1.1 MB1 kB | 378/799 kB | 279/369 kB | 0.5/1.1 MB
Progress (5): 0.8/1.4 MB | 671 kB | 500/799 kB | 369 kB | 0.7/1.1 MB
Progress (5): 0.9/1.4 MB | 671 kB | 602/799 kB | 369 kB | 0.8/1.1 MB71 kB | 500/799 kB | 369 kB | 0.7/1.1 MB
Progress (5): 1.0/1.4 MB | 671 kB | 705/799 kB | 369 kB | 0.9/1.1 MB.8/1.1 MB
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/spring-aop/5.1.2.RELEASE/spring-aop-5.1.2.RELEASE.jar (369 kB at 90 kB/s)
Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/spring-expression/5.1.2.RELEASE/spring-expression-5.1.2.RELEASE.jar
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/spring-beans/5.1.2.RELEASE/spring-beans-5.1.2.RELEASE.jar (671 kB at 164 kB/s)
Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-function-web/2.0.0.RC2/spring-cloud-function-web-2.0.0.RC2.jar
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/spring-webmvc/5.1.2.RELEASE/spring-webmvc-5.1.2.RELEASE.jar (799 kB at 185 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-function-context/2.0.0.RC2/spring-cloud-function-context-2.0.0.RC2.jar
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/spring-context/5.1.2.RELEASE/spring-context-5.1.2.RELEASE.jar (1.1 MB at 253 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-function-core/2.0.0.RC2/spring-cloud-function-core-2.0.0.RC2.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/spring-web/5.1.2.RELEASE/spring-web-5.1.2.RELEASE.jar (1.4 MB at 317 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/io/projectreactor/reactor-core/3.2.2.RELEASE/reactor-core-3.2.2.RELEASE.jar
Downloading from spring-milestones: https://repo.spring.io/milestone/org/reactivestreams/reactive-streams/1.0.2/reactive-streams-1.0.2.jar
Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/spring-messaging/5.1.2.RELEASE/spring-messaging-5.1.2.RELEASE.jar
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-function-web/2.0.0.RC2/spring-cloud-function-web-2.0.0.RC2.jar (64 kB at 13 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/boot/spring-boot-starter-test/2.1.0.RELEASE/spring-boot-starter-test-2.1.0.RELEASE.jar
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-function-context/2.0.0.RC2/spring-cloud-function-context-2.0.0.RC2.jar (68 kB at 13 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/boot/spring-boot-test/2.1.0.RELEASE/spring-boot-test-2.1.0.RELEASE.jar
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/spring-expression/5.1.2.RELEASE/spring-expression-5.1.2.RELEASE.jar (280 kB at 51 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/boot/spring-boot-test-autoconfigure/2.1.0.RELEASE/spring-boot-test-autoconfigure-2.1.0.RELEASE.jar
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/boot/spring-boot-starter-test/2.1.0.RELEASE/spring-boot-starter-test-2.1.0.RELEASE.jar (419 B at 75 B/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/com/jayway/jsonpath/json-path/2.4.0/json-path-2.4.0.jar
Downloading from spring-milestones: https://repo.spring.io/milestone/net/minidev/json-smart/2.3/json-smart-2.3.jar
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/cloud/spring-cloud-function-core/2.0.0.RC2/spring-cloud-function-core-2.0.0.RC2.jar (13 kB at 2.2 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/net/minidev/accessors-smart/1.2/accessors-smart-1.2.jar
Downloading from spring-milestones: https://repo.spring.io/milestone/org/ow2/asm/asm/5.0.4/asm-5.0.4.jar
Downloading from spring-milestones: https://repo.spring.io/milestone/org/slf4j/slf4j-api/1.7.25/slf4j-api-1.7.25.jar
Downloading from spring-milestones: https://repo.spring.io/milestone/junit/junit/4.12/junit-4.12.jar
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/spring-messaging/5.1.2.RELEASE/spring-messaging-5.1.2.RELEASE.jar (383 kB at 60 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/assertj/assertj-core/3.11.1/assertj-core-3.11.1.jar
Downloading from spring-milestones: https://repo.spring.io/milestone/org/mockito/mockito-core/2.23.0/mockito-core-2.23.0.jar
Downloading from spring-milestones: https://repo.spring.io/milestone/net/bytebuddy/byte-buddy/1.9.3/byte-buddy-1.9.3.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/boot/spring-boot-test/2.1.0.RELEASE/spring-boot-test-2.1.0.RELEASE.jar (198 kB at 30 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/net/bytebuddy/byte-buddy-agent/1.9.3/byte-buddy-agent-1.9.3.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/objenesis/objenesis/2.6/objenesis-2.6.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/boot/spring-boot-test-autoconfigure/2.1.0.RELEASE/spring-boot-test-autoconfigure-2.1.0.RELEASE.jar (175 kB at 26 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/hamcrest/hamcrest-core/1.3/hamcrest-core-1.3.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/hamcrest/hamcrest-library/1.3/hamcrest-library-1.3.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/skyscreamer/jsonassert/1.5.0/jsonassert-1.5.0.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/com/vaadin/external/google/android-json/0.0.20131108.vaadin1/android-json-0.0.20131108.vaadin1.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/spring-core/5.1.2.RELEASE/spring-core-5.1.2.RELEASE.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/spring-jcl/5.1.2.RELEASE/spring-jcl-5.1.2.RELEASE.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/springframework/spring-test/5.1.2.RELEASE/spring-test-5.1.2.RELEASE.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/org/xmlunit/xmlunit-core/2.6.2/xmlunit-core-2.6.2.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from spring-milestones: https://repo.spring.io/milestone/javax/xml/bind/jaxb-api/2.3.1/jaxb-api-2.3.1.jar
Downloading from spring-milestones: https://repo.spring.io/milestone/javax/activation/javax.activation-api/1.2.0/javax.activation-api-1.2.0.jar
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/spring-jcl/5.1.2.RELEASE/spring-jcl-5.1.2.RELEASE.jar (24 kB at 3.2 kB/s)
Progress (2): 0.4/1.3 MB | 306/619 kBild-step-build]: Progress (2): 0.1/1.3 MB | 44/619 kB
Progress (2): 0.7/1.3 MB | 581/619 kBild-step-build]:  306/619 kB
Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/spring-test/5.1.2.RELEASE/spring-test-5.1.2.RELEASE.jar (619 kB at 72 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from spring-milestones: https://repo.spring.io/milestone/org/springframework/spring-core/5.1.2.RELEASE/spring-core-5.1.2.RELEASE.jar (1.3 MB at 148 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/ch/qos/logback/logback-classic/1.2.3/logback-classic-1.2.3.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/ch/qos/logback/logback-core/1.2.3/logback-core-1.2.3.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/logging/log4j/log4j-to-slf4j/2.11.1/log4j-to-slf4j-2.11.1.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/slf4j/jul-to-slf4j/1.7.25/jul-to-slf4j-1.7.25.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/logging/log4j/log4j-api/2.11.1/log4j-api-2.11.1.jar
Downloaded from central: https://repo.maven.apache.org/maven2/ch/qos/logback/logback-classic/1.2.3/logback-classic-1.2.3.jar (290 kB at 495 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/javax/annotation/javax.annotation-api/1.3.2/javax.annotation-api-1.3.2.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/slf4j/jul-to-slf4j/1.7.25/jul-to-slf4j-1.7.25.jar (4.6 kB at 5.1 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/yaml/snakeyaml/1.23/snakeyaml-1.23.jar
Downloaded from central: https://repo.maven.apache.org/maven2/javax/annotation/javax.annotation-api/1.3.2/javax.annotation-api-1.3.2.jar (27 kB at 29 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/core/jackson-databind/2.9.7/jackson-databind-2.9.7.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/logging/log4j/log4j-to-slf4j/2.11.1/log4j-to-slf4j-2.11.1.jar (18 kB at 16 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/core/jackson-annotations/2.9.0/jackson-annotations-2.9.0.jar
Progress (5): 196/472 kB | 196/264 kB | 32/301 kB | 0.7/1.4 MB | 32/67 kB  kB | 81/264 kB | 13/301 kB | 0/1.4 MB
Progress (5): 409/472 kB | 264 kB | 81/301 kB | 1.3/1.4 MB | 67 kB       64 kB | 32/301 kB | 0.7/1.4 MB | 32/67 kB
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/logging/log4j/log4j-api/2.11.1/log4j-api-2.11.1.jar (264 kB at 173 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/core/jackson-core/2.9.7/jackson-core-2.9.7.jar
Downloaded from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/core/jackson-annotations/2.9.0/jackson-annotations-2.9.0.jar (67 kB at 42 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/datatype/jackson-datatype-jdk8/2.9.7/jackson-datatype-jdk8-2.9.7.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/core/jackson-databind/2.9.7/jackson-databind-2.9.7.jar (1.4 MB at 827 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/datatype/jackson-datatype-jsr310/2.9.7/jackson-datatype-jsr310-2.9.7.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/ch/qos/logback/logback-core/1.2.3/logback-core-1.2.3.jar (472 kB at 282 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/module/jackson-module-parameter-names/2.9.7/jackson-module-parameter-names-2.9.7.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/yaml/snakeyaml/1.23/snakeyaml-1.23.jar (301 kB at 160 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/tomcat/embed/tomcat-embed-core/9.0.12/tomcat-embed-core-9.0.12.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/datatype/jackson-datatype-jdk8/2.9.7/jackson-datatype-jdk8-2.9.7.jar (33 kB at 17 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/tomcat/embed/tomcat-embed-el/9.0.12/tomcat-embed-el-9.0.12.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/module/jackson-module-parameter-names/2.9.7/jackson-module-parameter-names-2.9.7.jar (8.6 kB at 4.4 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/tomcat/embed/tomcat-embed-websocket/9.0.12/tomcat-embed-websocket-9.0.12.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/datatype/jackson-datatype-jsr310/2.9.7/jackson-datatype-jsr310-2.9.7.jar (100 kB at 50 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/hibernate/validator/hibernate-validator/6.0.13.Final/hibernate-validator-6.0.13.Final.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/core/jackson-core/2.9.7/jackson-core-2.9.7.jar (324 kB at 162 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/javax/validation/validation-api/2.0.1.Final/validation-api-2.0.1.Final.jar
Progress (5): 0.2/3.2 MB | 49/250 kB | 263 kB | 0.6/1.2 MB | 93 kB    3.2 MB
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/tomcat/embed/tomcat-embed-websocket/9.0.12/tomcat-embed-websocket-9.0.12.jar (263 kB at 113 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/jboss/logging/jboss-logging/3.3.2.Final/jboss-logging-3.3.2.Final.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/javax/validation/validation-api/2.0.1.Final/validation-api-2.0.1.Final.jar (93 kB at 40 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/com/fasterxml/classmate/1.4.0/classmate-1.4.0.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/hibernate/validator/hibernate-validator/6.0.13.Final/hibernate-validator-6.0.13.Final.jar (1.2 MB at 474 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/io/projectreactor/reactor-core/3.2.2.RELEASE/reactor-core-3.2.2.RELEASE.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/tomcat/embed/tomcat-embed-el/9.0.12/tomcat-embed-el-9.0.12.jar (250 kB at 96 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/reactivestreams/reactive-streams/1.0.2/reactive-streams-1.0.2.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/jboss/logging/jboss-logging/3.3.2.Final/jboss-logging-3.3.2.Final.jar (66 kB at 25 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/com/jayway/jsonpath/json-path/2.4.0/json-path-2.4.0.jar
Downloaded from central: https://repo.maven.apache.org/maven2/com/fasterxml/classmate/1.4.0/classmate-1.4.0.jar (67 kB at 25 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/net/minidev/json-smart/2.3/json-smart-2.3.jar
Progress (5): 2.6/3.2 MB | 1.4 MB | 2.1 kB | 223 kB | 16/120 kB 2): 1.9/3.2 MB | 0.7/1.4 MB
Downloaded from central: https://repo.maven.apache.org/maven2/io/projectreactor/reactor-core/3.2.2.RELEASE/reactor-core-3.2.2.RELEASE.jar (1.4 MB at 500 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/net/minidev/accessors-smart/1.2/accessors-smart-1.2.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/reactivestreams/reactive-streams/1.0.2/reactive-streams-1.0.2.jar (2.1 kB at 709 B/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm/5.0.4/asm-5.0.4.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/com/jayway/jsonpath/json-path/2.4.0/json-path-2.4.0.jar (223 kB at 75 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/slf4j/slf4j-api/1.7.25/slf4j-api-1.7.25.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/net/minidev/json-smart/2.3/json-smart-2.3.jar (120 kB at 40 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/junit/junit/4.12/junit-4.12.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/tomcat/embed/tomcat-embed-core/9.0.12/tomcat-embed-core-9.0.12.jar (3.2 MB at 1.0 MB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/assertj/assertj-core/3.11.1/assertj-core-3.11.1.jar
Downloaded from central: https://repo.maven.apache.org/maven2/net/minidev/accessors-smart/1.2/accessors-smart-1.2.jar (30 kB at 9.3 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/mockito/mockito-core/2.23.0/mockito-core-2.23.0.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm/5.0.4/asm-5.0.4.jar (53 kB at 16 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/net/bytebuddy/byte-buddy/1.9.3/byte-buddy-1.9.3.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/slf4j/slf4j-api/1.7.25/slf4j-api-1.7.25.jar (41 kB at 12 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/net/bytebuddy/byte-buddy-agent/1.9.3/byte-buddy-agent-1.9.3.jar
Downloaded from central: https://repo.maven.apache.org/maven2/junit/junit/4.12/junit-4.12.jar (315 kB at 94 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/objenesis/objenesis/2.6/objenesis-2.6.jar
Progress (2): 3.4/4.1 MB | 565 kB    ild-step-build]: Progress (1): 1.9/4.1 MB
Downloaded from central: https://repo.maven.apache.org/maven2/org/mockito/mockito-core/2.23.0/mockito-core-2.23.0.jar (565 kB at 157 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/hamcrest/hamcrest-core/1.3/hamcrest-core-1.3.jar
Downloaded from central: https://repo.maven.apache.org/maven2/net/bytebuddy/byte-buddy-agent/1.9.3/byte-buddy-agent-1.9.3.jar (43 kB at 12 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/hamcrest/hamcrest-library/1.3/hamcrest-library-1.3.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/assertj/assertj-core/3.11.1/assertj-core-3.11.1.jar (4.1 MB at 1.1 MB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/skyscreamer/jsonassert/1.5.0/jsonassert-1.5.0.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/objenesis/objenesis/2.6/objenesis-2.6.jar (56 kB at 15 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/com/vaadin/external/google/android-json/0.0.20131108.vaadin1/android-json-0.0.20131108.vaadin1.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/hamcrest/hamcrest-core/1.3/hamcrest-core-1.3.jar (45 kB at 11 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/xmlunit/xmlunit-core/2.6.2/xmlunit-core-2.6.2.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/hamcrest/hamcrest-library/1.3/hamcrest-library-1.3.jar (53 kB at 13 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/javax/xml/bind/jaxb-api/2.3.1/jaxb-api-2.3.1.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/skyscreamer/jsonassert/1.5.0/jsonassert-1.5.0.jar (30 kB at 7.6 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/javax/activation/javax.activation-api/1.2.0/javax.activation-api-1.2.0.jar
Downloaded from central: https://repo.maven.apache.org/maven2/com/vaadin/external/google/android-json/0.0.20131108.vaadin1/android-json-0.0.20131108.vaadin1.jar (18 kB at 4.6 kB/s)
Progress (4): 3.2/3.2 MB | 168 kB | 128 kB | 57 kB    Progress (1): 1.8/3.2 MB
Downloaded from central: https://repo.maven.apache.org/maven2/org/xmlunit/xmlunit-core/2.6.2/xmlunit-core-2.6.2.jar (168 kB at 39 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/javax/xml/bind/jaxb-api/2.3.1/jaxb-api-2.3.1.jar (128 kB at 30 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/javax/activation/javax.activation-api/1.2.0/javax.activation-api-1.2.0.jar (57 kB at 13 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/net/bytebuddy/byte-buddy/1.9.3/byte-buddy-1.9.3.jar (3.2 MB at 741 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: [INFO]
default/uppercase-btpf4-pod-d4639b[build-step-build]: [INFO] --- maven-resources-plugin:3.1.0:resources (default-resources) @ uppercase ---
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-plugin-api/3.0/maven-plugin-api-3.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-plugin-api/3.0/maven-plugin-api-3.0.pom (2.3 kB at 6.7 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven/3.0/maven-3.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven/3.0/maven-3.0.pom (22 kB at 62 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-parent/15/maven-parent-15.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-parent/15/maven-parent-15.pom (24 kB at 70 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/apache/6/apache-6.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/apache/6/apache-6.pom (13 kB at 37 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-model/3.0/maven-model-3.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-model/3.0/maven-model-3.0.pom (3.9 kB at 11 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/2.0.4/plexus-utils-2.0.4.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/2.0.4/plexus-utils-2.0.4.pom (3.3 kB at 9.7 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus/2.0.6/plexus-2.0.6.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus/2.0.6/plexus-2.0.6.pom (17 kB at 49 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-artifact/3.0/maven-artifact-3.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-artifact/3.0/maven-artifact-3.0.pom (1.9 kB at 5.6 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/sonatype/sisu/sisu-inject-plexus/1.4.2/sisu-inject-plexus-1.4.2.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/sonatype/sisu/sisu-inject-plexus/1.4.2/sisu-inject-plexus-1.4.2.pom (5.4 kB at 16 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/sonatype/sisu/inject/guice-plexus/1.4.2/guice-plexus-1.4.2.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/sonatype/sisu/inject/guice-plexus/1.4.2/guice-plexus-1.4.2.pom (3.1 kB at 9.1 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/sonatype/sisu/inject/guice-bean/1.4.2/guice-bean-1.4.2.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/sonatype/sisu/inject/guice-bean/1.4.2/guice-bean-1.4.2.pom (2.6 kB at 7.6 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/sonatype/sisu/sisu-inject/1.4.2/sisu-inject-1.4.2.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/sonatype/sisu/sisu-inject/1.4.2/sisu-inject-1.4.2.pom (1.2 kB at 3.7 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/sonatype/sisu/sisu-parent/1.4.2/sisu-parent-1.4.2.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/sonatype/sisu/sisu-parent/1.4.2/sisu-parent-1.4.2.pom (7.8 kB at 22 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/sonatype/forge/forge-parent/6/forge-parent-6.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/sonatype/forge/forge-parent/6/forge-parent-6.pom (11 kB at 30 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-component-annotations/1.7.1/plexus-component-annotations-1.7.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-component-annotations/1.7.1/plexus-component-annotations-1.7.1.pom (770 B at 2.3 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-containers/1.7.1/plexus-containers-1.7.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-containers/1.7.1/plexus-containers-1.7.1.pom (5.0 kB at 15 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus/4.0/plexus-4.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus/4.0/plexus-4.0.pom (22 kB at 62 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/sonatype/forge/forge-parent/10/forge-parent-10.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/sonatype/forge/forge-parent/10/forge-parent-10.pom (14 kB at 40 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-classworlds/2.2.3/plexus-classworlds-2.2.3.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-classworlds/2.2.3/plexus-classworlds-2.2.3.pom (4.0 kB at 12 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/2.0.5/plexus-utils-2.0.5.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/2.0.5/plexus-utils-2.0.5.pom (3.3 kB at 9.5 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/sonatype/sisu/sisu-inject-bean/1.4.2/sisu-inject-bean-1.4.2.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/sonatype/sisu/sisu-inject-bean/1.4.2/sisu-inject-bean-1.4.2.pom (5.5 kB at 16 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/sonatype/sisu/sisu-guice/2.1.7/sisu-guice-2.1.7.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/sonatype/sisu/sisu-guice/2.1.7/sisu-guice-2.1.7.pom (11 kB at 32 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-core/3.0/maven-core-3.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-core/3.0/maven-core-3.0.pom (6.6 kB at 19 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-settings/3.0/maven-settings-3.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-settings/3.0/maven-settings-3.0.pom (1.9 kB at 5.4 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-settings-builder/3.0/maven-settings-builder-3.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-settings-builder/3.0/maven-settings-builder-3.0.pom (2.2 kB at 6.5 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-interpolation/1.14/plexus-interpolation-1.14.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-interpolation/1.14/plexus-interpolation-1.14.pom (910 B at 2.6 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-components/1.1.18/plexus-components-1.1.18.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-components/1.1.18/plexus-components-1.1.18.pom (5.4 kB at 15 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus/2.0.7/plexus-2.0.7.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus/2.0.7/plexus-2.0.7.pom (17 kB at 51 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/sonatype/plexus/plexus-sec-dispatcher/1.3/plexus-sec-dispatcher-1.3.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/sonatype/plexus/plexus-sec-dispatcher/1.3/plexus-sec-dispatcher-1.3.pom (3.0 kB at 8.6 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/sonatype/spice/spice-parent/12/spice-parent-12.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/sonatype/spice/spice-parent/12/spice-parent-12.pom (6.8 kB at 20 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/sonatype/forge/forge-parent/4/forge-parent-4.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/sonatype/forge/forge-parent/4/forge-parent-4.pom (8.4 kB at 24 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/1.5.5/plexus-utils-1.5.5.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/1.5.5/plexus-utils-1.5.5.pom (5.1 kB at 15 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus/1.0.11/plexus-1.0.11.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus/1.0.11/plexus-1.0.11.pom (9.0 kB at 26 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/sonatype/plexus/plexus-cipher/1.4/plexus-cipher-1.4.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/sonatype/plexus/plexus-cipher/1.4/plexus-cipher-1.4.pom (2.1 kB at 6.0 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-repository-metadata/3.0/maven-repository-metadata-3.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-repository-metadata/3.0/maven-repository-metadata-3.0.pom (1.9 kB at 5.6 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-model-builder/3.0/maven-model-builder-3.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-model-builder/3.0/maven-model-builder-3.0.pom (2.2 kB at 6.6 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-aether-provider/3.0/maven-aether-provider-3.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-aether-provider/3.0/maven-aether-provider-3.0.pom (2.5 kB at 7.2 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/sonatype/aether/aether-api/1.7/aether-api-1.7.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/sonatype/aether/aether-api/1.7/aether-api-1.7.pom (1.7 kB at 4.8 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/sonatype/aether/aether-parent/1.7/aether-parent-1.7.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/sonatype/aether/aether-parent/1.7/aether-parent-1.7.pom (7.7 kB at 23 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/sonatype/aether/aether-util/1.7/aether-util-1.7.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/sonatype/aether/aether-util/1.7/aether-util-1.7.pom (2.1 kB at 5.9 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/sonatype/aether/aether-impl/1.7/aether-impl-1.7.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/sonatype/aether/aether-impl/1.7/aether-impl-1.7.pom (3.7 kB at 11 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/sonatype/aether/aether-spi/1.7/aether-spi-1.7.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/sonatype/aether/aether-spi/1.7/aether-spi-1.7.pom (1.7 kB at 5.1 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/3.1.0/plexus-utils-3.1.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/3.1.0/plexus-utils-3.1.0.pom (4.7 kB at 14 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-filtering/3.1.1/maven-filtering-3.1.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-filtering/3.1.1/maven-filtering-3.1.1.pom (5.7 kB at 17 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-components/30/maven-shared-components-30.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-components/30/maven-shared-components-30.pom (4.6 kB at 13 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-parent/30/maven-parent-30.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-parent/30/maven-parent-30.pom (41 kB at 121 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-utils/3.0.0/maven-shared-utils-3.0.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-utils/3.0.0/maven-shared-utils-3.0.0.pom (5.6 kB at 16 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-components/21/maven-shared-components-21.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-components/21/maven-shared-components-21.pom (5.1 kB at 15 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-parent/25/maven-parent-25.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-parent/25/maven-parent-25.pom (37 kB at 109 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/apache/15/apache-15.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/apache/15/apache-15.pom (15 kB at 45 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/commons-io/commons-io/2.4/commons-io-2.4.pom
Downloaded from central: https://repo.maven.apache.org/maven2/commons-io/commons-io/2.4/commons-io-2.4.pom (10 kB at 29 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-parent/25/commons-parent-25.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-parent/25/commons-parent-25.pom (48 kB at 141 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/apache/9/apache-9.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/apache/9/apache-9.pom (15 kB at 44 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/com/google/code/findbugs/jsr305/2.0.1/jsr305-2.0.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/com/google/code/findbugs/jsr305/2.0.1/jsr305-2.0.1.pom (965 B at 2.8 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/3.0.24/plexus-utils-3.0.24.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/3.0.24/plexus-utils-3.0.24.pom (4.1 kB at 12 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-interpolation/1.22/plexus-interpolation-1.22.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-interpolation/1.22/plexus-interpolation-1.22.pom (1.5 kB at 4.3 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-components/1.3.1/plexus-components-1.3.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-components/1.3.1/plexus-components-1.3.1.pom (3.1 kB at 8.9 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus/3.3.1/plexus-3.3.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus/3.3.1/plexus-3.3.1.pom (20 kB at 60 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/sonatype/spice/spice-parent/17/spice-parent-17.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/sonatype/spice/spice-parent/17/spice-parent-17.pom (6.8 kB at 20 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/sonatype/plexus/plexus-build-api/0.0.7/plexus-build-api-0.0.7.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/sonatype/plexus/plexus-build-api/0.0.7/plexus-build-api-0.0.7.pom (3.2 kB at 9.3 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/sonatype/spice/spice-parent/15/spice-parent-15.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/sonatype/spice/spice-parent/15/spice-parent-15.pom (8.4 kB at 25 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/sonatype/forge/forge-parent/5/forge-parent-5.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/sonatype/forge/forge-parent/5/forge-parent-5.pom (8.4 kB at 24 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/1.5.8/plexus-utils-1.5.8.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/1.5.8/plexus-utils-1.5.8.pom (8.1 kB at 23 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus/2.0.2/plexus-2.0.2.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus/2.0.2/plexus-2.0.2.pom (12 kB at 34 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/commons-io/commons-io/2.5/commons-io-2.5.pom
Downloaded from central: https://repo.maven.apache.org/maven2/commons-io/commons-io/2.5/commons-io-2.5.pom (13 kB at 39 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-parent/39/commons-parent-39.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-parent/39/commons-parent-39.pom (62 kB at 180 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/apache/16/apache-16.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/apache/16/apache-16.pom (15 kB at 26 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-interpolation/1.24/plexus-interpolation-1.24.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-interpolation/1.24/plexus-interpolation-1.24.pom (2.6 kB at 7.7 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-plugin-api/3.0/maven-plugin-api-3.0.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-artifact/3.0/maven-artifact-3.0.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/sonatype/sisu/sisu-inject-bean/1.4.2/sisu-inject-bean-1.4.2.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/sonatype/sisu/sisu-inject-plexus/1.4.2/sisu-inject-plexus-1.4.2.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/sonatype/sisu/sisu-guice/2.1.7/sisu-guice-2.1.7-noaop.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-artifact/3.0/maven-artifact-3.0.jar (52 kB at 157 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-core/3.0/maven-core-3.0.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-plugin-api/3.0/maven-plugin-api-3.0.jar (49 kB at 131 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-settings/3.0/maven-settings-3.0.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/sonatype/sisu/sisu-inject-bean/1.4.2/sisu-inject-bean-1.4.2.jar (153 kB at 405 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/sonatype/sisu/sisu-inject-plexus/1.4.2/sisu-inject-plexus-1.4.2.jar (202 kB at 527 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-settings-builder/3.0/maven-settings-builder-3.0.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-repository-metadata/3.0/maven-repository-metadata-3.0.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-core/3.0/maven-core-3.0.jar (527 kB at 784 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-model-builder/3.0/maven-model-builder-3.0.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-settings/3.0/maven-settings-3.0.jar (47 kB at 68 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-aether-provider/3.0/maven-aether-provider-3.0.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-repository-metadata/3.0/maven-repository-metadata-3.0.jar (30 kB at 41 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-settings-builder/3.0/maven-settings-builder-3.0.jar (38 kB at 52 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/sonatype/aether/aether-impl/1.7/aether-impl-1.7.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/sonatype/aether/aether-spi/1.7/aether-spi-1.7.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-model-builder/3.0/maven-model-builder-3.0.jar (148 kB at 148 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/sonatype/aether/aether-api/1.7/aether-api-1.7.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-aether-provider/3.0/maven-aether-provider-3.0.jar (51 kB at 50 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/sonatype/aether/aether-util/1.7/aether-util-1.7.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/sonatype/aether/aether-spi/1.7/aether-spi-1.7.jar (14 kB at 13 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-classworlds/2.2.3/plexus-classworlds-2.2.3.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/sonatype/aether/aether-impl/1.7/aether-impl-1.7.jar (106 kB at 99 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-component-annotations/1.7.1/plexus-component-annotations-1.7.1.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/sonatype/aether/aether-api/1.7/aether-api-1.7.jar (74 kB at 55 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/sonatype/plexus/plexus-sec-dispatcher/1.3/plexus-sec-dispatcher-1.3.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/sonatype/aether/aether-util/1.7/aether-util-1.7.jar (108 kB at 80 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/sonatype/plexus/plexus-cipher/1.4/plexus-cipher-1.4.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-component-annotations/1.7.1/plexus-component-annotations-1.7.1.jar (4.3 kB at 3.0 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-model/3.0/maven-model-3.0.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-classworlds/2.2.3/plexus-classworlds-2.2.3.jar (46 kB at 32 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/3.1.0/plexus-utils-3.1.0.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/sonatype/plexus/plexus-sec-dispatcher/1.3/plexus-sec-dispatcher-1.3.jar (29 kB at 17 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-filtering/3.1.1/maven-filtering-3.1.1.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/sonatype/plexus/plexus-cipher/1.4/plexus-cipher-1.4.jar (13 kB at 8.1 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-utils/3.0.0/maven-shared-utils-3.0.0.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/sonatype/sisu/sisu-guice/2.1.7/sisu-guice-2.1.7-noaop.jar (472 kB at 271 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/com/google/code/findbugs/jsr305/2.0.1/jsr305-2.0.1.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-model/3.0/maven-model-3.0.jar (165 kB at 92 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/sonatype/plexus/plexus-build-api/0.0.7/plexus-build-api-0.0.7.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/3.1.0/plexus-utils-3.1.0.jar (262 kB at 145 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/commons-io/commons-io/2.5/commons-io-2.5.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-filtering/3.1.1/maven-filtering-3.1.1.jar (51 kB at 26 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-interpolation/1.24/plexus-interpolation-1.24.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-utils/3.0.0/maven-shared-utils-3.0.0.jar (155 kB at 77 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/com/google/code/findbugs/jsr305/2.0.1/jsr305-2.0.1.jar (32 kB at 15 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/sonatype/plexus/plexus-build-api/0.0.7/plexus-build-api-0.0.7.jar (8.5 kB at 4.0 kB/s)
Downloaded from central: https://repo.maven.apache.org/maven2/commons-io/commons-io/2.5/commons-io-2.5.jar (209 kB at 96 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-interpolation/1.24/plexus-interpolation-1.24.jar (79 kB at 34 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: [INFO] Using 'UTF-8' encoding to copy filtered resources.
default/uppercase-btpf4-pod-d4639b[build-step-build]: [INFO] Copying 1 resource
default/uppercase-btpf4-pod-d4639b[build-step-build]: [INFO] Copying 0 resource
default/uppercase-btpf4-pod-d4639b[build-step-build]: [INFO]
default/uppercase-btpf4-pod-d4639b[build-step-build]: [INFO] --- maven-compiler-plugin:3.8.0:compile (default-compile) @ uppercase ---
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-utils/3.2.1/maven-shared-utils-3.2.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-utils/3.2.1/maven-shared-utils-3.2.1.pom (5.6 kB at 17 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-incremental/1.1/maven-shared-incremental-1.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-incremental/1.1/maven-shared-incremental-1.1.pom (4.7 kB at 15 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-components/19/maven-shared-components-19.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-components/19/maven-shared-components-19.pom (6.4 kB at 20 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-parent/23/maven-parent-23.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-parent/23/maven-parent-23.pom (33 kB at 101 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/apache/13/apache-13.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/apache/13/apache-13.pom (14 kB at 43 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-plugin-api/2.2.1/maven-plugin-api-2.2.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-plugin-api/2.2.1/maven-plugin-api-2.2.1.pom (1.5 kB at 4.5 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven/2.2.1/maven-2.2.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven/2.2.1/maven-2.2.1.pom (22 kB at 69 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-parent/11/maven-parent-11.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-parent/11/maven-parent-11.pom (32 kB at 100 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/apache/5/apache-5.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/apache/5/apache-5.pom (4.1 kB at 13 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-core/2.2.1/maven-core-2.2.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-core/2.2.1/maven-core-2.2.1.pom (12 kB at 35 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-settings/2.2.1/maven-settings-2.2.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-settings/2.2.1/maven-settings-2.2.1.pom (2.2 kB at 6.7 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-model/2.2.1/maven-model-2.2.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-model/2.2.1/maven-model-2.2.1.pom (3.2 kB at 9.9 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/1.5.15/plexus-utils-1.5.15.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/1.5.15/plexus-utils-1.5.15.pom (6.8 kB at 21 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-interpolation/1.11/plexus-interpolation-1.11.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-interpolation/1.11/plexus-interpolation-1.11.pom (889 B at 2.7 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-components/1.1.14/plexus-components-1.1.14.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-components/1.1.14/plexus-components-1.1.14.pom (5.8 kB at 17 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-plugin-parameter-documenter/2.2.1/maven-plugin-parameter-documenter-2.2.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-plugin-parameter-documenter/2.2.1/maven-plugin-parameter-documenter-2.2.1.pom (2.0 kB at 6.0 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/slf4j/slf4j-jdk14/1.5.6/slf4j-jdk14-1.5.6.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/slf4j/slf4j-jdk14/1.5.6/slf4j-jdk14-1.5.6.pom (1.9 kB at 5.9 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/slf4j/slf4j-parent/1.5.6/slf4j-parent-1.5.6.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/slf4j/slf4j-parent/1.5.6/slf4j-parent-1.5.6.pom (7.9 kB at 24 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/slf4j/slf4j-api/1.5.6/slf4j-api-1.5.6.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/slf4j/slf4j-api/1.5.6/slf4j-api-1.5.6.pom (3.0 kB at 9.2 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/slf4j/jcl-over-slf4j/1.5.6/jcl-over-slf4j-1.5.6.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/slf4j/jcl-over-slf4j/1.5.6/jcl-over-slf4j-1.5.6.pom (2.2 kB at 6.7 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-profile/2.2.1/maven-profile-2.2.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-profile/2.2.1/maven-profile-2.2.1.pom (2.2 kB at 6.7 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-artifact/2.2.1/maven-artifact-2.2.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-artifact/2.2.1/maven-artifact-2.2.1.pom (1.6 kB at 4.9 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-repository-metadata/2.2.1/maven-repository-metadata-2.2.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-repository-metadata/2.2.1/maven-repository-metadata-2.2.1.pom (1.9 kB at 5.8 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-error-diagnostics/2.2.1/maven-error-diagnostics-2.2.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-error-diagnostics/2.2.1/maven-error-diagnostics-2.2.1.pom (1.7 kB at 5.2 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-project/2.2.1/maven-project-2.2.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-project/2.2.1/maven-project-2.2.1.pom (2.8 kB at 8.5 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-artifact-manager/2.2.1/maven-artifact-manager-2.2.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-artifact-manager/2.2.1/maven-artifact-manager-2.2.1.pom (3.1 kB at 9.5 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/backport-util-concurrent/backport-util-concurrent/3.1/backport-util-concurrent-3.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/backport-util-concurrent/backport-util-concurrent/3.1/backport-util-concurrent-3.1.pom (880 B at 2.6 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-plugin-registry/2.2.1/maven-plugin-registry-2.2.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-plugin-registry/2.2.1/maven-plugin-registry-2.2.1.pom (1.9 kB at 5.9 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-plugin-descriptor/2.2.1/maven-plugin-descriptor-2.2.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-plugin-descriptor/2.2.1/maven-plugin-descriptor-2.2.1.pom (2.1 kB at 6.4 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-monitor/2.2.1/maven-monitor-2.2.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-monitor/2.2.1/maven-monitor-2.2.1.pom (1.3 kB at 3.9 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-utils/0.1/maven-shared-utils-0.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-utils/0.1/maven-shared-utils-0.1.pom (4.0 kB at 13 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-components/18/maven-shared-components-18.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-components/18/maven-shared-components-18.pom (4.9 kB at 15 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-parent/22/maven-parent-22.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-parent/22/maven-parent-22.pom (30 kB at 92 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/apache/11/apache-11.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/apache/11/apache-11.pom (15 kB at 45 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-java/0.9.10/plexus-java-0.9.10.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-java/0.9.10/plexus-java-0.9.10.pom (5.1 kB at 16 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-languages/0.9.10/plexus-languages-0.9.10.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-languages/0.9.10/plexus-languages-0.9.10.pom (4.1 kB at 13 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm/6.2/asm-6.2.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm/6.2/asm-6.2.pom (2.9 kB at 9.1 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/ow2/ow2/1.5/ow2-1.5.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/ow2/ow2/1.5/ow2-1.5.pom (11 kB at 35 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/com/thoughtworks/qdox/qdox/2.0-M9/qdox-2.0-M9.pom
Downloaded from central: https://repo.maven.apache.org/maven2/com/thoughtworks/qdox/qdox/2.0-M9/qdox-2.0-M9.pom (16 kB at 49 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/sonatype/oss/oss-parent/9/oss-parent-9.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/sonatype/oss/oss-parent/9/oss-parent-9.pom (6.6 kB at 20 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-compiler-api/2.8.4/plexus-compiler-api-2.8.4.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-compiler-api/2.8.4/plexus-compiler-api-2.8.4.pom (867 B at 2.5 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-compiler/2.8.4/plexus-compiler-2.8.4.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-compiler/2.8.4/plexus-compiler-2.8.4.pom (6.0 kB at 19 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-components/4.0/plexus-components-4.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-components/4.0/plexus-components-4.0.pom (2.7 kB at 8.2 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/3.0.22/plexus-utils-3.0.22.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/3.0.22/plexus-utils-3.0.22.pom (3.8 kB at 12 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-compiler-manager/2.8.4/plexus-compiler-manager-2.8.4.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-compiler-manager/2.8.4/plexus-compiler-manager-2.8.4.pom (692 B at 2.1 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-compiler-javac/2.8.4/plexus-compiler-javac-2.8.4.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-compiler-javac/2.8.4/plexus-compiler-javac-2.8.4.pom (771 B at 2.4 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-compilers/2.8.4/plexus-compilers-2.8.4.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-compilers/2.8.4/plexus-compilers-2.8.4.pom (1.3 kB at 4.2 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/2.0.4/plexus-utils-2.0.4.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-interpolation/1.14/plexus-interpolation-1.14.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-utils/3.2.1/maven-shared-utils-3.2.1.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-incremental/1.1/maven-shared-incremental-1.1.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-java/0.9.10/plexus-java-0.9.10.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/2.0.4/plexus-utils-2.0.4.jar (222 kB at 650 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm/6.2/asm-6.2.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-java/0.9.10/plexus-java-0.9.10.jar (39 kB at 115 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/com/thoughtworks/qdox/qdox/2.0-M9/qdox-2.0-M9.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-interpolation/1.14/plexus-interpolation-1.14.jar (61 kB at 166 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-compiler-api/2.8.4/plexus-compiler-api-2.8.4.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-incremental/1.1/maven-shared-incremental-1.1.jar (14 kB at 37 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-compiler-manager/2.8.4/plexus-compiler-manager-2.8.4.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-utils/3.2.1/maven-shared-utils-3.2.1.jar (167 kB at 438 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-compiler-javac/2.8.4/plexus-compiler-javac-2.8.4.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm/6.2/asm-6.2.jar (111 kB at 169 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-compiler-manager/2.8.4/plexus-compiler-manager-2.8.4.jar (4.7 kB at 6.9 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/com/thoughtworks/qdox/qdox/2.0-M9/qdox-2.0-M9.jar (317 kB at 465 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-compiler-api/2.8.4/plexus-compiler-api-2.8.4.jar (27 kB at 39 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-compiler-javac/2.8.4/plexus-compiler-javac-2.8.4.jar (21 kB at 29 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: [INFO] Changes detected - recompiling the module!
default/uppercase-btpf4-pod-d4639b[build-step-build]: [INFO] Compiling 1 source file to /workspace/target/classes
default/uppercase-btpf4-pod-d4639b[build-step-build]: [INFO]
default/uppercase-btpf4-pod-d4639b[build-step-build]: [INFO] --- maven-resources-plugin:3.1.0:testResources (default-testResources) @ uppercase ---
default/uppercase-btpf4-pod-d4639b[build-step-build]: [INFO] Not copying test resources
default/uppercase-btpf4-pod-d4639b[build-step-build]: [INFO]
default/uppercase-btpf4-pod-d4639b[build-step-build]: [INFO] --- maven-compiler-plugin:3.8.0:testCompile (default-testCompile) @ uppercase ---
default/uppercase-btpf4-pod-d4639b[build-step-build]: [INFO] Not compiling test sources
default/uppercase-btpf4-pod-d4639b[build-step-build]: [INFO]
default/uppercase-btpf4-pod-d4639b[build-step-build]: [INFO] --- maven-surefire-plugin:2.22.1:test (default-test) @ uppercase ---
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/maven-surefire-common/2.22.1/maven-surefire-common-2.22.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/maven-surefire-common/2.22.1/maven-surefire-common-2.22.1.pom (11 kB at 33 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugin-tools/maven-plugin-annotations/3.5.2/maven-plugin-annotations-3.5.2.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugin-tools/maven-plugin-annotations/3.5.2/maven-plugin-annotations-3.5.2.pom (1.6 kB at 4.7 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugin-tools/maven-plugin-tools/3.5.2/maven-plugin-tools-3.5.2.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugin-tools/maven-plugin-tools/3.5.2/maven-plugin-tools-3.5.2.pom (15 kB at 44 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-api/2.22.1/surefire-api-2.22.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-api/2.22.1/surefire-api-2.22.1.pom (3.5 kB at 10 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-logger-api/2.22.1/surefire-logger-api-2.22.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-logger-api/2.22.1/surefire-logger-api-2.22.1.pom (2.0 kB at 5.6 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-booter/2.22.1/surefire-booter-2.22.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-booter/2.22.1/surefire-booter-2.22.1.pom (7.5 kB at 21 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-container-default/1.0-alpha-9-stable-1/plexus-container-default-1.0-alpha-9-stable-1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-container-default/1.0-alpha-9-stable-1/plexus-container-default-1.0-alpha-9-stable-1.pom (3.9 kB at 11 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-containers/1.0.3/plexus-containers-1.0.3.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-containers/1.0.3/plexus-containers-1.0.3.pom (492 B at 1.4 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus/1.0.4/plexus-1.0.4.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus/1.0.4/plexus-1.0.4.pom (5.7 kB at 17 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/1.0.4/plexus-utils-1.0.4.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/1.0.4/plexus-utils-1.0.4.pom (6.9 kB at 20 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/classworlds/classworlds/1.1-alpha-2/classworlds-1.1-alpha-2.pom
Downloaded from central: https://repo.maven.apache.org/maven2/classworlds/classworlds/1.1-alpha-2/classworlds-1.1-alpha-2.pom (3.1 kB at 9.1 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/reporting/maven-reporting-api/3.0/maven-reporting-api-3.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/reporting/maven-reporting-api/3.0/maven-reporting-api-3.0.pom (2.4 kB at 6.8 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-components/15/maven-shared-components-15.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-components/15/maven-shared-components-15.pom (9.3 kB at 27 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-parent/16/maven-parent-16.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-parent/16/maven-parent-16.pom (23 kB at 67 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/apache/7/apache-7.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/apache/7/apache-7.pom (14 kB at 42 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/classworlds/classworlds/1.1/classworlds-1.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/classworlds/classworlds/1.1/classworlds-1.1.pom (3.3 kB at 9.7 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-toolchain/2.2.1/maven-toolchain-2.2.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-toolchain/2.2.1/maven-toolchain-2.2.1.pom (3.3 kB at 9.8 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/com/thoughtworks/qdox/qdox/2.0-M8/qdox-2.0-M8.pom
Downloaded from central: https://repo.maven.apache.org/maven2/com/thoughtworks/qdox/qdox/2.0-M8/qdox-2.0-M8.pom (16 kB at 46 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/maven-surefire-common/2.22.1/maven-surefire-common-2.22.1.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-plugin-api/2.2.1/maven-plugin-api-2.2.1.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugin-tools/maven-plugin-annotations/3.5.2/maven-plugin-annotations-3.5.2.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-api/2.22.1/surefire-api-2.22.1.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-logger-api/2.22.1/surefire-logger-api-2.22.1.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-logger-api/2.22.1/surefire-logger-api-2.22.1.jar (13 kB at 39 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-booter/2.22.1/surefire-booter-2.22.1.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-plugin-api/2.2.1/maven-plugin-api-2.2.1.jar (12 kB at 35 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugin-tools/maven-plugin-annotations/3.5.2/maven-plugin-annotations-3.5.2.jar (14 kB at 40 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/1.5.15/plexus-utils-1.5.15.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-artifact/2.2.1/maven-artifact-2.2.1.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/maven-surefire-common/2.22.1/maven-surefire-common-2.22.1.jar (528 kB at 1.3 MB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-plugin-descriptor/2.2.1/maven-plugin-descriptor-2.2.1.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-api/2.22.1/surefire-api-2.22.1.jar (186 kB at 272 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-container-default/1.0-alpha-9-stable-1/plexus-container-default-1.0-alpha-9-stable-1.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-artifact/2.2.1/maven-artifact-2.2.1.jar (80 kB at 116 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-project/2.2.1/maven-project-2.2.1.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/1.5.15/plexus-utils-1.5.15.jar (228 kB at 322 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-settings/2.2.1/maven-settings-2.2.1.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-booter/2.22.1/surefire-booter-2.22.1.jar (274 kB at 381 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-profile/2.2.1/maven-profile-2.2.1.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-plugin-descriptor/2.2.1/maven-plugin-descriptor-2.2.1.jar (39 kB at 54 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-artifact-manager/2.2.1/maven-artifact-manager-2.2.1.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-container-default/1.0-alpha-9-stable-1/plexus-container-default-1.0-alpha-9-stable-1.jar (194 kB at 185 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/backport-util-concurrent/backport-util-concurrent/3.1/backport-util-concurrent-3.1.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-settings/2.2.1/maven-settings-2.2.1.jar (49 kB at 47 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-plugin-registry/2.2.1/maven-plugin-registry-2.2.1.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-project/2.2.1/maven-project-2.2.1.jar (156 kB at 149 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-interpolation/1.11/plexus-interpolation-1.11.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-profile/2.2.1/maven-profile-2.2.1.jar (35 kB at 33 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-model/2.2.1/maven-model-2.2.1.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-artifact-manager/2.2.1/maven-artifact-manager-2.2.1.jar (68 kB at 63 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-core/2.2.1/maven-core-2.2.1.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-plugin-registry/2.2.1/maven-plugin-registry-2.2.1.jar (30 kB at 22 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-plugin-parameter-documenter/2.2.1/maven-plugin-parameter-documenter-2.2.1.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-interpolation/1.11/plexus-interpolation-1.11.jar (51 kB at 37 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/slf4j/slf4j-jdk14/1.5.6/slf4j-jdk14-1.5.6.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/backport-util-concurrent/backport-util-concurrent/3.1/backport-util-concurrent-3.1.jar (332 kB at 237 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/slf4j/slf4j-api/1.5.6/slf4j-api-1.5.6.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-model/2.2.1/maven-model-2.2.1.jar (88 kB at 62 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/slf4j/jcl-over-slf4j/1.5.6/jcl-over-slf4j-1.5.6.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-core/2.2.1/maven-core-2.2.1.jar (178 kB at 125 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/reporting/maven-reporting-api/3.0/maven-reporting-api-3.0.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-plugin-parameter-documenter/2.2.1/maven-plugin-parameter-documenter-2.2.1.jar (22 kB at 13 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-repository-metadata/2.2.1/maven-repository-metadata-2.2.1.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/slf4j/slf4j-jdk14/1.5.6/slf4j-jdk14-1.5.6.jar (8.8 kB at 5.2 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-error-diagnostics/2.2.1/maven-error-diagnostics-2.2.1.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/slf4j/slf4j-api/1.5.6/slf4j-api-1.5.6.jar (22 kB at 13 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-monitor/2.2.1/maven-monitor-2.2.1.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/slf4j/jcl-over-slf4j/1.5.6/jcl-over-slf4j-1.5.6.jar (17 kB at 9.6 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/classworlds/classworlds/1.1/classworlds-1.1.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/reporting/maven-reporting-api/3.0/maven-reporting-api-3.0.jar (11 kB at 6.2 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-toolchain/2.2.1/maven-toolchain-2.2.1.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-error-diagnostics/2.2.1/maven-error-diagnostics-2.2.1.jar (13 kB at 6.4 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/com/thoughtworks/qdox/qdox/2.0-M8/qdox-2.0-M8.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-repository-metadata/2.2.1/maven-repository-metadata-2.2.1.jar (26 kB at 13 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-monitor/2.2.1/maven-monitor-2.2.1.jar (10 kB at 5.1 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/classworlds/classworlds/1.1/classworlds-1.1.jar (38 kB at 18 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-toolchain/2.2.1/maven-toolchain-2.2.1.jar (38 kB at 18 kB/s)
Downloaded from central: https://repo.maven.apache.org/maven2/com/thoughtworks/qdox/qdox/2.0-M8/qdox-2.0-M8.jar (316 kB at 134 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: [INFO] Tests are skipped.
default/uppercase-btpf4-pod-d4639b[build-step-build]: [INFO]
default/uppercase-btpf4-pod-d4639b[build-step-build]: [INFO] --- maven-jar-plugin:3.1.0:jar (default-jar) @ uppercase ---
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-archiver/3.2.0/maven-archiver-3.2.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-archiver/3.2.0/maven-archiver-3.2.0.pom (4.3 kB at 13 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-utils/3.2.0/maven-shared-utils-3.2.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-utils/3.2.0/maven-shared-utils-3.2.0.pom (4.9 kB at 15 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-archiver/3.5/plexus-archiver-3.5.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-archiver/3.5/plexus-archiver-3.5.pom (4.8 kB at 15 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus/5.0/plexus-5.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus/5.0/plexus-5.0.pom (21 kB at 65 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-io/3.0.0/plexus-io-3.0.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-io/3.0.0/plexus-io-3.0.0.pom (4.5 kB at 14 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-compress/1.14/commons-compress-1.14.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-compress/1.14/commons-compress-1.14.pom (13 kB at 40 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-parent/42/commons-parent-42.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-parent/42/commons-parent-42.pom (68 kB at 205 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/iq80/snappy/snappy/0.4/snappy-0.4.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/iq80/snappy/snappy/0.4/snappy-0.4.pom (15 kB at 45 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/tukaani/xz/1.6/xz-1.6.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/tukaani/xz/1.6/xz-1.6.pom (1.9 kB at 5.9 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-archiver/3.2.0/maven-archiver-3.2.0.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-io/3.0.0/plexus-io-3.0.0.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-archiver/3.5/plexus-archiver-3.5.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-utils/3.2.0/maven-shared-utils-3.2.0.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-compress/1.14/commons-compress-1.14.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-archiver/3.5/plexus-archiver-3.5.jar (187 kB at 549 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/iq80/snappy/snappy/0.4/snappy-0.4.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-archiver/3.2.0/maven-archiver-3.2.0.jar (24 kB at 66 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/tukaani/xz/1.6/xz-1.6.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-io/3.0.0/plexus-io-3.0.0.jar (74 kB at 202 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-utils/3.2.0/maven-shared-utils-3.2.0.jar (165 kB at 433 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-compress/1.14/commons-compress-1.14.jar (530 kB at 1.4 MB/s)
Downloaded from central: https://repo.maven.apache.org/maven2/org/iq80/snappy/snappy/0.4/snappy-0.4.jar (58 kB at 87 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/tukaani/xz/1.6/xz-1.6.jar (103 kB at 150 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: [INFO] Building jar: /workspace/target/uppercase-0.0.1-SNAPSHOT.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: [INFO]
default/uppercase-btpf4-pod-d4639b[build-step-build]: [INFO] --- spring-boot-maven-plugin:2.1.0.RELEASE:repackage (repackage) @ uppercase ---
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/springframework/boot/spring-boot-loader-tools/2.1.0.RELEASE/spring-boot-loader-tools-2.1.0.RELEASE.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/springframework/boot/spring-boot-loader-tools/2.1.0.RELEASE/spring-boot-loader-tools-2.1.0.RELEASE.pom (2.7 kB at 7.8 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-compress/1.18/commons-compress-1.18.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-compress/1.18/commons-compress-1.18.pom (18 kB at 55 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-parent/47/commons-parent-47.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-parent/47/commons-parent-47.pom (78 kB at 229 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-component-annotations/1.5.5/plexus-component-annotations-1.5.5.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-component-annotations/1.5.5/plexus-component-annotations-1.5.5.pom (815 B at 2.4 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-containers/1.5.5/plexus-containers-1.5.5.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-containers/1.5.5/plexus-containers-1.5.5.pom (4.2 kB at 13 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-component-annotations/1.5.4/plexus-component-annotations-1.5.4.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-component-annotations/1.5.4/plexus-component-annotations-1.5.4.pom (815 B at 2.5 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-containers/1.5.4/plexus-containers-1.5.4.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-containers/1.5.4/plexus-containers-1.5.4.pom (4.2 kB at 13 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus/2.0.5/plexus-2.0.5.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus/2.0.5/plexus-2.0.5.pom (17 kB at 52 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-artifact/3.3.9/maven-artifact-3.3.9.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-artifact/3.3.9/maven-artifact-3.3.9.pom (2.1 kB at 6.3 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven/3.3.9/maven-3.3.9.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven/3.3.9/maven-3.3.9.pom (24 kB at 72 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-parent/27/maven-parent-27.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-parent/27/maven-parent-27.pom (41 kB at 118 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/apache/17/apache-17.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/apache/17/apache-17.pom (16 kB at 47 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-lang3/3.8.1/commons-lang3-3.8.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-lang3/3.8.1/commons-lang3-3.8.1.pom (28 kB at 83 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-core/3.3.9/maven-core-3.3.9.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-core/3.3.9/maven-core-3.3.9.pom (8.3 kB at 25 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-model/3.3.9/maven-model-3.3.9.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-model/3.3.9/maven-model-3.3.9.pom (4.0 kB at 12 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-settings/3.3.9/maven-settings-3.3.9.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-settings/3.3.9/maven-settings-3.3.9.pom (1.8 kB at 5.1 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-settings-builder/3.3.9/maven-settings-builder-3.3.9.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-settings-builder/3.3.9/maven-settings-builder-3.3.9.pom (2.6 kB at 7.8 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-builder-support/3.3.9/maven-builder-support-3.3.9.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-builder-support/3.3.9/maven-builder-support-3.3.9.pom (1.7 kB at 5.0 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-interpolation/1.21/plexus-interpolation-1.21.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-interpolation/1.21/plexus-interpolation-1.21.pom (1.5 kB at 4.7 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-component-annotations/1.6/plexus-component-annotations-1.6.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-component-annotations/1.6/plexus-component-annotations-1.6.pom (748 B at 2.3 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-containers/1.6/plexus-containers-1.6.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-containers/1.6/plexus-containers-1.6.pom (3.8 kB at 11 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus/3.3.2/plexus-3.3.2.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus/3.3.2/plexus-3.3.2.pom (22 kB at 65 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-repository-metadata/3.3.9/maven-repository-metadata-3.3.9.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-repository-metadata/3.3.9/maven-repository-metadata-3.3.9.pom (1.9 kB at 5.7 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-plugin-api/3.3.9/maven-plugin-api-3.3.9.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-plugin-api/3.3.9/maven-plugin-api-3.3.9.pom (2.7 kB at 8.1 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/eclipse/sisu/org.eclipse.sisu.plexus/0.3.2/org.eclipse.sisu.plexus-0.3.2.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/eclipse/sisu/org.eclipse.sisu.plexus/0.3.2/org.eclipse.sisu.plexus-0.3.2.pom (4.2 kB at 13 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/eclipse/sisu/sisu-plexus/0.3.2/sisu-plexus-0.3.2.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/eclipse/sisu/sisu-plexus/0.3.2/sisu-plexus-0.3.2.pom (14 kB at 42 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/javax/enterprise/cdi-api/1.0/cdi-api-1.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/javax/enterprise/cdi-api/1.0/cdi-api-1.0.pom (1.4 kB at 4.3 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/jboss/weld/weld-api-parent/1.0/weld-api-parent-1.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/jboss/weld/weld-api-parent/1.0/weld-api-parent-1.0.pom (2.4 kB at 7.1 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/jboss/weld/weld-api-bom/1.0/weld-api-bom-1.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/jboss/weld/weld-api-bom/1.0/weld-api-bom-1.0.pom (7.9 kB at 24 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/jboss/weld/weld-parent/6/weld-parent-6.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/jboss/weld/weld-parent/6/weld-parent-6.pom (21 kB at 62 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/javax/annotation/jsr250-api/1.0/jsr250-api-1.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/javax/annotation/jsr250-api/1.0/jsr250-api-1.0.pom (1.0 kB at 3.1 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/javax/inject/javax.inject/1/javax.inject-1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/javax/inject/javax.inject/1/javax.inject-1.pom (612 B at 1.8 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/eclipse/sisu/org.eclipse.sisu.inject/0.3.2/org.eclipse.sisu.inject-0.3.2.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/eclipse/sisu/org.eclipse.sisu.inject/0.3.2/org.eclipse.sisu.inject-0.3.2.pom (2.6 kB at 7.9 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/eclipse/sisu/sisu-inject/0.3.2/sisu-inject-0.3.2.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/eclipse/sisu/sisu-inject/0.3.2/sisu-inject-0.3.2.pom (14 kB at 44 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-classworlds/2.5.2/plexus-classworlds-2.5.2.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-classworlds/2.5.2/plexus-classworlds-2.5.2.pom (7.3 kB at 22 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/3.0.17/plexus-utils-3.0.17.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/3.0.17/plexus-utils-3.0.17.pom (3.4 kB at 10 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-model-builder/3.3.9/maven-model-builder-3.3.9.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-model-builder/3.3.9/maven-model-builder-3.3.9.pom (3.1 kB at 9.5 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/com/google/guava/guava/18.0/guava-18.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/com/google/guava/guava/18.0/guava-18.0.pom (5.7 kB at 17 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/com/google/guava/guava-parent/18.0/guava-parent-18.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/com/google/guava/guava-parent/18.0/guava-parent-18.0.pom (7.7 kB at 23 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-aether-provider/3.3.9/maven-aether-provider-3.3.9.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-aether-provider/3.3.9/maven-aether-provider-3.3.9.pom (4.0 kB at 12 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/eclipse/aether/aether-api/1.0.2.v20150114/aether-api-1.0.2.v20150114.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/eclipse/aether/aether-api/1.0.2.v20150114/aether-api-1.0.2.v20150114.pom (1.8 kB at 5.5 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/eclipse/aether/aether/1.0.2.v20150114/aether-1.0.2.v20150114.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/eclipse/aether/aether/1.0.2.v20150114/aether-1.0.2.v20150114.pom (29 kB at 88 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/eclipse/aether/aether-spi/1.0.2.v20150114/aether-spi-1.0.2.v20150114.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/eclipse/aether/aether-spi/1.0.2.v20150114/aether-spi-1.0.2.v20150114.pom (2.0 kB at 6.0 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/eclipse/aether/aether-util/1.0.2.v20150114/aether-util-1.0.2.v20150114.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/eclipse/aether/aether-util/1.0.2.v20150114/aether-util-1.0.2.v20150114.pom (2.1 kB at 6.4 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/eclipse/aether/aether-impl/1.0.2.v20150114/aether-impl-1.0.2.v20150114.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/eclipse/aether/aether-impl/1.0.2.v20150114/aether-impl-1.0.2.v20150114.pom (3.4 kB at 10 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/com/google/inject/guice/4.0/guice-4.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/com/google/inject/guice/4.0/guice-4.0.pom (11 kB at 32 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/com/google/inject/guice-parent/4.0/guice-parent-4.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/com/google/inject/guice-parent/4.0/guice-parent-4.0.pom (15 kB at 47 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/com/google/google/5/google-5.pom
Downloaded from central: https://repo.maven.apache.org/maven2/com/google/google/5/google-5.pom (2.5 kB at 7.4 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/aopalliance/aopalliance/1.0/aopalliance-1.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/aopalliance/aopalliance/1.0/aopalliance-1.0.pom (363 B at 1.1 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/com/google/guava/guava/16.0.1/guava-16.0.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/com/google/guava/guava/16.0.1/guava-16.0.1.pom (6.1 kB at 18 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/com/google/guava/guava-parent/16.0.1/guava-parent-16.0.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/com/google/guava/guava-parent/16.0.1/guava-parent-16.0.1.pom (7.3 kB at 22 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-common-artifact-filters/3.0.1/maven-common-artifact-filters-3.0.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-common-artifact-filters/3.0.1/maven-common-artifact-filters-3.0.1.pom (4.8 kB at 15 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-utils/3.1.0/maven-shared-utils-3.1.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-utils/3.1.0/maven-shared-utils-3.1.0.pom (5.0 kB at 15 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-archiver/3.6.0/plexus-archiver-3.6.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-archiver/3.6.0/plexus-archiver-3.6.0.pom (4.8 kB at 14 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-io/3.0.1/plexus-io-3.0.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-io/3.0.1/plexus-io-3.0.1.pom (4.5 kB at 14 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/commons-io/commons-io/2.6/commons-io-2.6.pom
Downloaded from central: https://repo.maven.apache.org/maven2/commons-io/commons-io/2.6/commons-io-2.6.pom (14 kB at 43 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-compress/1.16.1/commons-compress-1.16.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-compress/1.16.1/commons-compress-1.16.1.pom (16 kB at 47 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-parent/43/commons-parent-43.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-parent/43/commons-parent-43.pom (70 kB at 207 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/tukaani/xz/1.8/xz-1.8.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/tukaani/xz/1.8/xz-1.8.pom (1.9 kB at 5.7 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-shade-plugin/3.2.0/maven-shade-plugin-3.2.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-shade-plugin/3.2.0/maven-shade-plugin-3.2.0.pom (9.3 kB at 28 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-artifact-transfer/0.10.0/maven-artifact-transfer-0.10.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-artifact-transfer/0.10.0/maven-artifact-transfer-0.10.0.pom (12 kB at 33 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-components/31/maven-shared-components-31.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-components/31/maven-shared-components-31.pom (5.1 kB at 15 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/commons-codec/commons-codec/1.11/commons-codec-1.11.pom
Downloaded from central: https://repo.maven.apache.org/maven2/commons-codec/commons-codec/1.11/commons-codec-1.11.pom (14 kB at 42 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm/6.2.1/asm-6.2.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm/6.2.1/asm-6.2.1.pom (2.9 kB at 8.6 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-commons/6.2.1/asm-commons-6.2.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-commons/6.2.1/asm-commons-6.2.1.pom (3.7 kB at 11 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-tree/6.2.1/asm-tree-6.2.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-tree/6.2.1/asm-tree-6.2.1.pom (3.1 kB at 9.4 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-analysis/6.2.1/asm-analysis-6.2.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-analysis/6.2.1/asm-analysis-6.2.1.pom (3.2 kB at 9.6 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/jdom/jdom2/2.0.6/jdom2-2.0.6.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/jdom/jdom2/2.0.6/jdom2-2.0.6.pom (4.6 kB at 14 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-dependency-tree/2.2/maven-dependency-tree-2.2.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-dependency-tree/2.2/maven-dependency-tree-2.2.pom (7.3 kB at 22 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-components/20/maven-shared-components-20.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-components/20/maven-shared-components-20.pom (5.1 kB at 15 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-parent/24/maven-parent-24.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-parent/24/maven-parent-24.pom (37 kB at 109 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/apache/14/apache-14.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/apache/14/apache-14.pom (15 kB at 44 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/eclipse/aether/aether-util/0.9.0.M2/aether-util-0.9.0.M2.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/eclipse/aether/aether-util/0.9.0.M2/aether-util-0.9.0.M2.pom (2.0 kB at 6.1 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/eclipse/aether/aether/0.9.0.M2/aether-0.9.0.M2.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/eclipse/aether/aether/0.9.0.M2/aether-0.9.0.M2.pom (28 kB at 84 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/vafer/jdependency/2.0/jdependency-2.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/vafer/jdependency/2.0/jdependency-2.0.pom (11 kB at 34 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-analysis/6.2/asm-analysis-6.2.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-analysis/6.2/asm-analysis-6.2.pom (3.2 kB at 9.6 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-tree/6.2/asm-tree-6.2.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-tree/6.2/asm-tree-6.2.pom (3.1 kB at 9.5 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-commons/6.2/asm-commons-6.2.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-commons/6.2/asm-commons-6.2.pom (3.7 kB at 11 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-util/6.2/asm-util-6.2.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-util/6.2/asm-util-6.2.pom (3.6 kB at 11 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/com/google/guava/guava/19.0/guava-19.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/com/google/guava/guava/19.0/guava-19.0.pom (6.8 kB at 20 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/com/google/guava/guava-parent/19.0/guava-parent-19.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/com/google/guava/guava-parent/19.0/guava-parent-19.0.pom (9.9 kB at 30 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/springframework/boot/spring-boot-loader-tools/2.1.0.RELEASE/spring-boot-loader-tools-2.1.0.RELEASE.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/springframework/spring-core/5.1.2.RELEASE/spring-core-5.1.2.RELEASE.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/springframework/spring-jcl/5.1.2.RELEASE/spring-jcl-5.1.2.RELEASE.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-compress/1.18/commons-compress-1.18.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-interpolation/1.22/plexus-interpolation-1.22.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/springframework/spring-jcl/5.1.2.RELEASE/spring-jcl-5.1.2.RELEASE.jar (0 B at 0 B/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-artifact/3.3.9/maven-artifact-3.3.9.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/springframework/spring-core/5.1.2.RELEASE/spring-core-5.1.2.RELEASE.jar (0 B at 0 B/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-lang3/3.8.1/commons-lang3-3.8.1.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/springframework/boot/spring-boot-loader-tools/2.1.0.RELEASE/spring-boot-loader-tools-2.1.0.RELEASE.jar (148 kB at 424 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-core/3.3.9/maven-core-3.3.9.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-interpolation/1.22/plexus-interpolation-1.22.jar (77 kB at 217 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-settings-builder/3.3.9/maven-settings-builder-3.3.9.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-artifact/3.3.9/maven-artifact-3.3.9.jar (55 kB at 109 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-builder-support/3.3.9/maven-builder-support-3.3.9.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-lang3/3.8.1/commons-lang3-3.8.1.jar (502 kB at 766 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-repository-metadata/3.3.9/maven-repository-metadata-3.3.9.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-settings-builder/3.3.9/maven-settings-builder-3.3.9.jar (43 kB at 62 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-model-builder/3.3.9/maven-model-builder-3.3.9.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-core/3.3.9/maven-core-3.3.9.jar (638 kB at 885 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-aether-provider/3.3.9/maven-aether-provider-3.3.9.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-builder-support/3.3.9/maven-builder-support-3.3.9.jar (15 kB at 18 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/eclipse/aether/aether-spi/1.0.2.v20150114/aether-spi-1.0.2.v20150114.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-repository-metadata/3.3.9/maven-repository-metadata-3.3.9.jar (27 kB at 28 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/eclipse/aether/aether-impl/1.0.2.v20150114/aether-impl-1.0.2.v20150114.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-aether-provider/3.3.9/maven-aether-provider-3.3.9.jar (67 kB at 63 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/eclipse/aether/aether-api/1.0.2.v20150114/aether-api-1.0.2.v20150114.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-model-builder/3.3.9/maven-model-builder-3.3.9.jar (177 kB at 166 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/eclipse/aether/aether-util/1.0.2.v20150114/aether-util-1.0.2.v20150114.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/eclipse/aether/aether-spi/1.0.2.v20150114/aether-spi-1.0.2.v20150114.jar (31 kB at 27 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/eclipse/sisu/org.eclipse.sisu.plexus/0.3.2/org.eclipse.sisu.plexus-0.3.2.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/eclipse/aether/aether-impl/1.0.2.v20150114/aether-impl-1.0.2.v20150114.jar (173 kB at 131 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/javax/enterprise/cdi-api/1.0/cdi-api-1.0.jarB
Downloaded from central: https://repo.maven.apache.org/maven2/org/eclipse/aether/aether-api/1.0.2.v20150114/aether-api-1.0.2.v20150114.jar (136 kB at 98 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/javax/annotation/jsr250-api/1.0/jsr250-api-1.0.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/eclipse/aether/aether-util/1.0.2.v20150114/aether-util-1.0.2.v20150114.jar (147 kB at 103 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/eclipse/sisu/org.eclipse.sisu.inject/0.3.2/org.eclipse.sisu.inject-0.3.2.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/eclipse/sisu/org.eclipse.sisu.plexus/0.3.2/org.eclipse.sisu.plexus-0.3.2.jar (205 kB at 138 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/com/google/inject/guice/4.0/guice-4.0-no_aop.jar
Downloaded from central: https://repo.maven.apache.org/maven2/javax/enterprise/cdi-api/1.0/cdi-api-1.0.jar (45 kB at 27 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/javax/inject/javax.inject/1/javax.inject-1.jar
Downloaded from central: https://repo.maven.apache.org/maven2/javax/annotation/jsr250-api/1.0/jsr250-api-1.0.jar (5.8 kB at 3.4 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/aopalliance/aopalliance/1.0/aopalliance-1.0.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/eclipse/sisu/org.eclipse.sisu.inject/0.3.2/org.eclipse.sisu.inject-0.3.2.jar (378 kB at 211 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-classworlds/2.5.2/plexus-classworlds-2.5.2.jar
Downloaded from central: https://repo.maven.apache.org/maven2/com/google/inject/guice/4.0/guice-4.0-no_aop.jar (424 kB at 231 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-component-annotations/1.6/plexus-component-annotations-1.6.jar
Downloaded from central: https://repo.maven.apache.org/maven2/javax/inject/javax.inject/1/javax.inject-1.jar (2.5 kB at 1.3 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-model/3.3.9/maven-model-3.3.9.jar
Downloaded from central: https://repo.maven.apache.org/maven2/aopalliance/aopalliance/1.0/aopalliance-1.0.jar (4.5 kB at 2.2 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-plugin-api/3.3.9/maven-plugin-api-3.3.9.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-compress/1.18/commons-compress-1.18.jar (592 kB at 281 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-settings/3.3.9/maven-settings-3.3.9.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-classworlds/2.5.2/plexus-classworlds-2.5.2.jar (53 kB at 25 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-common-artifact-filters/3.0.1/maven-common-artifact-filters-3.0.1.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-component-annotations/1.6/plexus-component-annotations-1.6.jar (4.3 kB at 2.0 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-archiver/3.6.0/plexus-archiver-3.6.0.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-model/3.3.9/maven-model-3.3.9.jar (164 kB at 71 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-io/3.0.1/plexus-io-3.0.1.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-plugin-api/3.3.9/maven-plugin-api-3.3.9.jar (47 kB at 20 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/tukaani/xz/1.8/xz-1.8.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-settings/3.3.9/maven-settings-3.3.9.jar (44 kB at 18 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-shade-plugin/3.2.0/maven-shade-plugin-3.2.0.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-common-artifact-filters/3.0.1/maven-common-artifact-filters-3.0.1.jar (61 kB at 25 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-artifact-transfer/0.10.0/maven-artifact-transfer-0.10.0.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-archiver/3.6.0/plexus-archiver-3.6.0.jar (191 kB at 76 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/commons-codec/commons-codec/1.11/commons-codec-1.11.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-io/3.0.1/plexus-io-3.0.1.jar (74 kB at 28 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm/6.2.1/asm-6.2.1.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/tukaani/xz/1.8/xz-1.8.jar (109 kB at 40 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-commons/6.2.1/asm-commons-6.2.1.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-shade-plugin/3.2.0/maven-shade-plugin-3.2.0.jar (113 kB at 41 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-tree/6.2.1/asm-tree-6.2.1.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-artifact-transfer/0.10.0/maven-artifact-transfer-0.10.0.jar (128 kB at 45 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-analysis/6.2.1/asm-analysis-6.2.1.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/commons-codec/commons-codec/1.11/commons-codec-1.11.jar (335 kB at 118 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/jdom/jdom2/2.0.6/jdom2-2.0.6.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm/6.2.1/asm-6.2.1.jar (113 kB at 38 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-dependency-tree/2.2/maven-dependency-tree-2.2.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-commons/6.2.1/asm-commons-6.2.1.jar (79 kB at 26 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/vafer/jdependency/2.0/jdependency-2.0.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-tree/6.2.1/asm-tree-6.2.1.jar (50 kB at 16 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-util/6.2/asm-util-6.2.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-analysis/6.2.1/asm-analysis-6.2.1.jar (33 kB at 10 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloading from central: https://repo.maven.apache.org/maven2/com/google/guava/guava/19.0/guava-19.0.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: Downloaded from central: https://repo.maven.apache.org/maven2/org/jdom/jdom2/2.0.6/jdom2-2.0.6.jar (305 kB at 96 kB/s)
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-dependency-tree/2.2/maven-dependency-tree-2.2.jar (64 kB at 19 kB/s)
Progress (3): 183 kB | 80 kB | 1.6/2.3 MBstep-build]: Progress (3): 183 kB | 80 kB | 0/2.3 MB
Downloaded from central: https://repo.maven.apache.org/maven2/org/vafer/jdependency/2.0/jdependency-2.0.jar (183 kB at 54 kB/s)
Downloaded from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-util/6.2/asm-util-6.2.jar (80 kB at 23 kB/s)
Downloaded from central: https://repo.maven.apache.org/maven2/com/google/guava/guava/19.0/guava-19.0.jar (2.3 MB at 624 kB/s)
default/uppercase-btpf4-pod-d4639b[build-step-build]: [INFO] Replacing main artifact /workspace/target/uppercase-0.0.1-SNAPSHOT.jar
default/uppercase-btpf4-pod-d4639b[build-step-build]: [INFO] ------------------------------------------------------------------------
default/uppercase-btpf4-pod-d4639b[build-step-build]: [INFO] BUILD SUCCESS
default/uppercase-btpf4-pod-d4639b[build-step-build]: [INFO] ------------------------------------------------------------------------
default/uppercase-btpf4-pod-d4639b[build-step-build]: [INFO] Total time: 03:17 min
default/uppercase-btpf4-pod-d4639b[build-step-build]: [INFO] Finished at: 2019-07-16T06:13:12Z
default/uppercase-btpf4-pod-d4639b[build-step-build]: [INFO] ------------------------------------------------------------------------
default/uppercase-btpf4-pod-d4639b[build-step-build]:        Removing source code
default/uppercase-btpf4-pod-d4639b[build-step-build]:
default/uppercase-btpf4-pod-d4639b[build-step-build]: -----> Java Function Buildpack 0.1.4
default/uppercase-btpf4-pod-d4639b[build-step-build]: -----> riff Java Invoker 0.1.4: Contributing to layer
default/uppercase-btpf4-pod-d4639b[build-step-build]:        Reusing cached download from buildpack
default/uppercase-btpf4-pod-d4639b[build-step-build]:        Unzipping java invoker to /layers/io.projectriff.java/riff-invoker-java
default/uppercase-btpf4-pod-d4639b[build-step-build]: -----> Java: Contributing to layer
default/uppercase-btpf4-pod-d4639b[build-step-build]:        Writing FUNCTION_URI to launch
default/uppercase-btpf4-pod-d4639b[build-step-build]: -----> Process types:
default/uppercase-btpf4-pod-d4639b[build-step-build]:        web:      java -cp /layers/io.projectriff.java/riff-invoker-java $JAVA_OPTS org.springframework.boot.loader.JarLauncher
default/uppercase-btpf4-pod-d4639b[build-step-build]:        function: java -cp /layers/io.projectriff.java/riff-invoker-java $JAVA_OPTS org.springframework.boot.loader.JarLauncher
default/uppercase-btpf4-pod-d4639b[build-step-build]:
default/uppercase-btpf4-pod-d4639b[build-step-export]: WARNING: image 'gcr.io/pa-yrampuria/uppercase' not found or requires authentication to access
default/uppercase-btpf4-pod-d4639b[build-step-export]: WARNING: image 'gcr.io/pa-yrampuria/uppercase' has incompatible 'io.buildpacks.lifecycle.metadata' label
default/uppercase-btpf4-pod-d4639b[build-step-export]: adding layer 'app' with diffID 'sha256:4575b10bb864be0017c0d978418bb86a6472cf9da67fce47ba1d7026a1368b5f'
default/uppercase-btpf4-pod-d4639b[build-step-export]: adding layer 'config' with diffID 'sha256:76df7cd4280e695367d7ddc9a84fa5af0eca4ab0efdcd39b4283145f3a544f10'
default/uppercase-btpf4-pod-d4639b[build-step-export]: adding layer 'launcher' with diffID 'sha256:7417c05f2e27d60b777911b95a538f0bac23fec8fec4175a499039949781fabc'
default/uppercase-btpf4-pod-d4639b[build-step-export]: adding layer 'org.cloudfoundry.openjdk:openjdk-jre' with diffID 'sha256:c71074e6642f870a4d644b778e4d6c7b84c773b932281fe8d89efcfb9e2475f9'
default/uppercase-btpf4-pod-d4639b[build-step-export]: adding layer 'io.projectriff.java:function' with diffID 'sha256:3bbd13f7161524809396ec97f3f2b2982807f55c02e986ba3d8bed4fe2d9b36d'
default/uppercase-btpf4-pod-d4639b[build-step-export]: adding layer 'io.projectriff.java:riff-invoker-java' with diffID 'sha256:1e5fab43556eb05d7aceb4313cf5fc3943933a7002b6a720a8b218354647097b'
default/uppercase-btpf4-pod-d4639b[build-step-export]: setting metadata label 'io.buildpacks.lifecycle.metadata'
default/uppercase-btpf4-pod-d4639b[build-step-export]: setting env var 'CNB_LAYERS_DIR=/layers'
default/uppercase-btpf4-pod-d4639b[build-step-export]: setting env var 'CNB_APP_DIR=/workspace'
default/uppercase-btpf4-pod-d4639b[build-step-export]: setting entrypoint '/lifecycle/launcher'
default/uppercase-btpf4-pod-d4639b[build-step-export]: setting empty cmd
default/uppercase-btpf4-pod-d4639b[build-step-export]: writing image
default/uppercase-btpf4-pod-d4639b[build-step-export]:
default/uppercase-btpf4-pod-d4639b[build-step-export]: *** Image: gcr.io/pa-yrampuria/uppercase@sha256:f181a15fe30c510b13655ae3f80188c0669e9f403f392533c6a4ba9615ba5e4c
default/uppercase-vkfb5-deployment-88b6876c4-pv9kz[user-container]:
default/uppercase-vkfb5-deployment-88b6876c4-pv9kz[user-container]:                 ?      ????????????
default/uppercase-vkfb5-deployment-88b6876c4-pv9kz[user-container]:                 ???    ??  ????  ??
default/uppercase-vkfb5-deployment-88b6876c4-pv9kz[user-container]:                ???? ??????????????
default/uppercase-vkfb5-deployment-88b6876c4-pv9kz[user-container]:               ?????   ???    ??
default/uppercase-vkfb5-deployment-88b6876c4-pv9kz[user-container]:    ?????????  ??      ???    ??
default/uppercase-vkfb5-deployment-88b6876c4-pv9kz[user-container]:     ???   ??  ??      ???    ??
default/uppercase-vkfb5-deployment-88b6876c4-pv9kz[user-container]:     ???       ??     ?????  ?????
default/uppercase-vkfb5-deployment-88b6876c4-pv9kz[user-container]:     ???       ??
default/uppercase-vkfb5-deployment-88b6876c4-pv9kz[user-container]:    ??????
default/uppercase-vkfb5-deployment-88b6876c4-pv9kz[user-container]:
default/uppercase-vkfb5-deployment-88b6876c4-pv9kz[user-container]: :: Powered by Spring Boot ::
default/uppercase-vkfb5-deployment-88b6876c4-pv9kz[user-container]: Jul 16, 2019 6:13:55 AM org.springframework.boot.StartupInfoLogger logStarting
default/uppercase-vkfb5-deployment-88b6876c4-pv9kz[user-container]: INFO: Starting application on uppercase-vkfb5-deployment-88b6876c4-pv9kz with PID 1 (/layers/io.projectriff.java/riff-invoker-java/BOOT-INF/classes started by pack in /workspace)
default/uppercase-vkfb5-deployment-88b6876c4-pv9kz[user-container]: Jul 16, 2019 6:13:55 AM org.springframework.boot.SpringApplication logStartupProfileInfo
default/uppercase-vkfb5-deployment-88b6876c4-pv9kz[user-container]: INFO: No active profile set, falling back to default profiles: default
default/uppercase-vkfb5-deployment-88b6876c4-pv9kz[user-container]: Jul 16, 2019 6:13:59 AM org.springframework.cloud.function.deployer.FunctionCreatorConfiguration init
default/uppercase-vkfb5-deployment-88b6876c4-pv9kz[user-container]: INFO: Locating function from [file:/workspace]
default/uppercase-vkfb5-deployment-88b6876c4-pv9kz[user-container]: Jul 16, 2019 6:13:59 AM org.springframework.cloud.function.deployer.FunctionCreatorConfiguration$BeanCreator run
default/uppercase-vkfb5-deployment-88b6876c4-pv9kz[user-container]: INFO: SpringApplication available. Bootstrapping: functions.UppercaseApplication
default/uppercase-vkfb5-deployment-88b6876c4-pv9kz[user-container]: WARNING: An illegal reflective access operation has occurred
default/uppercase-vkfb5-deployment-88b6876c4-pv9kz[user-container]: WARNING: Illegal reflective access by org.springframework.util.ReflectionUtils (jar:file:/workspace/BOOT-INF/lib/spring-core-5.1.2.RELEASE.jar!/) to field java.net.URL.factory
default/uppercase-vkfb5-deployment-88b6876c4-pv9kz[user-container]: WARNING: Please consider reporting this to the maintainers of org.springframework.util.ReflectionUtils
default/uppercase-vkfb5-deployment-88b6876c4-pv9kz[user-container]: WARNING: Use --illegal-access=warn to enable warnings of further illegal reflective access operations
default/uppercase-vkfb5-deployment-88b6876c4-pv9kz[user-container]: WARNING: All illegal access operations will be denied in a future release
default/uppercase-vkfb5-deployment-88b6876c4-pv9kz[user-container]: 2019-07-16 06:14:01.152  INFO 1 --- [       Thread-3] o.s.boot.SpringApplication               : Starting application on uppercase-vkfb5-deployment-88b6876c4-pv9kz with PID 1 (/workspace/BOOT-INF/lib/spring-cloud-function-web-2.0.0.RC2.jar started by pack in /workspace)
default/uppercase-vkfb5-deployment-88b6876c4-pv9kz[user-container]: 2019-07-16 06:14:01.173  INFO 1 --- [       Thread-3] o.s.boot.SpringApplication               : No active profile set, falling back to default profiles: default
default/uppercase-vkfb5-deployment-88b6876c4-pv9kz[user-container]: 2019-07-16 06:14:03.519  INFO 1 --- [       Thread-3] o.s.boot.SpringApplication               : Started application in 3.5 seconds (JVM running for 11.785)
default/uppercase-vkfb5-deployment-88b6876c4-pv9kz[user-container]: 2019-07-16 06:14:03.590  INFO 1 --- [       Thread-1] o.s.c.f.d.FunctionCreatorConfiguration   : Located bean: uppercase of type class functions.UppercaseApplication$$Lambda$505/0x00000001005cc440
default/uppercase-vkfb5-deployment-88b6876c4-pv9kz[user-container]: 2019-07-16 06:14:04.700  INFO 1 --- [       Thread-1] o.s.c.f.web.flux.FunctionHandlerMapping  : FunctionCatalog: org.springframework.cloud.function.context.config.ContextFunctionCatalogAutoConfiguration$BeanFactoryFunctionCatalog@2e05a5d1
default/uppercase-vkfb5-deployment-88b6876c4-pv9kz[user-container]: 2019-07-16 06:14:05.898  INFO 1 --- [       Thread-1] o.s.b.web.embedded.netty.NettyWebServer  : Netty started on port(s): 8080
default/uppercase-vkfb5-deployment-88b6876c4-pv9kz[user-container]: 2019-07-16 06:14:05.938  INFO 1 --- [       Thread-1] o.s.boot.SpringApplication               : Started application in 11.923 seconds (JVM running for 14.205)

pfs function create completed successfully
```
