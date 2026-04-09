# MDE Linux Helm Chart Repository

Helm chart repository for Microsoft Defender for Endpoint on Linux.

## Usage

```bash
# Add this repo to Helm
helm repo add mde-linux https://zeeshan1995.github.io/mdatp-helm-charts
helm repo update

# Install the chart
helm install mde mde-linux/mdatp-linux --set onboarding.blob=<BASE64_BLOB>
```

## OpenShift Developer Catalog

Apply this on your OpenShift cluster to see the chart in the Developer Catalog:

```bash
oc apply -f helmchartrepository.yaml
```
