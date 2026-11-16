# Hi, I'm Anish Choudhary 👋

### Build & Release Engineer | Embedded Linux | Platform Engineering | DevSecOps

I build and automate the systems that make software delivery reliable, secure and repeatable, from Yocto images for automotive hardware to CI/CD platforms on AWS and Kubernetes.

For 8+ years I've worked across automotive, embedded systems, smart metering and enterprise platforms. My work sits where Embedded Linux, Build & Release Engineering, Platform Engineering and DevSecOps meet. I'm interested in the whole path software takes:

**Build → Integrate → Test → Secure → Deploy → Monitor**

📍 Jaipur, India · [Portfolio](https://releaseopswithanish.in/) · [Writing](https://releaseopswithanish.in/blog/index.html) · [LinkedIn](https://www.linkedin.com/in/rj18-anish-choudhary/)

---

### What I Work On

**Embedded systems and build engineering.** I work on Yocto/OpenEmbedded and BitBake image builds, custom layers and recipes, SDK generation, cross-compilation with CMake, and OTA delivery. I also automate CI/CT for automotive software, where a build has to be reproducible and traceable months after release.

**Platform and cloud engineering.** I set up AWS and EKS platforms with reusable CI/CD frameworks, deploy with Docker and Helm, and automate infrastructure with Ansible. Observability is built in: Prometheus, Grafana, Elastic APM and OpenTelemetry.

**DevSecOps and software supply-chain security.** I build security gates that fail the build instead of filing a ticket: static analysis, dependency and container vulnerability scanning, SBOMs, and secret detection.

These are one discipline to me. The release pipeline that builds a Yocto image needs the same versioning, quality gates and traceability as the one that deploys a service to Kubernetes.

---

### Technology Stack

| Area | Used in professional work |
|---|---|
| **Build & Embedded** | Yocto Project, OpenEmbedded, BitBake, devtool, CMake, Linux, OTA packaging |
| **CI/CD & Release** | Jenkins (pipelines, shared libraries), GitLab CI, GitHub Actions, Git, JFrog Artifactory |
| **Cloud & Platform** | AWS, EKS, Kubernetes, Docker, Helm, Ansible, Istio |
| **DevSecOps & Quality** | SonarQube, OWASP Dependency-Check, Cppcheck, MISRA validation, Gitleaks, SBOM, vulnerability scanning |
| **Observability** | Prometheus, Grafana, Elastic APM, Elasticsearch, Kibana, Loki, OpenTelemetry |
| **Languages** | C, Python, Java/Groovy, Bash / Shell |

---

### Featured Work

**[Controller Clock](https://github.com/jenkinsci/controller-clock-plugin)**: a Jenkins plugin I wrote and maintain under the `jenkinsci` organisation, [published on the Jenkins plugin site](https://plugins.jenkins.io/controller-clock/). It shows the controller's time and timezone in the Jenkins UI and highlights when they differ from the user's browser timezone, so timestamps in build logs and schedules aren't misread.

**[Engineering notes](https://releaseopswithanish.in/blog/index.html)**: practical write-ups on CI/CD, embedded Linux, cloud and security, drawn from real build and production problems. A few to start with:

- [Reproducible Yocto builds in CI](https://releaseopswithanish.in/blog/reproducible-yocto-builds-in-ci.html)
- [The BitBake task chain, in order](https://releaseopswithanish.in/blog/the-bitbake-task-chain.html)
- [Security gates should fail the build, not file a ticket](https://releaseopswithanish.in/blog/security-gates-that-fail-the-build.html)
- [Jenkins shared libraries, pinned and safe with strings](https://releaseopswithanish.in/blog/jenkins-shared-libraries-pinned-and-safe.html)
- [Helm upgrades that roll themselves back](https://releaseopswithanish.in/blog/helm-upgrades-that-roll-back.html)
- [Clearing node CVEs on EKS: replace the nodes, then read the PDBs](https://releaseopswithanish.in/blog/eks-node-group-cve-upgrade.html)

---

### Currently Building

I'm starting three open-source labs that put this work in public. They aren't published yet; this section will link to each one when it is.

- **yocto-build-lab**: reproducible Yocto/BitBake builds and CI for embedded Linux.
- **secure-ci-blueprint**: a CI/CD pipeline with security gates (static analysis, SBOM, vulnerability and secret scanning).
- **platform-observability-lab**: monitoring and observability for a Kubernetes platform.

---

### Engineering Impact

Results from my professional roles:

- **90% less manual effort** after building a CI/CT platform for automotive software delivery (Mobile Drive Technology).
- **60% fewer integration and deployment errors** after establishing a CI/CD ecosystem (Sirius Embedded Software).
- **75% fewer code defects** after integrating static analysis and security checks (Sirius Embedded Software).
- Improved build and validation workflows for Yocto/OpenEmbedded-based embedded Linux platforms.
- Set up greenfield AWS platforms with reusable CI/CD frameworks and centralised observability (PwC India).

---

### Professional Experience

| Company | Role | Focus |
|---|---|---|
| **PwC India** | Senior Associate | Cloud DevSecOps |
| **Mobile Drive Technology** | Senior Engineer, Product Management | Automotive CI/CT, Yocto & Embedded Linux |
| **Wipro** | Senior Engineer | Yocto, Embedded Linux & Build Automation |
| **Landis+Gyr** | Senior Engineer, SCM | Smart Metering & DevOps |
| **Netradyne** | Build & Release Engineer | Automotive Software |
| **Sirius Embedded Software** | Member of Technical Staff | Embedded Systems, Yocto & Release Engineering |

---

### Certifications & Education

- **KCNA: Kubernetes and Cloud Native Associate**, The Linux Foundation
- **B.Tech., Electronic Instrumentation and Control System**, Rajasthan Technical University, Kota
- **Embedded Systems & Design Training**, CDAC Knowledge Park, Bangalore

---

### Currently Exploring

- Yocto build systems and Embedded Linux development
- Linux internals and system programming
- CI/CD architecture and build optimisation
- Software supply-chain security
- Kubernetes, AWS and cloud infrastructure
- Automation, scripting and distributed systems

---

### Let's Collaborate

I'm happy to talk about:

- Yocto and BitBake build problems, especially reproducibility and build times.
- CI/CD pipeline design, Jenkins shared libraries and release governance.
- Adding security gates to a pipeline without stalling delivery.
- Contributions to the labs above once they're public. Issues and PRs are welcome.

The easiest way to reach me is [LinkedIn](https://www.linkedin.com/in/rj18-anish-choudhary/), or open an issue on one of my repositories.
