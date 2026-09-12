# Argo CD GitOps Practice Repository

## 📌 Overview
This repository is created to **practice GitOps with Argo CD**.  
It acts as the **source of truth** for Kubernetes manifests.  
Argo CD will continuously sync the cluster state with the files stored here.

---

## 🔹 What is GitOps?
- GitOps is a methodology where **Kubernetes manifests** are stored in Git.  
- Git becomes the **single source of truth** for deployments.  
- Any change in Git → Argo CD applies it to the cluster.

---

## 🔹 What is Argo CD?
- Argo CD is a **GitOps tool**.  
- It compares the manifests in Git with the resources running in the cluster.  
- If they match → no action.  
- If they differ → Argo CD **creates or updates** resources to match Git.

---
