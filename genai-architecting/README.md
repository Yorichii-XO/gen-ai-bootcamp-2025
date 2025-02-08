1. Functional Requirements
Our company is looking to own and manage its infrastructure to maintain control over costs and ensure data privacy. Here’s what we’re working with:

Budget: We’re planning to invest around $10-15K in an AI-powered PC to host our models locally.

Privacy Concerns: We want to avoid sending any student data to external cloud providers to keep everything secure and compliant.

Users: We’re serving 300 active students, all based in Istanbul.

Cloud Consideration: While we’re starting locally, we’re keeping the door open for future cloud adoption to scale deployment and improve performance.

2. Assumptions
Here’s what we’re assuming as we move forward:

The open-source LLMs we select (like Mistral AI) will be capable of running efficiently on hardware within our $10-15K budget.

A single server hosted in our office, connected to the internet, should provide enough bandwidth to serve all 300 students.

Our infrastructure should handle low-latency applications without needing to rely on the cloud right away.

3. Data Strategy
We’ve put together a plan for handling data effectively:

Data Collection: We’re exploring the use of synthetic data for pretraining our models.

Copyright Compliance: We’ll purchase and store only legally approved materials to avoid any issues.

Storage Strategy: We’re planning to implement a cost-effective local database for fast and reliable data retrieval.

Inference Optimization: We’re considering using vector databases to make model querying more efficient.

4. Model Selection
After evaluating our options, we’ve decided to go with Mistral AI as our primary choice. It’s open-source, highly efficient, and well-suited for our use case. Additionally, we’ll explore integrating AWS services (like Claude) for specific tasks to enhance performance and scalability.

5. Deployment & Maintenance Plan
Here’s how we’ll set things up and keep them running smoothly:

Initial Setup:
Install the AI PC with all necessary dependencies.

Deploy the Mistral AI model and integrate AWS Claude for specific services.

Monitoring:
Implement logging to track performance and identify bottlenecks.

Set up alerts for hardware resource usage to avoid overloading the system.

Backup & Recovery:
Automate regular backups to ensure data safety.

Security Measures:
Encrypt sensitive data to protect student information.

Cost Optimization:
Use power-efficient hardware to keep electricity costs low.

Optimize batch processing to reduce computational load and improve efficiency.