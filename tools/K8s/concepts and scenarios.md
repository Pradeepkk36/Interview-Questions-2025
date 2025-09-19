# kubernetes interview questions with advanced concepts and scenarios #

# Basic Level
- Explain the control plane components and their functionalities, and how they interact with each other.
- Explain how the kube-proxy component works on the node.
- Explain the CNI and CRI interfaces.
- How to troubleshoot etcd iss

# Intermediate Level
- Explain the core components and benefits of a service mesh like Istio or Linkerd.
- Describe how traffic management (e.g., canary deployments, A/B testing)  is implemented using a service mesh.
- Discuss the security implications and best practices for implementing mutual TLS (mTLS)  in a service mesh.
- How do you troubleshoot a performance issue originating from the service mesh?
- Explain the differences between ClusterIP, NodePort, LoadBalancer, and Ingress services.
- Describe how you would implement a multi-cluster ingress solution.
- Discuss the challenges of implementing network policies and how you would troubleshoot network connectivity issues within a Kubernetes cluster.
- Explain how to implement and troubleshoot egress network policies.
- Explain the differences between PersistentVolumes (PVs), PersistentVolumeClaims (PVCs), and StorageClasses.

# Advance Level 
- Describe how you would implement dynamic provisioning of persistent storage for stateful applications.
- Discuss the challenges of managing stateful applications in Kubernetes and how you would ensure data consistency and availability.
- How to take and restore a snapshot of a persistent volume?

# K8s Best Practices(Security):
- Describe how you would implement role-based access control (RBAC) to restrict access to Kubernetes resources.
- Discuss the importance of container image security and how you would implement image scanning and vulnerability management.
- Explain how you would implement secrets management using Kubernetes Secrets or an external secrets management solution (e.g., HashiCorp Vault).
- How would you implement and enforce pod security policies, and how have pod security standards changed the landscape?
- Describe how you would implement a comprehensive monitoring and logging solution for a Kubernetes cluster.
- Discuss the importance of distributed tracing and how you would implement it using tools like Jaeger or Zipkin.
