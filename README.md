# kubernetes-nginx-deployment
Deploying Nginx web server using Kubernetes
# Kubernetes Nginx Deployment

This project demonstrates how to deploy an Nginx web server using Kubernetes.

## Technologies
- Kubernetes
- Docker
- Nginx

## Architecture

Deployment creates nginx pods  
Service exposes the pods using NodePort

## Files

k8s/deployment.yaml – creates nginx pods  
k8s/service.yaml – exposes nginx service

## Commands

Apply deployment

kubectl apply -f deployment.yaml

Apply service

kubectl apply -f service.yaml

Check pods

kubectl get pods

Check services

kubectl get svc
