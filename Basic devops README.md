
What is devops.?

“DevOps is a culture that combines development (Dev) and operations (Ops) to improve an organization’s ability to deliver applications and services faster and more reliably by autmomation.”
It improve the devlivery by include Automation,quality ,continous monitoring/observablilty and continous testing.

Why devops..?

Traditional Deployment Flow (Before DevOps)

Developer

Writes the application code.

Places the code in a central repository like SVN/CVS.

Their job stops at committing the code.

System Admin

Creates a server environment (e.g., physical, VMware, Openshift, Zen, etc.).

Prepares the infrastructure where the code will be deployed.

This was often manual and time-consuming.

Server Admin

Configures the application server (Tomcat, WebLogic, etc.).

Installs dependencies, sets up environments, etc.

Another manual, repetitive step.

Tester

Tests the application on the deployed server.

Reports issues → cycle goes back to developer → fix → redeploy.

Slowed down releases.

BRE (Build & Release Engineer)

Takes the code from the repo.

Deploys it manually either to Pre-production or directly to Production.

A lot of coordination needed → mistakes were common.

Final step: push to Production server → delivered to Customer.

⚠️ Problem with this old model:

Each step involved different people.

Manual handoffs → more errors, delays.

Redundant work → e.g., server admins repeating setups.

Slow feedback loop → developers waited days/weeks for test results.

A lot of human effort just for simple deployments.

🔹 With DevOps (Modern Flow)

DevOps introduced automation + collaboration:

CI/CD Pipelines (Jenkins, GitLab CI, etc.)

Developer pushes code → pipeline automatically builds, tests, and deploys.

Removes manual intervention from BRE and server admins.

Infrastructure as Code (IaC)

Tools like Terraform, Ansible, Docker, Kubernetes automatically create and configure servers.

No need for system/server admins to manually provision.

Automated Testing

Unit, integration, and regression tests run automatically after every commit.

Tester’s manual effort is reduced, focus shifts to exploratory testing.

Continuous Deployment

Code can go from commit → pre-production → production in minutes with approvals or automated rules.

BRE’s manual deployments are replaced by automation.

Monitoring & Feedback

Tools like Prometheus, ELK, Grafana continuously monitor apps.

Faster feedback loop to developers.

⚡ Result with DevOps:

Fewer people directly involved.

Deployment speed: days → minutes.

Reliability increased (less human error).

Teams collaborate better (Dev + Ops working together).


<img width="700" height="500" alt="image" src="https://github.com/user-attachments/assets/fdf8301e-b0a1-44fd-bedc-53f59d2bae11" />
<img width="700" height="500" alt="image" src="https://github.com/user-attachments/assets/6a06c87a-d73d-471e-b7ba-0983a73a771b" />

