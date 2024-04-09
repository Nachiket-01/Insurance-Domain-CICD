# Web Application CI/CD Pipeline 🚀

![Web Application CI/CD Pipeline](https://github.com/Nachiket-01/Insurance-Domain-CICD/assets/65771120/8a1aac01-4472-4ebe-9908-5168e51cc7de)

This repository contains the code and configuration files for a web application CI/CD pipeline. The pipeline automates the build, testing, containerization, and deployment processes for the application.

## Prerequisites 🛠️

- Spring Boot Application
- Git
- Docker
- Testing (Selenium)
- CI/CD Tool (Jenkins)
- Artifact Repository (Docker Hub)
- Infrastructure as Code Tool (Kubernets/Ansible)
- Monitoring Tool (Grafana, Prometheus)

## Steps to Run ▶️

1. **Source Code Repository**:
   - Clone the repository: [Insurance-Domain-CICD](https://github.com/Nachiket-01/Insurance-Domain-CICD.git)

2. **Continuous Integration (CI)**:
   - Set up the CI tool of your choice (Jenkins).
   - Configure the CI tool to trigger a build whenever changes are pushed to the repository.
   - Define the build pipeline in the CI tool's configuration file (Jenkinsfile).

3. **Build Pipeline**:
   - The build pipeline should include the following steps:
     - Compiling the code.
     - Running unit tests and generating artifacts/reports.
     - Deploying on the main server.
     - In order to run the application, use port 8081.

## Microservice Development 🧪

To implement a proof of concept (POC), you are requested to develop a Mavenized microservice using Spring Boot and an in-memory H2 database.

### Microservice Development Steps

1. Develop a microservice which exposes the following endpoints as APIs and uses an in-memory H2 database to store the data:
   
   ![Microservice Endpoints](https://github.com/Nachiket-01/Insurance-Domain-CICD/assets/65771120/a00d9f1d-aed2-459c-9fd5-b58b425524be)

   - `/createPolicy` (HTTP Method: POST) (Request Body: JSON)
   - `/updatePolicy/{policy id}` (HTTP Method: PUT) (Request Body: JSON)
   - `/viewPolicy/{policy id}` (HTTP Method: GET) (No Request Body)
   - `/deletePolicy/{policy id}` (HTTP Method: DELETE) (No Request Body)
  
     ![Microservice Endpoint Example](https://github.com/Nachiket-01/Insurance-Domain-CICD/assets/65771120/c120b7bc-78d9-4da1-a9c9-4add7719f26c)

3. Write necessary JUnit test cases.
   
   ![JUnit Test Cases](https://github.com/Nachiket-01/Insurance-Domain-CICD/assets/65771120/69d5625c-ca49-4ffa-85b7-4543f021e40b)

4. Generate HTML report using TestNG.
   
   ![TestNG HTML Report](https://github.com/Nachiket-01/Insurance-Domain-CICD/assets/65771120/29faaee4-cb27-4ced-aceb-dfe67192c2ba)

   ![TestNG HTML Report](https://github.com/Nachiket-01/Insurance-Domain-CICD/assets/65771120/975b8ac9-c292-45bb-ab48-65c28a60ac5b)

   ![TestNG HTML Report](https://github.com/Nachiket-01/Insurance-Domain-CICD/assets/65771120/f23c37e7-019d-4c53-b3a9-4733b8172e70)

6. Push your code into your GitHub Repository.

**Note:** Preload some data into the database.

### Continuous Integration & Continuous Deployment 🔄

- **Git**: For version control to track changes in code files
  
  ![Git](https://github.com/Nachiket-01/Insurance-Domain-CICD/assets/65771120/41b97f39-04f6-4e70-97c2-e67d063576f0)

- **Jenkins**: For continuous integration and continuous deployment
  
  ![Jenkins](https://github.com/Nachiket-01/Insurance-Domain-CICD/assets/65771120/abb40028-49bf-4c67-afe7-8cd81167ed37)

  ![Jenkins](https://github.com/Nachiket-01/Insurance-Domain-CICD/assets/65771120/1637c421-4478-4606-ad89-fad48a535c8d)

  ![Jenkins](https://github.com/Nachiket-01/Insurance-Domain-CICD/assets/65771120/b3fff105-e027-4f2a-aafb-6d3748d703db)

  ![Jenkins](https://github.com/Nachiket-01/Insurance-Domain-CICD/assets/65771120/6fcc9af3-c268-4ebc-9d2f-e161c6295b2f)

  ![Jenkins](https://github.com/Nachiket-01/Insurance-Domain-CICD/assets/65771120/7cec8a24-86f8-41c8-8817-7bb5954e2b3f)

  ![Jenkins](https://github.com/Nachiket-01/Insurance-Domain-CICD/assets/65771120/2ebb5b92-a604-4e1d-baaa-c1d937402c56)

  ![Jenkins](https://github.com/Nachiket-01/Insurance-Domain-CICD/assets/65771120/c55898d9-43ce-40fd-930c-acd5fc94fe23)

  ![Jenkins](https://github.com/Nachiket-01/Insurance-Domain-CICD/assets/65771120/30ccfb9f-471b-410b-83a1-8f26242659da)

- **Test Server**:
  
  ![Test Server](https://github.com/Nachiket-01/Insurance-Domain-CICD/assets/65771120/5f1cdf22-b4f1-457c-b20a-2e2e0542dbea)

  ![Test Server](https://github.com/Nachiket-01/Insurance-Domain-CICD/assets/65771120/08821267-824d-4b81-a29b-ee6226338cfd)

  ![Test Server](https://github.com/Nachiket-01/Insurance-Domain-CICD/assets/65771120/aac9c23e-e118-4aa3-9b5e-e2538c4b2bf1)

- **Production Server**:
  
  ![Production Server](https://github.com/Nachiket-01/Insurance-Domain-CICD/assets/65771120/2e0476c1-74aa-4986-9efc-0d5604f77779)

- **Docker**: For deploying containerized applications

  ![Docker](https://github.com/Nachiket-01/Insurance-Domain-CICD/assets/65771120/58f7a552-1b64-4598-9684-e65191d85748)

- **Ansible**: Configuration management tool

  ![Ansible](https://github.com/Nachiket-01/Insurance-Domain-CICD/assets/65771120/50efdaa2-cdc9-4d6f-ba91-1491c7c88c2f)

  ![Ansible](https://github.com/Nachiket-01/Insurance-Domain-CICD/assets/65771120/e067d995-166b-4055-8072-3b416e3bead3)

- **Selenium**: For automating tests on the deployed web application

  ![Selenium](https://github.com/Nachiket-01/Insurance-Domain-CICD/assets/65771120/1e1c645f-6547-45e8-bdc8-fc42d6bed2e7)

  ![Selenium](https://github.com/Nachiket-01/Insurance-Domain-CICD/assets/65771120/041f62df-98ad-467d-81ed-8fba0fa2affb)

  ![Selenium](https://github.com/Nachiket-01/Insurance-Domain-CICD/assets/65771120/b5b641e7-0c12-414a-90e1-d48bd30ecff7)

  ![Selenium](https://github.com/Nachiket-01/Insurance-Domain-CICD/assets/65771120/7c1ac336-bcc9-45b6-b1f1-64e67c276b9b)

- **AWS**: For creating EC2 machines as servers and deploying the web application

  ![AWS](https://github.com/Nachiket-01/Insurance-Domain-CICD/assets/65771120/45ddca31-5137-4122-b7b9-d4cae777a6bc)

  ![AWS](https://github.com/Nachiket-01/Insurance-Domain-CICD/assets/65771120/e3b55ec7-c6bf-4b77-a848-7e78f32a2cb9)

## Business Challenge/Requirement 💼

As soon as the developer pushes the updated code on the Git master branch, the Jenkins job should be triggered using a GitHub Webhook. The code should be checked out, compiled, tested, packaged, containerized, and deployed to the preconfigured test-server automatically.

The deployment should then be tested using a test automation tool (Selenium), and if the build is successful, it should be deployed to the production server. All this should happen automatically and should be triggered from a push to the GitHub master branch.

## Resources 📚

- [Jenkins Documentation](https://www.jenkins.io/doc/)
- [Docker Documentation](https://docs.docker.com/)
- [Ansible Documentation](https://docs.ansible.com/)
- [Grafana Documentation](https://grafana.com/docs/grafana/latest/)
- [Prometheus Documentation](https://prometheus.io/docs/)

## Thank You! 🙏

Thank you for exploring our System!

If you have any questions, feedback, or suggestions, please feel free to reach out to us. We're here to help!

---

**Name:** **Nachiket Shinde**  
**Email:** nachiketshinde2001@gmail.com  
**Phone:** 9960096257  
**GitHub:** [Nachiket-01](https://github.com/Nachiket-01)  
**LinkedIn:** [Nachiket Shinde](https://www.linkedin.com/in/nachiket-shinde01/)
