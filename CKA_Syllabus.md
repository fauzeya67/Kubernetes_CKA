# 📘 Certified Kubernetes Administrator (CKA) -- Official Syllabus

This document outlines the official syllabus for the Certified
Kubernetes Administrator (CKA) certification, offered by the Linux
Foundation in collaboration with the Cloud Native Computing Foundation
(CNCF).

The CKA exam is 100% performance-based and conducted on a live
Kubernetes cluster.

------------------------------------------------------------------------

## 🧩 Exam Overview

-   **Certification:** Certified Kubernetes Administrator (CKA)
-   **Exam Type:** Hands-on / Practical
-   **Duration:** 2 hours
-   **Number of Questions:** \~15--20 performance-based tasks
-   **Passing Score:** As defined by Linux Foundation (typically \~66%)
-   **Documentation Allowed:** Official Kubernetes documentation only
-   **Kubernetes Version:** Aligned with the current exam version

------------------------------------------------------------------------

# 📌 Official Exam Domains & Weightage

  Domain                                               Weight
  ---------------------------------------------------- --------
  Cluster Architecture, Installation & Configuration   25%
  Workloads & Scheduling                               15%
  Services & Networking                                20%
  Storage                                              10%
  Troubleshooting                                      30%

------------------------------------------------------------------------

# 1️⃣ Cluster Architecture, Installation & Configuration (25%)

## Kubernetes Architecture

-   Understand Kubernetes cluster architecture
-   Understand control plane components:
    -   kube-apiserver
    -   kube-controller-manager
    -   kube-scheduler
    -   etcd
-   Understand worker node components:
    -   kubelet
    -   kube-proxy
    -   container runtime

## Cluster Setup & Management

-   Install Kubernetes using kubeadm
-   Design and configure Kubernetes clusters
-   Configure High Availability (HA) control plane
-   Upgrade Kubernetes clusters (control plane and worker nodes)
-   Backup and restore etcd
-   Manage Kubernetes certificates

## Security & Access

-   Configure and manage RBAC:
    -   Roles
    -   ClusterRoles
    -   RoleBindings
    -   ClusterRoleBindings
    -   ServiceAccounts
-   Understand authentication & authorization mechanisms

## Extensions

-   Understand and manage:
    -   Custom Resource Definitions (CRDs)
    -   Admission Controllers
    -   Cluster extensions

------------------------------------------------------------------------

# 2️⃣ Workloads & Scheduling (15%)

## Workload Management

Deploy and manage: - Pods - Deployments - ReplicaSets - StatefulSets -
DaemonSets - Jobs - CronJobs

## Updates & Scaling

-   Perform rolling updates and rollbacks
-   Scale workloads manually
-   Understand autoscaling concepts (HPA basics)

## Configuration & Resources

-   Configure and use:
    -   ConfigMaps
    -   Secrets
-   Understand and configure:
    -   Resource requests
    -   Resource limits

## Scheduling

-   Configure scheduling using:
    -   Node selectors
    -   Node affinity / anti-affinity
    -   Taints and tolerations

------------------------------------------------------------------------

# 3️⃣ Services & Networking (20%)

## Networking Fundamentals

-   Understand Kubernetes networking model
-   Configure Pod-to-Pod communication

## Services

Create and manage: - ClusterIP - NodePort - LoadBalancer

## Ingress & DNS

-   Understand and configure:
    -   Ingress
    -   Ingress Controllers
-   Configure and troubleshoot CoreDNS

## Network Security

-   Implement and manage Network Policies
-   Understand CNI concepts (operational level)

------------------------------------------------------------------------

# 4️⃣ Storage (10%)

## Storage Concepts

-   Understand Kubernetes storage architecture

## Persistent Storage

Configure and manage: - PersistentVolumes (PV) - PersistentVolumeClaims
(PVC) - StorageClasses

Understand: - Access modes - Reclaim policies - Dynamic volume
provisioning

## Workload Integration

-   Attach and manage storage for Pods and workloads

------------------------------------------------------------------------

# 5️⃣ Troubleshooting (30%)

## Application Troubleshooting

-   Troubleshoot Pods:
    -   Pending
    -   CrashLoopBackOff
    -   ImagePullBackOff
-   Debug application failures

## Networking & Services

-   Troubleshoot Service connectivity issues
-   Debug DNS and network-related problems

## Node & Cluster Issues

-   Troubleshoot node failures
-   Troubleshoot control plane components

## Observability & Debugging

-   Analyze:
    -   Pod logs
    -   Node logs
    -   Control plane logs
-   Use events and metrics for debugging
-   Identify and fix misconfigurations efficiently

------------------------------------------------------------------------

# 🧠 Important Notes

-   The exam is hands-on only (no multiple-choice questions).
-   Speed and accuracy are critical.
-   Strong command-line skills are essential.
-   Practice directly on Kubernetes clusters.
-   Use `kubectl` efficiently (aliases and shortcuts recommended).

