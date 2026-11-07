# AIOps Learning Roadmap

A step-by-step path to learn AIOps, from infrastructure foundations to practical, responsible automation.

## 1. Build the foundations

Learn Linux, networking, Git, Python, and basic cloud concepts. Get comfortable with the command line and write small scripts to automate routine tasks.

**Milestone:** Write a Python script that reads a log file and summarizes common errors.

## 2. Learn one cloud platform

Choose AWS, Azure, or Google Cloud. Learn the basics of compute, storage, networking, identity and access management, and managed services.

**Milestone:** Deploy a small application to your chosen cloud and explain how it is connected and secured.

## 3. Learn containers and deployment

Study Docker, Kubernetes fundamentals, and CI/CD. Practice building, deploying, updating, and rolling back a small service.

**Milestone:** Containerize your application and deploy it using a basic CI/CD pipeline.

## 4. Understand observability

Learn the three main observability signals: metrics, logs, and traces. Practice dashboards, alerting, and investigating an issue. Explore tools such as Prometheus and Grafana, and a log platform such as Loki or the ELK stack.

**Milestone:** Create a dashboard and an actionable alert for your service.

## 5. Practice SRE fundamentals

Study service level indicators (SLIs), service level objectives (SLOs), error budgets, incident response, and root-cause analysis. Learn to write clear runbooks and post-incident reviews.

**Milestone:** Define an SLO for your service and write a runbook for responding to an alert.

## 6. Learn data and machine learning basics

Use Python for data analysis. Learn basic statistics, time-series data, anomaly detection, and model evaluation. Focus on validating signals and measuring model quality, rather than only training a model.

**Milestone:** Analyze historical or synthetic metrics and evaluate a simple anomaly detector, including its false-positive rate.

## 7. Apply automation to operations

Choose a repetitive, low-risk operational task to automate, such as alert enrichment or runbook lookup. Add tests, logging, access controls, and a human approval step when appropriate.

**Milestone:** Build an automation that provides useful context for an alert without taking unapproved consequential actions.

## 8. Build an end-to-end AIOps project

Combine what you have learned: collect service metrics, detect unusual behavior, correlate it with logs or deployments, and generate an incident summary with supporting evidence and suggested next steps.

**Milestone:** Demonstrate the project using historical or synthetic data and show how an operator can verify its findings.

## 9. Evaluate it responsibly

Measure false positives, missed incidents, time to detect, and time to resolve. Test against historical or synthetic data. Protect sensitive information, make uncertainty visible, and keep humans in control of consequential actions.

**Milestone:** Document evaluation results, known limitations, and situations where the system should defer to an operator.

## 10. Document and iterate

Write setup instructions, an architecture overview, and an explanation of how to run and evaluate your project. Use test results and operator feedback to improve it.

**Milestone:** Make it possible for someone else to reproduce your demonstration from the documentation.

## Suggested order

**Foundations → cloud and containers → observability and SRE → data and ML → automation → end-to-end project**

Focus on finishing a small, well-evaluated project rather than trying to learn every tool at once.
