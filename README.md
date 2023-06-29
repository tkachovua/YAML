| NAME | PROMPT | DESCRIPTION | EXAMPLE |
|------|--------|-------------|---------|
| app.yaml | create an nginx deployment with 3 replicas | Defines the main deployment of the application, its containers, and configurations. | [app.yaml](app.yaml)|
| app-livenessProbe.yaml | create a live check every minute for nginx | Specifies the liveness probe settings for the application. | [app-livenessProbe.yaml](app-livenessProbe.yaml) |
| app-readinessProbe.yaml | create a readiness probe | Specifies the readiness probe settings for the application. | [app-readinessProbe.yaml](app-readinessProbe.yaml) |
| app-volumeMounts.yaml | create container with mount volume | Defines the volume mounts settings for the container.	 | [app-volumeMounts.yaml](app-volumeMounts.yaml) |
| app-cronjob.yaml | create cron job running daily monday rebooting nginx | Defines a scheduled job using CronJob. | [app-cronjob.yaml](app-cronjob.yaml) |
| app-job.yaml | create job rebooting server | Defines a one-time job that will be executed. | [app-job.yaml](app-job.yaml) |
| app-multicontainer.yaml | create multicontainer pod nginx with debian and FreeBSD | Defines a Pod that contains multiple containers working together. | [app-multicontainer.yaml](app-multicontainer.yaml) |
| app-resources.yaml | create manifest with cpu and memory resources. Cpu 10000m and memory 4096 | Defines resource limits and requests for the application. | [app-resources.yaml](app-resources.yaml) |
| app-secret-env.yaml | create secret environment for mangoDB | Defines secret data passed to the container as environment variables. | [app-secret-env.yaml](app-secret-env.yaml) |
