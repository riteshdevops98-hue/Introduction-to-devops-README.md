Notes: "Improve SDLC with DevOps"
1. What is SDLC?

The Software Development Life Cycle (SDLC) is a standard process used across the software industry to design → develop → test → deploy software and ensure delivery of high-quality products. 


At a high level, SDLC phases include: Planning → Designing → Building (Development) → Testing → Deployment, and this cycle repeats for every feature increment. 


2. Why DevOps Needs SDLC

Everyone in an organization—including developers, testers, and DevOps engineers—must understand SDLC to adhere to standard processes when delivering software. 

The end goal of following SDLC is to consistently deliver a high-quality product to customers.

3. SDLC Example Workflow

Using a simplified scenario from example.com (e-commerce):

Planning: Define new feature (e.g., adding a kids’ clothing section).

Design: Prepare requirements and design documents (high-level and low-level).

Build: Developers write code and push it to a central repository (e.g., Git).

Test: QA (Quality Assurance) team tests the deployed application in a staging environment.

Deploy: Once validated, the application is promoted to production for customers.
This cycle continues for each new feature. 

4. DevOps Role within SDLC

The core value of DevOps is automation—particularly in the Build, Test, and Deploy phases. 


A DevOps engineer orchestrates automation of these phases, reducing manual intervention and enhancing delivery efficiency. 


5. Summary: DevOps & SDLC

SDLC defines the essential stages for delivering software.

DevOps accelerates this process by automating the most repetitive and error-prone stages.

The result: faster cycles, higher quality, and more reliable software delivery.

Diagram Sketch: SDLC with DevOps Automation
   +-----------+      +---------+      +--------+
   |  PLAN     | ---> | DESIGN  | ---> | BUILD  |
   | (Feature) |      | Docs    |      | Code & |
   |           |      |         |      | Commit |
   +-----------+      +---------+      +--------+
                                          |
                                          v
                                   +-------------+
                                   | AUTOMATED   |
                                   | TESTING     |
                                   | (QA + CI/CD)|
                                   +-------------+
                                          |
                                          v
                                   +-------------+
                                   | AUTOMATED   |
                                   | DEPLOYMENT  |
                                   | (Pre-prod → |
                                   |  Production)|
                                   +-------------+
                                          |
                                          v
                                     +------------+
                                     | CUSTOMER   |
                                     +------------+

How This Works

Planning → define what to build.

Design → prepare technical specifications.

Build → developers write code → push to Git.

Automated Testing → CI/CD pipeline runs tests (unit, integration).

Automated Deployment → pipeline promotes the tested build to pre-prod, then production.

Customer → receives the release quickly and reliably.

This captures how DevOps seamlessly integrates into the SDLC, significantly enhancing speed and reducing manual errors.
