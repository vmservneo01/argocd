## ArgoCD Applications per YKS Cluster

Name of the folder represent name of the YKS Cluster (Except HelmCharts).

```
├── demo-dev         # YKS Cluster name
│   ├── applications
│   │   ├── app1.yaml
│   │   ├── app2.yaml
│   │   ├── app3.yaml
│   │   ├── app4.yaml
│   │   └── app5.yaml
│   └── root.yaml    # Root ArgoCD Application
├── HelmCharts       # All Helm Charts
│   ├── MyChart1
│   │   ├── Chart.yaml
│   │   └── templates
│   │       ├── deployment.yaml
│   │       ├── nginx.yaml       # Default Values
│   │       └── service.yaml
│   ├── MyChart2
│   │   ├── Chart.yaml
│   │   └── templates
│   │       ├── deployment.yaml
│   │       ├── service.yaml
│   │       └── tomcat.yaml      # Default Values
│   ├── MyChart3
│   │   ├── Chart.yaml
│   │   └── templates
│   │       ├── deployment.yaml
│   │       ├── service.yaml
│   │       └── webtest1.yaml    # Default Values
│   ├── MyChart4
│   │   ├── Chart.yaml
│   │   └── templates
│   │       ├── deployment.yaml
│   │       ├── service.yaml
│   │       └── webtest2.yaml    # Default Values
│   └── MyChart5
│       ├── Chart.yaml
│       └── templates
│           ├── deployment.yaml
│           ├── flatris.yaml     # Default Values
│           └── service.yaml
└── README.md
```

