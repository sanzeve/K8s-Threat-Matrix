# Kubernetes Threat Matrix using MITRE ATT&CK Framework

## Overview

This repository provides a guide on creating a threat matrix specific to a Kubernetes (K8s) cluster, leveraging the MITRE ATT&CK framework. The threat matrix assists in understanding and mapping potential threats, tactics, and techniques relevant to K8s environments such as GKE, AKS, EKS

## Table of Contents

1. [Introduction](#introduction)
2. [Components of a K8s cluster](#Components)
3. [Techniques and Mitigation](#techniques-and-mitigation)
    - [Initial Access](#initial-access)
    - [Execution](#execution)
    - [Execution (Production)](#execution-production)
    - [Persistence](#persistence)
    - [Privilege Escalation](#privilege-escalation)
    - [Defense Evasion](#defense-evasion)
    - [Credential Access](#credential-access)
    - [Lateral Movement](#lateral-movement)
    - [Exfiltration](#exfiltration)
    - [Impact](#impact)

## Introduction

The MITRE ATT&CK framework is a knowledge base that describes the actions, tactics, and techniques employed by adversaries to compromise and operate within a specific environment. This repository focuses on applying the MITRE ATT&CK framework to Kubernetes clusters to enhance security posture and threat detection.

## Components of a K8s Cluster

Control Plane: set of components responsible for managing the overall state of the cluster (Brain of K8s cluster)

Worker Nodes: Machines that run containerised applications. They are managed by control plane

Kubelet: heart of worker node

Kube-Proxy: Kube Proxy maintains network rules on nodes. It enables communication across Pods within the cluster and also handles load balancing for services.

Container Runtime: The container runtime is responsible for pulling container images and running containers on each node.

Pod: smallest deployable units in K8s and represent a single instance of a running process

Container: lightweight, standalone software package that includes everything needed to run an application, including the code, runtime and libraries


## Techniques and Mitigation

### Initial Access

| Technique       | Description | Mitigation      |
|-----------------|-------------|-----------------|
| Misconfigured Kubernetes services e.g. exposed K8s API server, kubelet API, Kubernetes Dashboard, etcd API
            | 30          | Software Engineer|
| Mary            | 28          | Data Scientist  |
| Robert          | 35          | UX Designer     |


