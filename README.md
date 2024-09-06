
# DevOps Challenge

This repository contains a DevOps challenge focusing on building a local Kubernetes environment, deploying Docker-based microservices, and automating the process using Pulumi.

## Assignment

Your task is to:
1. Set up a Kubernetes environment using a tool like **Minikube** or **KiND**.
2. Build Dockerfiles for the provided sample applications.
3. Use **Pulumi** to deploy the services to your Kubernetes cluster.
4. Ensure the API microservice is accessible externally and communicate with the job microservice internally.

## Steps

1. **Kubernetes Setup**:
   - Install and configure Kubernetes using Minikube/KiND.
   
2. **Docker Build**:
   - Create Dockerfiles for the provided applications ensuring correct functionality.

3. **Pulumi Deployment**:
   - Use Pulumi with your preferred language to automate the deployment of the services.
   
4. **Environment Variables**:
   - Ensure `JOBS_SERVICE` is available as an environment variable in the API container.

5. **Automation**:
   - Automate the process using scripts (shell, Makefile, etc.).

## Bonus

- Add **metrics** and monitoring (e.g., Prometheus).
- Apply **best practices** for container and pod security.

## Notes

- This process should be as automated as possible.
- Be prepared to discuss your solution and CI/CD improvements.

## References

- [Pulumi Documentation](https://www.pulumi.com/docs/)
- [Kubernetes Documentation](https://kubernetes.io/docs/)

