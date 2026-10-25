
# Special Topics in Computer Science – I
## Version Control and CI/CD Automation

**Al-Zaytoonah University of Jordan**  
**Department of Computer Science**  
**Instructor:** Dr. Jalal Kiswani

---

## Course Overview

This repository contains the lectures, practical exercises, assignments, examples, and project resources for the **Special Topics in Computer Science – I: Version Control and CI/CD Automation** course.

The course introduces modern software development practices, focusing on **Version Control, Collaborative Development, Continuous Integration (CI), and Continuous Delivery/Deployment (CD)**.

Students will gain hands-on experience using industry-standard tools to manage source code, collaborate on software projects, and automate software building, testing, packaging, and deployment.

## Course Information

| Item | Description |
|---|---|
| Course | Special Topics in Computer Science – I |
| Focus | Version Control and CI/CD Automation |
| Target Students | 3rd and 4th Year Computer Science |
| Duration | 15 Weeks |
| Weekly Sessions | 2 (Theory + Practical) |
| Total Sessions | 30 |
| Prerequisites | Programming Fundamentals and Basic Software Development |

## Course Learning Outcomes

By the end of this course, students will be able to:

1. Understand the principles of version control systems.
2. Manage local and remote Git repositories.
3. Apply branching, merging, and conflict resolution techniques.
4. Collaborate on software projects using GitHub.
5. Explain CI/CD concepts and DevOps workflows.
6. Design automated workflows using GitHub Actions.
7. Automate static website and PHP application deployment.
8. Build, test, and package Java web applications using Maven.
9. Install, configure, and manage Jenkins.
10. Develop and troubleshoot Jenkins pipelines.

## Technologies and Tools

| Technology | Purpose |
|---|---|
| Git CLI | Distributed Version Control |
| TortoiseGit | Graphical Git Client |
| GitHub | Repository Hosting and Collaboration |
| GitHub Actions | CI/CD Workflow Automation |
| Jenkins | CI/CD Automation Server |
| Apache Maven | Java Build and Dependency Management |
| Java | Application Development |
| PHP | Web Application Development |
| HTML / CSS / JavaScript | Static Website Development |
| Apache Tomcat | Optional Java Web Application Deployment |

## Weekly Course Schedule

| Week | Theory Session | Practical Session |
|---|---|---|
| 1 | Introduction to Version Control and Git | Git CLI and TortoiseGit Fundamentals |
| 2 | Branching, Merging, and Git Workflows | Branch Management and Conflict Resolution |
| 3 | GitHub and Collaborative Development | Remote Repositories, Pull Requests, and Code Reviews |
| 4 | Introduction to DevOps and CI/CD | CI/CD Concepts and Workflow Design |
| 5 | GitHub Actions Fundamentals | Creating Basic GitHub Actions Workflows |
| 6 | Advanced GitHub Actions | Jobs, Dependencies, Variables, Secrets, and Artifacts |
| 7 | Static Website Deployment | Automated Deployment Using GitHub Actions |
| 8 | **Midterm Theoretical Exam** | **Midterm Practical Exam** |
| 9 | CI/CD for PHP Applications | Automated PHP Application Deployment |
| 10 | CI/CD for Java Applications Using Maven | Automated Build, Test, and WAR Packaging |
| 11 | Jenkins Fundamentals and Architecture | Jenkins Installation and Configuration |
| 12 | Jenkins Pipelines and Jenkinsfile | Creating Declarative Jenkins Pipelines |
| 13 | Jenkins-Based Web Deployment | Static Website and PHP Deployment Pipelines |
| 14 | Jenkins with Maven, Security, and Troubleshooting | Automated Java WAR Packaging and Pipeline Troubleshooting |
| 15 | **Final Project Presentations** | **Final Project Demonstrations and Evaluation** |

## Assessment and Grading

| Assessment Component | Weight |
|---|---:|
| Midterm Exam (Theory and Practical) | 30% |
| Quizzes, Assignments, and Presentations | 20% |
| Participation and Practical Activities | 10% |
| Final Project | 40% |
| **Total** | **100%** |

## Repository Structure

The recommended repository structure is:

```text
special-topics-cicd/
│
├── README.md
│
├── lectures/
│   ├── week-01-git-fundamentals/
│   ├── week-02-branching-merging/
│   ├── week-03-github-collaboration/
│   ├── week-04-cicd-concepts/
│   ├── week-05-github-actions/
│   ├── week-06-advanced-actions/
│   ├── week-07-static-deployment/
│   ├── week-09-php-cicd/
│   ├── week-10-maven-cicd/
│   ├── week-11-jenkins-fundamentals/
│   ├── week-12-jenkins-pipelines/
│   ├── week-13-jenkins-deployment/
│   └── week-14-jenkins-maven/
│
├── labs/
│
├── assignments/
│
├── examples/
│   ├── git/
│   ├── github-actions/
│   ├── static-website/
│   ├── php-application/
│   ├── maven-webapp/
│   └── jenkins/
│
├── projects/
│   └── final-project-guidelines.md
│
└── resources/
```

> **Note:** Course materials and directories will be added progressively throughout the semester.

## Practical Learning Activities

### 1. Version Control and Collaboration

- Creating and managing Git repositories
- Tracking changes and managing commits
- Creating and merging branches
- Resolving merge conflicts
- Working with remote GitHub repositories
- Collaborating through pull requests and code reviews

### 2. GitHub Actions Automation

- Creating YAML-based CI/CD workflows
- Configuring workflow triggers, jobs, and steps
- Managing environment variables and secrets
- Building and testing applications automatically
- Deploying static websites
- Automating PHP application deployment
- Building and packaging Maven-based Java web applications

### 3. Jenkins Automation

- Installing and configuring Jenkins
- Creating Jenkins jobs and pipelines
- Writing declarative Jenkinsfiles
- Integrating Jenkins with Git repositories
- Automating builds and deployments
- Managing credentials and security
- Troubleshooting pipeline failures

## Final Project

Students will develop a software project demonstrating practical implementation of version control and CI/CD automation.

### Minimum Requirements

1. A Git repository with meaningful commit history.
2. A structured branching and collaboration workflow.
3. A functional application or website.
4. An automated CI/CD pipeline using GitHub Actions or Jenkins.
5. Automated build, validation, or testing steps.
6. Automated deployment or artifact packaging.
7. A clear README explaining the project and pipeline.
8. A live demonstration of the implemented workflow.

### Suggested Project Categories

- Static website with automated deployment
- PHP web application with automated deployment
- Java Maven web application with automated WAR packaging
- Multi-stage CI/CD pipeline integrating build, test, and deployment activities

Detailed project requirements and evaluation criteria will be provided during the semester.

## Getting Started

### Required Software

Students should install the following tools as needed:

- [Git](https://git-scm.com/downloads)
- [TortoiseGit](https://tortoisegit.org/)
- [GitHub](https://github.com/)
- [Visual Studio Code](https://code.visualstudio.com/) or another IDE
- [Java Development Kit](https://adoptium.net/)
- [Apache Maven](https://maven.apache.org/)
- [Jenkins](https://www.jenkins.io/)

### Clone the Repository

```bash
git clone <repository-url>
cd <repository-directory>
```

Replace the placeholders with the actual repository URL and directory name.

### Basic Git Commands

```bash
# Check repository status
git status

# View commit history
git log --oneline

# Create a new branch
git switch -c feature/my-feature

# Stage changes
git add .

# Commit changes
git commit -m "Implement new feature"

# Push the branch
git push -u origin feature/my-feature
```

## Course Policies and Guidelines

- Students are expected to attend theoretical and practical sessions.
- Practical exercises must be completed using the required tools.
- Assignments must be submitted according to announced deadlines.
- Students are responsible for maintaining their repositories and commit histories.
- Academic integrity must be maintained in all submitted work.
- Passwords, API keys, access tokens, and other sensitive information must never be committed.
- Course announcements and materials should be reviewed regularly.

## Learning Resources

### Official Documentation

- [Git Documentation](https://git-scm.com/doc)
- [Pro Git Book](https://git-scm.com/book/en/v2)
- [TortoiseGit Documentation](https://tortoisegit.org/docs/)
- [GitHub Documentation](https://docs.github.com/)
- [GitHub Actions Documentation](https://docs.github.com/en/actions)
- [Jenkins Documentation](https://www.jenkins.io/doc/)
- [Apache Maven Documentation](https://maven.apache.org/guides/)
- [GitHub Skills](https://skills.github.com/)

## Repository Updates

Course materials will be updated progressively throughout the semester.

Students should regularly synchronize their local repositories:

```bash
git pull origin main
```

---

## Instructor

**Dr. Jalal Kiswani**  
Department of Computer Science  
Al-Zaytoonah University of Jordan

---

**Academic Use:** This repository supports the educational activities of the Special Topics in Computer Science – I course.
