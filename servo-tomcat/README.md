The following Tomcat metrics are collected by Servo from JMX.  The Tomcat service name must be set to Catalina in server.xml in order for the metrics to be located in JMX.

### Executor

| Name | Class | Type |
|------|-------|------|
| tomcat.activeCount | Executor | GAUGE |
| tomcat.completedTaskCount | Executor | GAUGE |
| tomcat.maxThreads | Executor | GAUGE |
| tomcat.poolSize | Executor | GAUGE |
| tomcat.queueSize | Executor | GAUGE |

### Global Request Processor

| Name | Class | Type |
|------|-------|------|
| tomcat.bytesSent | GlobalRequestProcessor | COUNTER |
| tomcat.errorCount | GlobalRequestProcessor | COUNTER |
| tomcat.maxTime | GlobalRequestProcessor | GAUGE |
| tomcat.processingTime | GlobalRequestProcessor | COUNTER |
| tomcat.requestCount | GlobalRequestProcessor | COUNTER |

### Thread Pool

| Name | Class | Type |
|------|-------|------|
| tomcat.backlog | ThreadPool | GAUGE |
| tomcat.currentThreadCount | ThreadPool | GAUGE |
| tomcat.currentThreadsBusy | ThreadPool | GAUGE |
| tomcat.maxThreads | ThreadPool | GAUGE |
