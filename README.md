# Rancher 2.0 Catalogs

```
charts/<APPLICATION>/<APP_VERSION>/
|--charts/           # Directory containing dependency charts.
|--templates/        # Directory containing templates that, when combined with values.yml, generates Kubernetes YAML.
|--app-readme.md     # Text displayed in the charts header within the Rancher UI.*
|--Chart.yml         # Required Helm chart information file.
|--questions.yml     # Form questions displayed within the Rancher UI. Questions display in Configuration Options.*
|--README.md         # Optional: Helm Readme file displayed within Rancher UI. This text displays in Detailed Descriptions.
|--requirements.yml  # Optional: YAML file listing dependencies for the chart.
|--values.yml        # Default configuration values for the chart.
```