# Andrew Ciomperlik — IT Portfolio

Personal portfolio website showcasing my IT experience, certifications, technical projects, homelab infrastructure, cloud deployments, and ongoing professional development.

This repository contains the **source code and content for the portfolio website itself**. The Azure infrastructure and deployment configuration used to host the site are maintained separately in the **Azure Static Web App** project repository.

---

## About the Portfolio

This portfolio was created to document hands-on projects and demonstrate practical experience across areas including:

- Linux system administration
- Windows Server and Active Directory
- Docker and containerization
- Networking and DNS
- Cybersecurity
- Microsoft Azure
- High availability and redundancy
- Infrastructure automation
- Backup and disaster recovery
- Self-hosted infrastructure

The site serves as a central location for documenting projects beyond what can reasonably be included on a traditional resume.

---

## Technology Stack

The portfolio website is built using:

- **Hugo** — Static site generator
- **Hugo Profile** — Portfolio theme
- **HTML / CSS**
- **YAML** — Hugo site configuration
- **Git**
- **GitHub**
- **Azure Static Web Apps** — Production hosting

---

## Repository Purpose

This repository is intentionally focused on the **portfolio website itself**.

It contains items such as:

```text
portfolio/
├── content/
├── layouts/
├── static/
├── themes/
├── hugo.yaml
├── .gitignore
├── LICENSE
└── README.md
```

Cloud infrastructure and deployment configuration are maintained in a separate repository.

This separation keeps the website source clean while allowing the Azure deployment to be documented independently as its own technical project.

---

## Related Project

### Azure Static Web App Deployment

The production portfolio is hosted using **Microsoft Azure Static Web Apps**.

The Azure project is maintained separately and documents the cloud-hosting portion of the environment, including:

- Azure Static Web Apps
- GitHub integration
- Continuous deployment
- Custom domain configuration
- DNS configuration
- HTTPS/TLS
- Azure resource configuration

**Repository:**  
`<ADD LINK TO AZURE STATIC WEB APP REPOSITORY>`

This separation allows the two repositories to demonstrate different skill sets:

| Repository | Primary Focus |
|---|---|
| **Portfolio Website** | Hugo, web content, project presentation, Git |
| **Azure Static Web App** | Azure, cloud hosting, DNS, CI/CD, deployment |

---

## Featured Projects

The portfolio documents several hands-on infrastructure and technology projects.

### Highly Available Secure Homelab Infrastructure

A multi-host infrastructure environment built around a Raspberry Pi and Orange Pi with redundant network services.

Technologies and concepts include:

- AdGuard Home
- Unbound
- HAProxy
- Caddy
- DNS-over-TLS
- DNS-over-HTTPS
- DNSSEC
- Docker
- Docker Compose
- Redundant DNS
- Service synchronization
- TLS certificates
- Backup and recovery

---

### Containerized Homelab Infrastructure

A collection of self-hosted applications and infrastructure services deployed using Docker and Docker Compose.

The project demonstrates:

- Container deployment
- Persistent storage
- Docker networking
- Reverse proxy configuration
- Internal DNS
- HTTPS
- Container monitoring
- Service management
- Multi-host container environments

---

### Azure Static Web App

Deployment of this portfolio website to Microsoft Azure using Azure Static Web Apps.

The project demonstrates:

- Azure cloud services
- Static website hosting
- GitHub-based deployment
- Custom domains
- DNS configuration
- HTTPS
- Cloud resource management

---

## Local Development

### Prerequisites

Install Hugo before running the site locally.

Verify the installation:

```bash
hugo version
```

### Clone the Repository

```bash
git clone <PORTFOLIO-REPOSITORY-URL>
cd <PORTFOLIO-REPOSITORY>
```

### Start the Development Server

```bash
hugo server
```

Then open:

```text
http://localhost:1313
```

Hugo will automatically rebuild the site when local files are modified.

---

## Production Deployment

Production deployment is handled through the Azure Static Web Apps environment documented in the separate Azure repository.

The general workflow is:

```text
Local Development
        │
        ▼
      Git
        │
        ▼
     GitHub
        │
        ▼
Azure Static Web Apps
        │
        ▼
Production Portfolio
```

Changes committed to the appropriate branch can be deployed through the Azure/GitHub integration.

---

## Project Goals

This portfolio is intended to:

1. Document hands-on IT projects.
2. Demonstrate technical skills beyond certification knowledge.
3. Provide examples of real infrastructure configuration and troubleshooting.
4. Track continued professional development.
5. Demonstrate experience with Git and GitHub workflows.
6. Provide technical documentation that can be reviewed by potential employers.
7. Show progression from support-focused IT work toward systems, networking, cloud, and cybersecurity roles.

---

## Security

Sensitive information is not intentionally stored in this repository.

Secrets and environment-specific information such as the following should not be committed:

- API keys
- Passwords
- Private keys
- Access tokens
- Credentials
- Environment files containing secrets
- Private certificates
- Internal configuration containing sensitive information

Sensitive values are excluded through `.gitignore` or replaced with example values where appropriate.

---

## License

The source code and configuration created specifically for this portfolio are licensed under the **MIT License**.

Copyright © 2026 Andrew Ciomperlik.

See the [LICENSE](LICENSE) file for details.

Third-party software, themes, libraries, images, and other dependencies remain subject to their respective licenses.

Personal portfolio content, resume information, project descriptions, photographs, logos, and other personal media are not licensed for reuse unless otherwise stated.

---

## Author

**Andrew Ciomperlik**

IT professional focused on systems administration, networking, cloud technologies, cybersecurity, Linux, and containerized infrastructure.

- GitHub: [github.com/andciom](https://github.com/andciom)
- Portfolio: `<ADD PORTFOLIO URL>`

---

## Status

This portfolio is actively maintained and will continue to evolve as new projects, certifications, technologies, and infrastructure environments are completed.

## License

The source code and configuration in this repository are licensed under
the MIT License. See [LICENSE](LICENSE) for details.

Copyright © 2026 Andrew Ciomperlik.

Unless otherwise noted, personal portfolio content, project descriptions,
resume information, photographs, logos, and other original media are not
licensed for reuse.
