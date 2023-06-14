# YAML


| NAME | PROMPT | DESCRIPTION | EXAMPLE |
|------|--------|-------------|---------|
| app.yaml | Deployment | Defines the main deployment of the application, its containers, and configurations. | [app.yaml](app.yaml)|
| app-livenessProbe.yaml | Liveness Probe | Specifies the liveness probe settings for the application. | [app-livenessProbe.yaml](app-livenessProbe.yaml) |
| app-readinessProbe.yaml | Readiness Probe | Specifies the readiness probe settings for the application. | [app-readinessProbe.yaml](app-readinessProbe.yaml) |
| app-volumeMounts.yaml | Volume Mounts | Defines the volume mounts settings for the container.	 | [app-volumeMounts.yaml](app-volumeMounts.yaml) |
| app-cronjob.yaml | CronJob | Defines a scheduled job using CronJob. | [app-cronjob.yaml](app-cronjob.yaml) |
| app-job.yaml | Job | Defines a one-time job that will be executed. | [app-job.yaml](app-job.yaml) |
| app-multicontainer.yaml | Pod with Multiple Containers | Defines a Pod that contains multiple containers working together. | [app-multicontainer.yaml](app-multicontainer.yaml) |
| app-resources.yaml | Resource Limits and Requests | Defines resource limits and requests for the application. | [app-resources.yaml](app-resources.yaml) |
| app-secret-env.yaml | Environment Variables with Secret Data | Defines secret data passed to the container as environment variables. | [app-secret-env.yaml](app-secret-env.yaml) |
