📁 Cloud-Based Document Management System using AWS OpenSearch This project demonstrates a serverless, scalable architecture for managing documents using AWS services. It enables uploading, indexing, searching, and retrieving documents—all in a fully automated cloud environment without managing servers.

🚀 Project Overview Pipeline Components:

Amazon S3 – Stores uploaded documents (PDF, TXT).

AWS Lambda – Extracts text and indexes content in real time.

Amazon OpenSearch Service – Enables full-text search across documents.

AWS API Gateway – Exposes secure endpoints for search queries.

AWS IAM – Manages roles and access permissions.

Amazon CloudWatch – Monitors logs, metrics, and system performance.

🔧 Services Used AWS Lambda (Python)

Amazon S3

Amazon OpenSearch Service

AWS API Gateway

AWS IAM

Amazon CloudWatch

🛠️ How to Use

Upload Documents via S3 Upload files like about_design_v2.txt etc.., to a designated S3 bucket.

Lambda Processes Files Triggered on upload, Lambda extracts text and indexes content in OpenSearch.

Search Using API Use API Gateway or tools like Postman to query documents by keyword (e.g., “design”).

Monitor with CloudWatch Track logs, detect errors, and optimize resource usage in real-time.

📺 Demo Video Watch the full walkthrough here: https://youtu.be/wV4G_9CJY9k?si=kZjGBRNeRR8GCgwV

📬 Contact For feedback or collaboration, reach out to: 📧 deekshithadrithi@gmail.com
