Deploy Application on Kubernetes with Minikube

Overview:
This project demonstrates deploying a simple application on a local Kubernetes cluster using Minikube.
The application is containerized with Docker, deployed via Kubernetes manifests, and exposed through a NodePort service.

Files in this Repository
deployment.yaml – Defines the application deployment on Kubernetes.

service.yaml – Defines the service to expose the application.

Dockerfile  – Used to build a custom image.

screenshots/ – Contains proof of each step (Minikube start, pods, services, browser output).

Minikube start output:
<img width="1310" height="664" alt="Screenshot 2025-08-12 132436" src="https://github.com/user-attachments/assets/3a6dfea9-84b4-475d-8dd4-0bb1d73b8bd3" />

Pods running:
<img width="1297" height="688" alt="Screenshot 2025-08-12 124413" src="https://github.com/user-attachments/assets/d0c84a68-4811-4543-b750-ecf4deee0110" />

Services running:
<img width="1290" height="686" alt="Screenshot 2025-08-12 124619" src="https://github.com/user-attachments/assets/275315b1-714b-4f18-a70b-5e7508c00288" />

Application in browser:
<img width="1284" height="650" alt="Screenshot 2025-08-12 124652" src="https://github.com/user-attachments/assets/64ea2dad-3d3a-472d-a5a4-63abc0a65a27" />
