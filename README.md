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


# DevOps Zero to Hero – Day 3: Virtual Machines (Part 1)  
**Comprehensive Notes by Abhishek Veeramalla**

---

## 1. Introduction to Virtual Machines

- **What is a Virtual Machine (VM)?**
  - A VM is a software-based emulation of a physical computer.
  - It runs its own operating system (OS) and applications just like a physical computer.
- **Why Use VMs?**
  - **Resource Optimization:** Multiple VMs can run on a single physical server, making better use of hardware resources.
  - **Isolation:** Each VM is isolated from others, so issues in one VM do not affect others.
  - **Flexibility:** Easy to create, modify, and delete VMs as needed.
  - **Testing & Development:** Safe environment for testing new software or configurations.

---

## 2. Understanding Servers

- **What is a Server?**
  - A server is a computer or system that provides resources, data, or services to other computers (clients) over a network.
- **Physical Servers vs. Virtual Machines**
  - **Physical Servers:** Actual hardware machines dedicated to a single purpose.
  - **Virtual Machines:** Software-based servers running on a physical host, sharing its resources.
- **Benefits of Virtualization:**
  - **Cost Savings:** Fewer physical machines needed.
  - **Scalability:** Easily add more VMs as demand grows.
  - **Disaster Recovery:** VMs can be backed up and restored quickly.

---

## 3. Virtualization Concepts

- **Hypervisor**
  - The software layer that enables virtualization.
  - **Types of Hypervisors:**
    - **Type 1 (Bare Metal):** Runs directly on the host’s hardware (e.g., VMware ESXi, Microsoft Hyper-V).
    - **Type 2 (Hosted):** Runs on top of a conventional OS (e.g., Oracle VirtualBox, VMware Workstation).
- **Virtual Machine Manager (VMM)**
  - Another term for the hypervisor.
  - Manages the creation, operation, and deletion of VMs.

---

## 4. Real-World Example: Why Virtualization Matters

- **Scenario:** A company needs to run multiple applications (web server, database, file server) on separate servers.
  - **Without Virtualization:** Requires multiple physical servers, increasing cost and maintenance.
  - **With Virtualization:** All applications can run on separate VMs on a single physical server.
- **Advantages:**
  - **Resource Sharing:** CPU, memory, and storage are shared among VMs.
  - **Isolation:** Security and stability are improved.
  - **Easy Management:** VMs can be managed, migrated, and backed up with ease.

---

## 5. Key Takeaways

- **Virtual Machines are essential in modern IT infrastructure.**
- **Virtualization enables efficient use of resources and simplifies management.**
- **Hypervisors are the backbone of virtualization technology.**
- **VMs provide isolation, flexibility, and cost savings.**

---

## 6. Summary Table

| Concept                | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| Virtual Machine (VM)   | Software-based emulation of a physical computer                             |
| Server                 | Provides resources/services to clients over a network                       |
| Hypervisor             | Software that enables virtualization (Type 1 or Type 2)                     |
| Virtualization         | Running multiple VMs on a single physical server                            |
| Benefits               | Resource optimization, isolation, flexibility, cost savings                 |

---

## 7. Additional Resources

- **Watch the full video:** [Day-3 | Virtual Machines Part-1 | Free DevOps Course](https://www.youtube.com/watch?v=lgUwYwBozow)
- **Related notes:** [DevOps Zero to Hero Week 1 Overview](https://www.linkedin.com/posts/pratik-gote-516b361b3_devops-zero-to-hero-week-1-overview-activity-7208432533095518208-HuW3)
- **GitHub repo:** [aws-devops-zero-to-hero](https://github.com/iam-veeramalla/aws-devops-zero-to-hero)

---




# Day-5: AWS CLI, EC2 Instance Connection, and AWS CloudFormation (CFT) – Comprehensive Notes

## Overview

This session introduces practical DevOps workflows using AWS tools: the AWS Command Line Interface (CLI) for automation, methods to connect to EC2 instances from your local computer and the AWS Console, and an introduction to AWS CloudFormation (CFT) for Infrastructure as Code (IaC).

---

## AWS Command Line Interface (CLI)

### What is AWS CLI?

- **AWS CLI** is a unified command-line tool for managing AWS services.
- It enables automation, scripting, and streamlined management of AWS resources.
- It’s essential for DevOps engineers for tasks like deployment, monitoring, and maintenance.

### Installation and Configuration

- **Download:**  
  - **Windows:** Install via MSI installer or `pip install awscli`.
  - **Linux/macOS:** Use package managers (`brew`, `apt`, `yum`) or `pip install awscli`.
- **Configuration:**  
  - Run `aws configure` in your terminal.
  - Enter your AWS Access Key ID, Secret Access Key, default region (e.g., `ap-south-1`), and output format (e.g., `json`).
- **Verification:**  
  - Test with `aws s3 ls` or `aws ec2 describe-instances` to ensure setup is correct.

### Key CLI Commands

- **List EC2 instances:**  
  `aws ec2 describe-instances`
- **Start/Stop EC2 instance:**  
  `aws ec2 start-instances --instance-ids `  
  `aws ec2 stop-instances --instance-id `
- **Create a new S3 bucket:**  
  `aws s3 mb s3://`

---

## Connecting to EC2 Instances

### Methods to Connect

#### 1. **Via AWS Management Console (UI)**
- **Steps:**
  1. Go to the EC2 Dashboard.
  2. Select your instance.
  3. Click **Connect**.
  4. Choose the connection method:  
     - **SSH Client:** Use your private key (.pem) file.
     - **EC2 Instance Connect:** Browser-based SSH.
     - **Session Manager:** No need to open SSH port.
- **Follow on-screen instructions** to establish your connection.

#### 2. **Via Terminal (SSH)**
- **Requirements:**
  - Private key (.pem file).
  - Security group allowing inbound SSH (port 22) from your IP.
- **Command:**  
  ```
  ssh -i /path/to/your-key.pem ec2-user@
  ```
- **Note:** For Ubuntu instances, use `ubuntu` instead of `ec2-user`.

#### 3. **Via AWS CLI and EC2 Instance Connect**
- **Push your public key to the instance:**  
  ```
  aws ec2-instance-connect send-ssh-public-key \
    --instance-id  \
    --availability-zone  \
    --instance-os-user  \
    --ssh-public-key file://
  ```
- **Then SSH as usual.**

### Verifying the Connection

- **After login:**  
  - Run basic commands like `ls`, `pwd`, or `touch testfile`.
  - Check if you can create/modify files on the instance.

---

## AWS CloudFormation (CFT)

### What is AWS CloudFormation?

- **AWS CloudFormation** is an Infrastructure as Code (IaC) service.
- It allows you to model and provision AWS resources using templates (JSON or YAML).
- **Benefits:** Automation, repeatability, consistency, and easy management of infrastructure.

### Key Concepts

- **Template:** A file that defines the infrastructure and resources.
- **Stack:** A collection of AWS resources created and managed as a single unit.
- **Change Sets:** Preview changes before applying them.
- **Rollback:** Automatically reverts changes if provisioning fails.

### Getting Started

- **Sample Template (YAML):**  
  ```
  AWSTemplateFormatVersion: "2010-09-09"
  Resources:
    MyEC2Instance:
      Type: "AWS::EC2::Instance"
      Properties:
        ImageId: "ami-0abcdef1234567890"
        InstanceType: "t2.micro"
  ```
- **Deploy a Stack via CLI:**  
  ```
  aws cloudformation create-stack \
    --stack-name my-stack \
    --template-body file://my-template.yaml
  ```
- **Check Stack Status:**  
  ```
  aws cloudformation describe-stacks --stack-name my-stack
  ```

### Use Cases

- **Automate infrastructure setup** (VPC, EC2, RDS, etc.)
- **Disaster recovery and multi-region deployments**
- **Consistent environments for development, testing, and production**

---

## Summary Table

| Feature/Service         | AWS CLI                                   | AWS Console (UI)                  | AWS CloudFormation (CFT)           |
|------------------------|-------------------------------------------|-----------------------------------|------------------------------------|
| **Purpose**            | Command-line automation                   | Web-based management               | Infrastructure as Code (IaC)       |
| **Automation**         | Yes (scripts, cron jobs)                  | Manual (point-and-click)          | Yes (templates, stacks)            |
| **Connect to EC2**     | SSH, EC2 Instance Connect via CLI         | SSH, EC2 Instance Connect via UI  | N/A (provisions EC2, not connects) |
| **Resource Management**| All AWS services                          | All AWS services                  | All AWS services                   |
| **Learning Curve**     | Moderate (requires CLI knowledge)         | Low (intuitive interface)         | Moderate (requires template syntax)|

---

## Additional Resources

- **AWS CLI Documentation:** [https://aws.amazon.com/cli/](https://aws.amazon.com/cli/)
- **AWS CloudFormation Templates Examples:** [https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/sample-templates-services-us-west-2.html](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/sample-templates-services-us-west-2.html)
- **EC2 Instance Connect Guide:** [https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-instance-connect.html](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-instance-connect.html)
- **Community Support:** Join relevant Discord or Slack channels for live help.

---

## Practical Tips

- **Practice connecting to EC2 instances using both UI and CLI.**
- **Experiment with AWS CloudFormation templates for automating infrastructure.**
- **Regularly back up your AWS credentials and private keys.**
- **Use IAM roles and policies for secure access management.**
```

```
# Day-6 | Linux & Shell Scripting - Complete DevOps Course Notes

Welcome back everyone! Today is Day 6 of our DevOps journey, and we're diving deep into **Linux & Shell Scripting fundamentals**. This is going to be an exciting session where we'll understand why shell scripting is absolutely crucial for DevOps engineers.

## Understanding Shell Scripting Fundamentals

Shell scripting is essentially **the way you communicate with your operating system**. Think about it - in Windows, you have a beautiful graphical user interface where you can click and navigate through folders. But here's the reality: **most of the time when you're working in software organizations, you don't have a graphical user interface for your servers**.

When you have issues on your production server, there's no GUI to help you navigate and troubleshoot. You need to do everything through **command line interface**, and this is where shell commands become your best friend.

## Why Shell Scripting is Essential for DevOps

**Shell scripting is a fundamental skill for DevOps professionals**. It empowers you to:
- **Automate repetitive tasks**
- **Manage system configurations** 
- **Enhance overall efficiency** in the software development lifecycle

The beautiful thing about shell commands is that they are **99.9% common across different Linux distributions** - whether you're using CentOS, Fedora, Debian, or Ubuntu, the shell commands we use as DevOps engineers remain mostly the same.

## Setting Up Your Environment

For this course, I'm using a **Mac laptop with bash installed**. By default, Mac comes with zsh, but I recommend learning **bash** because it's one of the most popular and widely used shells. Instead of learning ksh or other shells, just focus on bash - you'll use this throughout your DevOps journey.

### Connecting to AWS Instance

Let me show you how to connect to the AWS instance we created in the previous class:

```
ssh -i your-key-pair.pem ubuntu@your-public-ip
```

We're using the **key value pair** we created earlier along with the **public IP of the EC2 instance** to log in. Since we created an Ubuntu image, the default user is "ubuntu".

## What is Shell Scripting?

**Shell scripting is the art of writing scripts (sets of commands) in a shell language to automate tasks or to interact with the operating system**. In a DevOps context, shell scripts are essential for:
- **Deploying applications**
- **Configuring systems**
- **Monitoring infrastructure**
- **Automating routine processes** like backups and log management

## The Shebang Line - #!/bin/bash

The **shebang line is essential in shell scripting** as it tells the operating system **which shell to use to interpret the commands** in the script. Different shells have different syntax and built-in commands, so it's important to specify the correct shell in the shebang line to ensure your script runs as intended.

**The shebang #!/bin/bash specifies that the Bash shell should interpret the script**. While you can use #!/bin/sh, it's good practice to use #!/bin/bash to ensure consistency.

## Writing Your First Shell Script

Let's start with a simple example:

```
#!/bin/bash
echo "I will complete #90DaysOfDevOps challenge"
```

To run this script:
1. Save it to a file (e.g., `first_script.sh`)
2. Make it executable: `chmod +x first_script.sh`
3. Run it: `./first_script.sh`

## Taking User Input and Command Line Arguments

Here's a more advanced example that demonstrates both user input and command-line arguments:

```
#!/bin/bash

# Taking user input
echo "Enter your name: "
read username
echo "Hello, $username!"

# Using command-line arguments
echo "You provided $# arguments"
echo "The first argument is: $1"
echo "The second argument is: $2"
echo "All arguments are: $*"
```

You can run this script with arguments like: `./input_script.sh Amit DevOps`

## Conditional Statements

**Conditional statements are vital in shell scripting** for making decisions and responding to different situations:

```
#!/bin/bash

# Define two numbers
num1=5
num2=10

if [ $num1 -eq $num2 ]; then
    echo "The numbers are equal."
elif [ $num1 -lt $num2 ]; then
    echo "Number 1 is less than Number 2."
else
    echo "Number 1 is greater than Number 2."
fi
```

## File Permissions and Execution

**Because of security in Linux, the creator of shell script does not get execution permission by default**. To run shell scripts, you need to:

1. **Give execution permission**: `chmod +x script-name` or `chmod 777 script-name`
2. **Run the script**: `./your-script-name`

You can also run scripts using: `bash script-name` or `/bin/sh script-name`

## Exit Status and Error Handling

Every command in Linux returns an **exit status**:
- **Return value 0**: Command successful
- **Return value >0**: Command failed or error occurred

You can check the exit status using `echo $?`

## Real-World DevOps Applications

### AWS Resource Monitoring Script

Here's a practical example for DevOps engineers - **writing a shell script to report AWS resource usage**:

```
#!/bin/bash
# AWS Resource Tracker Script
echo "AWS Resource Usage Report"
echo "========================"

# List EC2 instances
aws ec2 describe-instances

# List S3 buckets  
aws s3 ls

# List Lambda functions
aws lambda list-functions

# List IAM users
aws iam list-users
```

This script can be **integrated with CronJob** to automatically generate reports at scheduled times.

## Key Takeaways for DevOps Engineers

1. **Shell scripting is essential** for automating DevOps tasks
2. **Bash is the recommended shell** for consistency across environments
3. **Always use proper shebang lines** to specify the interpreter
4. **File permissions are crucial** - always set execute permissions
5. **Error handling and exit status** help in debugging and monitoring
6. **Real-world applications** include AWS resource monitoring and automation

## Next Steps

In our upcoming sessions, we'll dive deeper into:
- **Advanced shell scripting concepts**
- **Automation scripts for CI/CD pipelines**
- **Integration with cloud services**
- **Best practices for production environments**

Remember, shell scripting is not just about writing commands - it's about **thinking like a DevOps engineer** and automating everything that can be automated. Practice these concepts, and you'll see how powerful shell scripting can be in your DevOps journey!

Keep practicing, and I'll see you in the next session where we'll explore more advanced topics. Happy scripting!
```

## 8. Next Steps

- **Explore how to create and manage VMs on popular cloud platforms (AWS, Azure, GCP).**
- **Practice setting up a VM using VirtualBox or VMware.**
- **Learn about cloud-based VMs (EC2 in AWS, Virtual Machines in Azure).**
- ** End of Day 3 **

```
# Shell Scripting for DevOps - Zero to Hero (Part 1) - Abhishek Veeramalla Course Notes

This is a beginner-friendly tutorial for shell scripting specifically for DevOps engineers with focus on practical shell scripting applications in real DevOps scenarios. The course is designed to help with interview preparation where interviewers ask about practical use cases rather than individual commands. The tutorial teaches shell scripts that DevOps engineers actually use in their day-to-day work. We use bash scripting because bash is available across all operating systems, is the most widely used shell in the industry, is standard in most Linux distributions, and is essential for DevOps automation.

## The Shebang Line

Every shell script must start with a shebang (`#!`) followed by the interpreter path. This is a common interview question. The difference between `#!/bin/bash` and `#!/bin/sh` is that bash has more features while sh is more portable but limited. The shebang ensures scripts run consistently across different environments.

```
#!/bin/bash
# This tells the system to use bash interpreter

#!/bin/sh
# This uses the system's default shell
```

## Essential Linux Commands for DevOps

### File Operations
```
# Create files
touch filename.sh

# Edit files using vim
vim filename.sh

# Check file permissions
ls -la filename.sh

# Make script executable
chmod +x filename.sh
```

### System Monitoring Commands

**CPU Monitoring** - Used to verify server capacity before deploying applications and important for containerized applications where CPU limits are set:
```
# Check number of CPU cores
nproc
```

**Memory Monitoring** - Shows total, used, and available memory, critical for preventing out-of-memory issues, and used before deployments and for troubleshooting:
```
# Check memory usage
free -h
```

**Disk Space Monitoring** - Shows filesystem usage and available space, prevents disk space issues from log files, and important for database and container storage monitoring:
```
# Check disk usage
df -h
```

**Process Monitoring** - Used for monitoring application processes, identifying resource-hungry processes, and troubleshooting performance issues:
```
# View running processes
top

# Check specific processes
ps aux | grep processname
```

## Practical Example: Node Health Check Script

Abhishek demonstrated creating a simple shell script for node health monitoring:

```
#!/bin/bash

# Basic node health check
echo "=== Node Health Check ==="
echo "Date: $(date)"
echo "Hostname: $(hostname)"

# Check CPU cores
echo "CPU Cores: $(nproc)"

# Check memory
echo "Memory Usage:"
free -h

# Check disk space
echo "Disk Usage:"
df -h

echo "=== Health Check Complete ==="
```

## Script Execution

```
# Make the script executable
chmod +x health_check.sh

# Run the script
./health_check.sh
```

## Key Learning Objectives

The video covered understanding what shell scripting is and why it's important for DevOps, learning the basics of bash scripting, understanding the shebang line and its importance, learning essential Linux commands for system monitoring, creating a practical health monitoring script, and understanding how to make scripts executable and run them.

## Interview Preparation Points

Interviewers focus more on practical applications than individual commands. Important to understand the difference between different shell interpreters, know how to create executable scripts, and be able to explain real-world use cases for shell scripting in DevOps.

## Course Structure

This is Part 1 of a comprehensive series that builds foundational knowledge for more advanced topics. The course is designed to be practical and interview-focused where each part builds upon the previous knowledge. This video specifically focused on establishing the groundwork for shell scripting in DevOps context, with emphasis on practical skills that can be immediately applied in real-world scenarios.
```
