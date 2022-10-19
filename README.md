# GPU-Utilization-Dashboard
A Grafana dashboard that gives you a deep yet simple visualization of the GPU Utilization in you cluster.

## Prerequisites

### Prometheus
[Setting Up Prometheus](https://docs.nvidia.com/datacenter/cloud-native/gpu-telemetry/dcgm-exporter.html#setting-up-prometheus)

### Nvidia-dcgm-exporter
The easiest way is to install nvidia's [gpu-operator](https://docs.nvidia.com/datacenter/cloud-native/gpu-operator/getting-started.html#install-nvidia-gpu-operator),
that will have dcgm-exporter built-in.

Else, use [this guide](https://docs.nvidia.com/datacenter/cloud-native/gpu-telemetry/dcgm-exporter.html#setting-up-dcgm)
to install dcgm-exporter directly.

### Grafana
[Using Grafana](https://docs.nvidia.com/datacenter/cloud-native/gpu-telemetry/dcgm-exporter.html#using-grafana)

## Import the Dashboard
Using the [guide](https://grafana.com/docs/grafana/v9.0/dashboards/export-import/#import-dashboard),
upload "gpu_utilization.json" as a _.json_ file.
