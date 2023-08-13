# Helm Charts for [Demo Cloud-Native Microservices Application](https://github.com/TomiwaAribisala-git/microservices-demo)

# Clone the Charts 
```
git clone https://github.com/TomiwaAribisala-git/microservices_helm_charts.git
```

# Prerequisites
Install [Helm](https://helm.sh/docs/intro/install/)


# Helm Template and Helm Lint Commands
Helm Template renders the chart template in accordance with a selected values file and displays its output, Helm Lint examines a chart template in accordance with a selected values file for possible issues.

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

```
helm template -f values/cart-values.yaml microservice
```
```
helm lint -f values/cart-values.yaml microservice
```

```
helm template -f values/checkout-values.yaml microservice
```
```
helm lint -f values/checkout-values.yaml microservice
```

```
helm template -f values/currency-values.yaml microservice
```
```
helm lint -f values/currency-values.yaml microservice
```

```
helm template -f values/email-values.yaml microservice
```
```
helm lint -f values/email-values.yaml microservice
```

```
helm template -f values/frontend-values.yaml microservice
```
```
helm lint -f values/frontend-values.yaml microservice
```

```
helm template -f values/payment-values.yaml microservice
```
```
helm lint -f values/payment-values.yaml microservice
```

```
helm template -f values/product-values.yaml microservice
```
```
helm lint -f values/product-values.yaml microservice
```

```
helm template -f values/recommendation-values.yaml microservice
```
```
helm lint -f values/recommendation-values.yaml microservice
```

```
helm template -f values/shipping-values.yaml microservice
```
```
helm lint -f values/shipping-values.yaml microservice
```
# Deploy Microservices with Helmfile