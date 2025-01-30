# Azure-AKS-Cluster-Subnet-Migration

Overview: This documentation provides a step-by-step guide on how to migrate an existing Azure Kubernetes Service (AKS) cluster from a smaller subnet to a larger subnet. The process includes adding new node pools, draining and deleting old node pools, backing up and restoring Pod Disruption Budgets (PDBs), and reconciling the cluster.

Prerequisites

Before starting the migration process, ensure that you have:

Azure CLI installed

Kubectl installed and configured to connect to your AKS cluster

Proper permissions to manage AKS resources in your Azure subscription

A backup of your existing configurations
