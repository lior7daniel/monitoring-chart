# Monitoring Helm Chart

This Helm chart is designed to deploy a Kubernetes cluster with Prometheus and Node Exporter to monitor metrics and provide Grafana UI.

## Installation

### Prerequisites

- Helm installed on your system. If not installed, follow the instructions [here](https://helm.sh/docs/intro/install/).

### Add Repository

To add the `nanox-monitoring` Helm repository, run the following command:

```sh
sudo helm repo add nanox-monitoring https://lior7daniel.github.io/nanox-monitoring-chart
```

### Update Dependencies

Update the Helm chart dependencies by running:

```sh
sudo helm dependency update
```

### Install Helm Chart

To install the monitoring Helm chart, use the following command:

```sh
sudo helm install nanox nanox-monitoring/nanox
```

This will deploy Prometheus, Node Exporter, and Grafana on your Kubernetes cluster.
