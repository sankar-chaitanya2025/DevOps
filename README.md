# DevOps Day 01: Interactive Notes

## 1. What is DevOps?

DevOps is a modern approach to software development that brings together Development (Dev) and Operations (Ops) teams. The goal is to enable faster, more reliable, and more secure software delivery by fostering a culture of collaboration, automation, and continuous feedback.

### Analogy: The Restaurant Kitchen

Imagine a restaurant:

- **Chefs (Developers):** Cook the food (write code).
- **Waiters (Operations):** Deliver the food to customers (deploy and maintain software).

If chefs and waiters don’t communicate, orders get mixed up, food is delayed, and customers are unhappy. DevOps is like having an open kitchen where chefs and waiters work side-by-side, share feedback instantly, and use tools (like order screens and timers) to automate repetitive tasks, ensuring hot, fresh meals reach customers quickly and consistently.

### Key Concepts

- **Collaboration:** Dev and Ops work together, breaking down silos.
- **Automation:** Repetitive tasks (like testing and deployment) are automated.
- **Continuous Integration & Delivery (CI/CD):** Code changes are integrated and delivered frequently and reliably.
- **Monitoring & Feedback:** Systems are monitored in real-time, and feedback is used to improve processes.

---

## 2. Why DevOps?

### The Traditional Problem

In the past, developers wrote code and "threw it over the wall" to operations, who then struggled to deploy and maintain it. This led to:

- **Slow releases**
- **Frequent bugs**
- **Frustrated teams and users**

### DevOps Solution

DevOps solves these problems by:

- **Speeding up delivery:** Software reaches users faster.
- **Improving quality:** Automated testing and monitoring catch issues early.
- **Increasing reliability:** Frequent, smaller updates are less risky.
- **Boosting team morale:** Collaboration reduces friction and blame.

#### Analogy: The Family Home

Think of a family working together to keep the house running smoothly. If everyone shares chores, communicates, and uses smart tools (like a dishwasher), the home is happier and more efficient.

---

## 3. How to Introduce Yourself as a DevOps Engineer

### Structure

1. **Start with your name and current role**
2. **Highlight your experience and key skills**
3. **Mention a notable achievement or project**
4. **Share your current focus or learning goals**
5. **Wrap up with your enthusiasm for DevOps**

### Sample Introduction

> Hi, I’m [Your Name], currently working as a DevOps Engineer with [X years] of experience. I specialize in cloud platforms like AWS, and tools such as Docker, Kubernetes, Jenkins, and Terraform. One of my key achievements was implementing a scalable CI/CD pipeline that reduced deployment time by 30%. I’m passionate about automating infrastructure and continuously improving monitoring and reliability. I’m excited to contribute to building efficient, collaborative DevOps teams.

#### Tips

- **Mention specific tools and outcomes** (e.g., “reduced deployment time by 50%”).
- **Tailor your intro to the audience** (job interview, networking, online profile).
- **Keep it concise and focused** on your DevOps journey.

---

## 4. What Are Your Day-to-Day Activities as a DevOps Engineer?

### Typical Daily Tasks

- **Morning Checks:** Review system alerts and notifications, troubleshoot urgent issues (like pod errors in Kubernetes).
- **CI/CD Pipeline Management:** Modify, run, and optimize pipelines for continuous integration and deployment.
- **Automation:** Write scripts to automate repetitive tasks (e.g., deployments, backups).
- **Collaboration:** Attend stand-ups, coordinate with developers and operations on new features or incidents.
- **Monitoring & Logging:** Use tools (like Prometheus, Grafana) to monitor system health and performance.
- **Infrastructure as Code:** Manage cloud resources using tools like Terraform or Ansible.
- **Documentation:** Update runbooks, deployment guides, and incident reports.
- **Continuous Learning:** Explore new tools and best practices to improve team efficiency and system reliability.

### Analogy: The Air Traffic Controller

A DevOps engineer is like an air traffic controller—constantly monitoring, coordinating, and automating to ensure all flights (deployments) land safely and on time, while quickly resolving any turbulence (incidents) that arise.

---

## 5. Summary Table: DevOps at a Glance

| Aspect                | Analogy                  | Key Activities                        | Benefits                        |
|-----------------------|--------------------------|---------------------------------------|----------------------------------|
| What is DevOps?       | Restaurant Kitchen       | Collaboration, Automation, CI/CD      | Faster, reliable delivery        |
| Why DevOps?           | Family Home              | Shared responsibility, smart tools     | Happier teams, better software   |
| Self-Introduction     | Elevator Pitch           | Skills, achievements, tools            | Strong first impression          |
| Day-to-Day Activities | Air Traffic Controller   | Monitoring, automating, collaborating | Smooth, efficient operations     |

---

**DevOps is not just a set of tools, but a culture of collaboration, automation, and continuous improvement—making software delivery faster, safer, and more enjoyable for everyone involved.**

# Day 2: Improve SDLC with DevOps – Abhishek Veeramalla DevOps Zero to Hero

## What is SDLC?

**SDLC (Software Development Life Cycle)** is the structured process used by teams to plan, design, build, test, deploy, and maintain software. It ensures that software is developed efficiently and meets quality standards.

---

## Phases of SDLC

Abhishek breaks down the SDLC into the following main phases:

1. **Requirements Gathering:**  
   - Understand what the software needs to do.
   - Collect input from stakeholders.
2. **System Design:**  
   - Plan how the software will be built.
   - Create architecture and design documents.
3. **Development (Coding):**  
   - Write the actual code for the software.
4. **Testing:**  
   - Check for bugs and ensure the software works as intended.
5. **Deployment:**  
   - Release the software to users or production environments.
6. **Maintenance:**  
   - Fix issues, update features, and keep the software running smoothly.

---

## How DevOps Improves SDLC

DevOps brings major improvements to each SDLC phase:

- **Automation:**  
  - Automate repetitive tasks (builds, tests, deployments).
  - Reduces errors and speeds up the process.
- **Collaboration:**  
  - Developers and operations work together from day one.
  - No more “throwing code over the wall.”
- **Continuous Integration/Continuous Deployment (CI/CD):**  
  - Code changes are automatically built, tested, and deployed.
  - Faster feedback and quicker releases.
- **Monitoring and Feedback:**  
  - Monitor software in real-time.
  - Use feedback to improve future releases.
- **Infrastructure as Code (IaC):**  
  - Manage servers and environments using code (e.g., Terraform).
  - Makes environments consistent and reproducible.

---

## Key Takeaways from Day 2

- **SDLC is the backbone of software development.**
- **DevOps injects automation, collaboration, and feedback into every phase.**
- **CI/CD pipelines and IaC are core DevOps practices that make SDLC faster and more reliable.**
- **Monitoring and feedback loops help teams continuously improve software quality.**

---

## Practical Example

Abhishek often demonstrates how DevOps tools (like Jenkins, Docker, and Terraform) can be used to automate different SDLC phases, making the entire process more efficient and less error-prone[1][3].

---

## Why This Matters

- **Faster time to market:** New features and fixes reach users quicker.
- **Higher quality:** Automated testing catches bugs early.
- **Better teamwork:** Developers and operations collaborate, reducing blame and confusion.

---

> **“DevOps is not just about tools—it’s about culture, automation, and continuous improvement.”**  
> — Abhishek Veeramalla

---

**Next up:** In following days, Abhishek dives into cloud platforms (AWS), automation tools (Terraform), and more hands-on DevOps practices[3][5].

# Project Roles, Workflow, and Task Tracking in DevOps: The "15-Minute Delivery" Feature Example

## Understanding the Team Roles

Every successful software project relies on a team with clearly defined roles. Here’s a quick reference (from the image) for each role and their main responsibility:

| **Role**            | **Responsibility**                                           |
|---------------------|-------------------------------------------------------------|
| Business Analyst    | Gathers and documents customer requirements.                |
| Product Manager     | Defines the vision, goals, and priorities.                  |
| Product Owner       | Manages backlog and converts vision into actionable stories.|
| UI/UX Designer      | Designs user interface and user experience.                 |
| Software Architect  | Designs technical system structure and frameworks.          |
| Developers          | Build the actual product (UI, APIs, databases).             |
| DBA                 | Designs and manages the database.                           |
| Security Engineer   | Ensures product and infrastructure security.                |
| QA Engineer         | Tests product quality and performance.                      |
| DevOps Engineer     | Builds CI/CD pipelines and manages environments.            |
| Release Manager     | Plans and manages releases.                                 |
| SRE                 | Ensures uptime, performance, and reliability post-release.  |
| Technical Writer    | Creates documentation for users and developers.             |

---

## Example Workflow: Building the "15-Minute Delivery" Feature

Let’s say the company wants to launch a new **“15-minute delivery”** feature. Here’s how the workflow moves from idea to reality, step by step:

1. **Customer/Stakeholder Request:**  
   - The idea (15-min delivery) starts from customer needs or business goals.

2. **Business Analyst:**  
   - Talks to customers, gathers requirements, and documents what “15-minute delivery” should mean in practice.

3. **Product Manager:**  
   - Sets the vision: “We want to deliver groceries in 15 minutes to increase market share.”
   - Prioritizes this feature among other company goals.

4. **Product Owner:**  
   - Breaks down the vision into actionable stories for the development team (e.g., “As a user, I want to see only items available for 15-min delivery”).

5. **UI/UX Designer:**  
   - Designs new screens or updates the app to highlight the 15-min delivery option.

6. **Software Architect:**  
   - Plans how the backend and frontend systems need to change to support fast delivery (e.g., real-time inventory, optimized routing).

7. **Developers:**  
   - Write code for new features: updating UI, APIs, delivery algorithms, etc.

8. **DBA:**  
   - Designs or updates database tables to track fast-delivery orders and inventory.

9. **Security Engineer:**  
   - Ensures new APIs and data flows are secure.

10. **QA Engineer:**  
    - Tests the new feature: Does it show up for users? Are only eligible products shown? Is delivery time tracked correctly?

11. **DevOps Engineer:**  
    - Sets up CI/CD pipelines to automate testing and deployment of the new feature.

12. **Release Manager:**  
    - Plans when and how to release the feature (e.g., phased rollout, canary release).

13. **SRE (Site Reliability Engineer):**  
    - Monitors the system after release to ensure the feature is reliable and fast.

14. **Technical Writer:**  
    - Updates user guides and developer documentation to reflect the new feature.

---

## How JIRA Helps in Tracking These Tasks

**JIRA** is a powerful tool for managing and tracking all these tasks across the team:

- **Epic Creation:**  
  - The Product Owner creates an Epic called “15-Minute Delivery Feature.”

- **Story Breakdown:**  
  - The Epic is broken into smaller user stories (e.g., “Update UI for 15-min delivery,” “Optimize delivery routing algorithm”).

- **Task Assignment:**  
  - Each story/task is assigned to the appropriate team member (developer, QA, designer, etc.).

- **Status Tracking:**  
  - Tasks move through boards (To Do → In Progress → Code Review → Testing → Done), making progress visible to everyone.

- **Collaboration:**  
  - Team members can comment, attach designs, link related tasks, and update status in real time.

- **Sprint Planning:**  
  - The team uses JIRA to plan sprints, estimate effort, and track velocity.

- **Reporting:**  
  - JIRA provides burndown charts, cumulative flow diagrams, and other reports to monitor progress and identify bottlenecks.

**Interactive Example:**  
- The Product Owner creates a story:  
  *“As a user, I want to see a badge for 15-min delivery items.”*
- The UI/UX Designer attaches mockups to the story.
- The Developer marks the story as “In Progress” when coding starts.
- The QA Engineer moves it to “Testing” after development.
- Once all acceptance criteria are met, the story is marked “Done.”

---

## Summary

- Each role has a clear responsibility in delivering new features.
- The workflow for a feature like “15-minute delivery” moves step by step from idea to release, involving the whole team.
- **JIRA** acts as the central hub for planning, tracking, and collaborating on every task, ensuring nothing falls through the cracks and everyone stays aligned.
- End of Day 2 !!

