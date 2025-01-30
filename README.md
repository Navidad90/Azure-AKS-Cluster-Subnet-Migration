# Azure-AKS-Cluster-Subnet-Migration

## Table of Contents

1. [Step 1: Creating a New Subnet]
2. [Step 2: Adding a New Node Pool]
3. [Step 3: Migrating Workloads]
4. [Step 4: Removing the Old Node Pool]
5. [Step 5: Backing Up PDBs]
6. [Step 6: Restoring Up PDBs]
7. [Step 7: Reconciling the Cluster]
8. [Step 8: Deleting the PDBs]
9. [Verification and Final Checks]

Overview: 

This documentation provides a step-by-step guide on how to migrate an existing Azure Kubernetes Service (AKS) cluster from a smaller subnet to a larger subnet. The process includes adding new node pools, draining and deleting old node pools, backing up and restoring Pod Disruption Budgets (PDBs), and reconciling the cluster.

Prerequisites:

Before starting the migration process, ensure that you have:

Azure CLI installed

Kubectl installed and configured to connect to your AKS cluster

Proper permissions to manage AKS resources in your Azure subscription

A backup of your existing configurations
