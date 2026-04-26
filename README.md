# **Christopher J. Smith** - Software Engineer & Systems Architect

**csmith4work@gmail.com**

## Professional Summary
Software engineer and systems architect, experienced in building and scaling infrastructure platforms across startups and Fortune 500 companies. Founder of Nya, an open-source self-hosted PaaS built in Rust — the culmination of a career spent observing how infrastructure platforms succeed and fail at scale. Specializes in platform architecture, infrastructure automation, and full-stack delivery. Driven by a belief that developers and creators deserve ownership over their own infrastructure.

## Core Skills

#### Languages and Frameworks
- Rust, Typescript, React, C#, Vue, Python, GraphQL, Node

#### Infrastructure and DevOps
- Kubernetes, K3s, Helm, Docker, Terraform, MetalLB, BIND9, NGINX, GitHub Actions, Jenkins, ArgoCD, CircleCi

#### Cloud
- AWS (EC2, ECS, ECR, IAM, S3, CloudFront, CodeBuild, CodePipeline, Lambda, SNS, SQS, Secrets Manager, Parameter Store, RDS, VPC, CloudWatch)
- GCP (Cloud Run, OAuth, Firebase, Service Accounts)
- Azure (ACR, ACI)

#### Data
- PostgreSQL, DynamoDb, MongoDb, SQL Server

#### Networking
- Cloudflare, Route53

#### Automation, Configuration, and Scripting
- JSON, YAML, Git, Bash

#### Observability
- Splunk, Wavefront, New Relic, Opsgenie, Sentry, PagerDuty

#### Testing
- Jest, Artillery, XUnit

## Education

**Bachelor of Science in Computer Science, Minor in Mathematics** *- May 2016,
Tennessee State University*

## Professional Experience

### Founder and Lead Architect @ Nya (Open Source)
#### Dec 2024 - present
(https://github.com/CYBRSMTH/nya)

- Designed and built an open-source self-hosted PaaS CLI in Rust, wrapping K3s, MetalLB, BIND9, Helm, and nginx-ingress into a single provisioning command. 
- Engineered custom scaffolding application framework that provides an "on-rails" experience for platform level development.  
- Replaced Ansible with direct SSH orchestration and eliminated a major external dependency.
- Architected an event-driven async runtime using Tokio, Arc-based session sharing, CancellationToken, and TaskTracker for safe concurrent SSH task execution across multi-node clusters.
- Made key systems design decisions including compile-time script embedding, Tera templating, and a prelude pattern to reduce cross-module boilerplate
- Published to crates.io as nya_cloud; soft-launched publicly on GitHub and Bluesky with an active issue backlog and contribution guidelines.

### Senior Software Engineer, Intuit Data Exchange(IDX) @ Intuit
#### June 2024 – present

- Architected a ground-up redesign of the Integrations data model, eliminating developer friction and consolidating two divergent connection flows into a single unified experience across all offering types.
- Engineered the platform's Integration Launch widget end-to-end, from integration creation through dynamic connection resolution to dynamic collection of user settings. Introduced a self-serve entry point that aggregates integration configuration within the platform.
- Drove runtime-dynamic connection property resolution, removing hardcoded configuration dependencies and improving maintainability at scale across the platform.
- Designed and shipped reusable UI components adopted across multiple integration teams, expanding platform capabilities without requiring custom one-off implementations
- Unblocked multiple partner and POS integration teams by directly triaging platform-level blockers, maintaining delivery velocity across parallel workstreams
- Led or contributed to dozens of successful third-party integration efforts, becoming the primary point of contact and subject matter expert across product teams.
- Implemented new analytics and observability features, improved developer workflows, created and maintained platform documentation, participated in cross team architecture discussions, and contributed code across teams to sustain delivery momentum and unblock product initiatives. 
- Created custom Claude Code skill that combines knowledge of the system with common issue triaging techniques, reducing issue resolution time by 75%.

### Senior Application Engineer @ HCA
#### April 2023 – April 2024
- Researched, developed, documented and presented a proof-of-concept CI/CD pipeline for our applications that leveraged Docker, NGINX, Github Actions, Azure Container Registry and Azure Container Instances.
- Created a new framework for local development that simplifies and automates changing the application's behavior based on configuration and environment. 
- Led team through a successful application rewrite of a React dashboard. Designed new project architecture, delegated tasks among the team, and delivered the new and improved application on time. 
- Managed project complexity and consistently switched between contexts as I was entrusted to contribute to 5 dashboards that covered 3 different initiatives.
- Integrated a new React homepage for employees with third-party services and APIs using the provided API Gateway created by Infor.
- Mentored and assisted junior developers with application development. Delegated tasks that suited their technical experience. Provided personal experience and code reviews to help develop growth and reinforce software best practices.

### Cloud Platform Engineer II @ Butterfly Network
#### Dec 2021 – Jan 2023

- Coordinated and led the architecting of a system-wide monitoring and alerting system, seamlessly integrating AWS Route 53 Health Checks with NewRelic and Opsgenie.
- Consulted with a separate team and implemented the deployment pipeline for a brand new mobile Proof of Concept (POC) onto an established Kubernetes architecture leveraging Helm, Github Actions, and Terraform.
- Successfully orchestrated the migration of an e-commerce front-end from a legacy AWS architecture to a modern setup, taking the lead in configuring and maintaining the front-end using Cloudfront.
- Managed and coordinated 20+ application deployments to staging and production environments using CircleCI.
- Led a dynamic team in a Hackathon, innovating, testing, and presenting metrics for a robust load testing framework employing Artillery.
- Diligently participated in a 24x7 on-call rotation, providing support to the newly instituted Kubernetes architecture while also maintaining the legacy architecture established on Aptible.
- Authored and presented several Architecture Design documents to a Design Review committee, ensuring alignment and approval before project execution.

### Software Engineer @ SmileDirectClub
#### March 2019 – Dec 2021

- Contributed to the breakdown of three sections of the company’s monolithic e-commerce application into microservices, enhancing system maintainability and scalability.
- Crafted and deployed microservices using .Net Core and DynamoDb through a CI/CD pipeline leveraging Jenkins, Docker, AWS, and Terraform.
- Authored and integrated front-end and back-end unit and integration tests into the CI/CD pipeline, ensuring robust and reliable software delivery.
- Seamlessly integrated a microservice with the RioSEO third-party API, automating a critical business process and resulting in annual savings of at least $50,000 through reduced manual data entry.
- Enhanced and maintained the company's Component Library by adding and refactoring components using Vue.js and Bootstrap, promoting reusability and consistent UI/UX.
- Developed a MicroUI in Vue.js integrating with the Google Maps API, enabling it to be deployed as a CMS plugin via npm, improving content flexibility.
- Recognized for outstanding performance and contributions, leading to a promotion from Junior Software Engineer to Software Engineer.