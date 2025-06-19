# FortiCNAPP OpenShift Feature Matrix (Private and Public Cloud)

| Category                        | What You Can Do in OpenShift                                                                                       |
|--------------------------------|--------------------------------------------------------------------------------------------------------------------|
| Misconfiguration Detection       | Yes — via IaC scanning (Terraform, Helm, Kustomize) in CI/CD or pre-deployment                                    |
| Compliance (CIS, PCI, NIST)     | Limited — Custom rules can be defined in FortiCNAPP                                                               |
| Cloud Workload Protection (CWP) | Yes — via DaemonSet agent for runtime visibility, behavior monitoring, and threat detection                       |
| Runtime Threat Detection         | Yes — Detects anomalies, lateral movement, crypto mining, privilege abuse, etc.                                   |
| Image Vulnerability Scanning     | Yes — via CI/CD pipelines and container registry scanning                                                          |
| Container Registry Integration   | Yes — Supports scanning container images from integrated registries                                                |
| Admission Webhook Enforcement    | Yes — Blocks deployments based on high/critical CVEs and policy violations using OPAL                              |
| RBAC & Identity Monitoring       | Yes — Captures identity activity via runtime agent and Kubernetes audit log integration                           |
| Network Activity Monitoring      | Yes — Tracks pod-to-pod and pod-to-external communication patterns                                                |
