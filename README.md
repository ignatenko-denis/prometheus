# Sample Prometheus configuration in OpenShift for monitoring microservices

In the sample single [Prometheus](https://prometheus.io/) local service `prometheus-sample-service` aggregates metrics from `first-service` and `second-service`.

In your microservices should be added monitoring through [Spring Actuator](https://docs.spring.io/spring-boot/docs/current/reference/html/actuator.html) and [Micrometer](https://micrometer.io/)

Check result:
1. http://prometheus-sample-service.apps.my-sample-host.com/targets local Prometheus
1. http://first-service.apps.my-sample-host.com/first-service/actuator/prometheus
1. http://first-service.apps.my-sample-host.com/first-service/actuator/metrics

***

[OpenShift](https://www.openshift.com/)
