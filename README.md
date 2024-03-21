Domain Parking Page
============
![Error!](https://github.com/callowaysutton/docker-parking-page/actions/workflows/docker-image.yml/badge.svg) ![Error!](https://github.com/callowaysutton/docker-parking-page/actions/workflows/trivy.yml/badge.svg)
## Overview:
In the digital landscape, there are times when websites are under construction or domains are parked temporarily. During these periods, it's crucial to have a placeholder page to inform visitors about the status of the website and provide relevant information. Docker containers offer a convenient way to deploy such placeholder pages quickly and efficiently.

The Docker container for a "Website Under Construction/Parked Domain" service provides a lightweight, portable, and scalable solution for hosting temporary pages. It allows web developers, designers, and domain owners to easily deploy a customizable placeholder page without the need for complex server configurations.

## Example Usage:
```bash
docker run -it --rm -p 3000:3000 callowaysutton/parking-page
```

## Key Features:

1. **Easy Deployment:** Deploying the Docker container is simple and straightforward. Users can pull the container image from a Docker registry or build it locally from a Dockerfile. Once the container is running, the placeholder page is accessible to visitors.

2. **Scalability:** Docker containers are inherently scalable, allowing users to deploy multiple instances of the placeholder page to handle increased traffic during peak periods. Container orchestration tools like Kubernetes can be used to manage and scale the containers dynamically.

3. **Resource Efficiency:** This Docker container was built to be as small as possible for faster deployments and minimal headache when it comes to image management on hosts.

4. **Portability:** Docker containers encapsulate all the dependencies and configurations required to run the placeholder page, making them highly portable. Users can easily migrate the container between different environments, such as development, staging, and production.

5. **Security:** As this image is focused on being as lightweight, small and efficient as possible, there is little to no surface area for any type of attack. All system tools besides busybox have been removed, allowing for a lean design and 0 detected vulnerabilities through Docker Scout and several other open source container scanning softwares.

6. **Integration with CI/CD Pipelines:** The Docker container can be seamlessly integrated into continuous integration and deployment pipelines. Changes to the placeholder page can be automatically built, tested, and deployed using tools like Jenkins or GitLab CI/CD.

## 🙌 Thanks to:

- [martylouis](https://github.com/martylouis/domain-parking-page) for the original page!
- [Ian Espinosa](https://unsplash.com/@greystorm) for the background image. [View on Unsplash](https://unsplash.com/photos/Ws92xzbSris)
- [Fitty](https://github.com/rikschennink/fitty) for fitting text perfectly inside it's container with vanilla javascript.
