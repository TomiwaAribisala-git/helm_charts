# Helm Charts for (Demo Cloud-Native Microservices Application)[https://github.com/TomiwaAribisala-git/microservices-demo]

# Clone the Chart 
```
git clone https://github.com/TomiwaAribisala-git/microservices_helm_charts.git
```

# Prerequisites
Install (Helm)[https://helm.sh/docs/intro/install/]


# Helm Template and Helm Lint Commands
Helm Template command renders the chart template in accordance with a selected values file and display its output, Helm Lint examines a chart template in accordance with a selected values file for possible issues.

```
helm template -f redis-values/redis-values.yaml redis
```
```
helm lint -f redis-values/redis-values.yaml redis
```

```
helm template -f values/ad-values.yaml microservice
```
```
helm lint -f values/ad-values.yaml microservice
```

# Deploy Microservices with Helmfile