# Lab 6 — Kubernetes Deployment for Churn Prediction API

This lab demonstrates a full MLOps deployment pipeline using Docker + Kubernetes + Minikube, including ConfigMap, Secrets, Probes, PVC, Jobs and Drift Detection for a Machine Learning API (Churn Prediction).

---

## 🚀 Objectives

- Containerize a FastAPI Machine Learning service
- Deploy it on Kubernetes via Minikube
- Inject runtime configuration using ConfigMaps & Secrets
- Add readiness / liveness / startup probes
- Persist logs & registry using PVC
- Execute Kubernetes Jobs for model training
- Run drift monitoring inside Pods

---
