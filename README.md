ActorFlowEngine
=========
## A light & fastest work flow with Actor pattern.
### environment: JDK1.8 above
### use from maven repository:
```
<dependency>
  <groupId>io.github.daviswlau</groupId>
  <artifactId>actflow-engine</artifactId>
  <version>1.0.2</version>
</dependency>
```

the cluster configuration, pls view 'resources/akkaActor-cluster.conf'

the flow sample, pls view 'engines/flow-sample.xml'

support Spring 4.x, just use the annotation @Inject, the actor will be auto inject your spring bean or service.

support TCC (try, confirm, cancel)
