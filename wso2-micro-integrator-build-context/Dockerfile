# wso2 micro integrator with jmx exporter from bitnami

FROM wso2/wso2mi:4.0.0

WORKDIR ${WSO2_SERVER_HOME}

COPY --from=bitnami/jmx-exporter:latest --chown=wso2carbon:wso2 /opt/bitnami/jmx-exporter/jmx_prometheus_javaagent.jar bin
