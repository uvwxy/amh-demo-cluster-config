# Demo Config Repository

This is a demo config repository for the [autumn-macro-hindrance][1] demo.


## Structure

The demo is read by the [Spring Cloud Config Server][2].
The config files are as follows:

```
application.yml # read by all
task1.yml       # read by demo-cluster-service-task1
task2.yml       # read by demo-cluster-service-task2
...
```

## Links

[1]: https://github.com/uvwxy/autumn-macro-hindrance
[2]: https://cloud.spring.io/spring-cloud-config/
