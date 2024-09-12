# Challenge 5 :: Cloud Native Applications Observability (Intermediate)
In the last challenge you run the application's services and required infrastructure (PostgreSQL database) in a Kubernetes Cluster. 
In this challenge you will use different tools to understand how your application is working.

## Objectives 

1) Use [Headlamp](https://headlamp.dev/) to inspect your cluster, your application and your application infrastructure. Notice that there is an option to run Headlamp inside the cluster, you should use that.
  a) Can you take a screenshot of your application services?   
3) Depending on your programming language, you need to instrument your application's services using the [OpenTelemetry](https://opentelemetry.io/docs/) SDKs. Note that you shouldn't use auto instrumentation; instead, use the SDK.
  a) Then use the [OTEL LGTM](https://github.com/grafana/docker-otel-lgtm) stack to monitor the traces and metrics 


## Lessons learned

1) How to inspect the content of a Kubernetes cluster using Headlamp
2) How to use OpenTelemetry to understand what your applications are doing
3) How to inspect application traces and metrics using Grafana OTEL LGTM Stack

