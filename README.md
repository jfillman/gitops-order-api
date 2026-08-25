# gitops-order-api

GitOps deployment repo for `order-api`, scaffolded by `SpringBootApplication`
(idp-service-catalog). Empty until this app's first `ApplicationEnvironment`
resource is created - each environment gets its own `<cluster>/<env>/values.yaml`
here, rendered by `idp-application` (idp-service-catalog's shared Helm chart).
