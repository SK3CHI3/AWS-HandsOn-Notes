# AWS-HandsOn-Notes
Mastering AWS through the Ajira AWS re/Start Program, featuring projects, notes, and practical labs."
AWS Learning Journey 🚀
Welcome to my AWS Learning Journey repository! 🌟 This is where I document everything I learn during the Ajira AWS re/Start Program. From core AWS concepts to hands-on projects, this repo will serve as my knowledge hub as I explore the exciting world of cloud computing.

---

Why I’m Learning AWS
As a tech enthusiast passionate about cloud solutions, I aim to build expertise in Amazon Web Services (AWS) and leverage these skills to solve real-world problems. This program is my first step toward becoming a certified cloud practitioner and advancing my career in tech.

# AWS Learning Journey 🚀

Welcome to my AWS learning journey. I will be documenting what I learn each day about AWS in this repository.

## Onboarding

It was scheduled on Friday 23rd but was postponed due to issue with the emails.

# AWS Restart Program Cohort 12 Kickoff /27 Jan/
* The kickoff meeting for Cohort 12 of the AWS Restart program provided an overview of the upcoming 12-week virtual intensive course:

* The program aims to prepare learners for careers in cloud computing and certify them as AWS Cloud Practitioners.

* Learners will receive classroom-based skills development and training on cloud architecture, security, and other key cloud computing concepts.

* The 392 selected learners, comprising 58% females and 5 persons with disabilities, will be supported by a team of 14 fully certified AWS Restart instructors.

* Learners were encouraged to complete all labs and training classes, prepare well for the certification exams, and not drop out of the program.

* Networking and maintaining professionalism were emphasized as important aspects for learners to focus on during the 12-week journey.

* This kickoff sets the stage for an intensive, hands-on learning experience that will equip the Cohort 12 participants with in-demand cloud computing skills and certifications.

# 27-29 th.

# Summary
The “Basic Computing Concepts” module introduces fundamental computing technologies, emphasizing servers, data centers, and the software development life cycle (SDLC). It defines servers as computers that provide services to other machines, with examples including web, database, and mail servers. Data centers are physical facilities housing servers and networking equipment, which can be owned traditionally or accessed via cloud service providers. The module also covers virtualization and virtual machines, explaining how they allow multiple operating systems to run on a single physical machine. The SDLC outlines a structured process for software development, encompassing planning, analysis, design, development, testing, implementation, and maintenance, aimed at producing high-quality software.

# Key Insights
Servers are specialized computers providing data and services over a network, differing from desktop computers in design and functionality.
Data centers secure and maintain servers and other essential infrastructure, and can be owned by organizations or accessed via cloud providers.
Virtual machines (VMs) allow the emulation of multiple computing environments on a single physical host, enhancing resource efficiency and flexibility.
The software development life cycle (SDLC) is a systematic process that improves software quality through structured phases from planning to maintenance.
Cloud computing leverages virtualization, enabling scalable, cost-effective computing resources through services like Amazon EC2.

Frequently Asked Questions

  * What is a server, and how does it function?
A server is a computer that provides data or services to other computers over a network, responding to client requests.

  * What are the main components of a data center?
* A data center typically contains servers, storage devices, network devices, cooling systems, and uninterruptable power supplies to maintain optimal operation.

  * How do virtual machines benefit cloud computing?

* Virtual machines allow multiple workloads to run on a single physical machine, improving resource utilization, efficiency, and cost-effectiveness in cloud environments.
* What are the phases of the software development life cycle (SDLC)?
* The SDLC consists of the following phases: Plan, Analyze, Design, Develop, Test, Implement, and Maintain, facilitating organized and disciplined software production.
../

# 31st

A summarized, detailed overview of Amazon S3:

### **Amazon S3 (Simple Storage Service)**

**Overview:**
Amazon S3 is a scalable object storage service provided by AWS that allows users to store and manage data with high availability, security, and performance.

**Key Features:**
1. **Scalability:** Can store any amount of data, from small files to large datasets.
2. **Durability:** Ensures data is stored redundantly across multiple facilities.
3. **Availability:** High availability with 99.99% uptime.
4. **Security:** Offers encryption, access control, and compliance with industry standards.
5. **Cost-Effective:** Pay-as-you-go pricing model.

**Storage Classes:**
1. **S3 Standard:** For frequently accessed data with low latency and high throughput.
2. **S3 Standard-IA (Infrequent Access):** For less frequently accessed data with lower storage costs.
3. **S3 One Zone-IA:** Similar to Standard-IA but stored in a single Availability Zone.
4. **S3 Glacier:** For long-term archival with low storage costs.
5. **S3 Glacier Deep Archive:** For data that is rarely accessed and needs the lowest storage cost.
6. **S3 Intelligent-Tiering:** Automatically moves data between access tiers based on usage patterns.

**Key Concepts:**
- **Buckets:** Containers for storing objects (files).
- **Objects:** Individual units of data stored in buckets.
- **Versions:** Keep multiple versions of an object to recover from accidental deletions or overwrites.
- **Lifecycle Policies:** Automate moving data between storage classes or deleting old data.
- **Access Control:** Use policies to manage who can access your data.

**Use Cases:**
- **Data Backup and Restore:** Store backups securely.
- **Static Website Hosting:** Host websites with HTML, CSS, JavaScript, and media files.
- **Big Data Analytics:** Store and analyze large datasets.
- **Content Distribution:** Serve content globally with low latency.
- **Archiving:** Long-term storage of data that is rarely accessed.

**Security Features:**
- **Encryption:** Server-side encryption (SSE) and client-side encryption.
- **Access Control:** Bucket policies, Access Control Lists (ACLs), and IAM roles.
- **Compliance:** Meets various compliance standards like PCI DSS, HIPAA, and GDPR.

**Integration:**
- **AWS Services:** Integrates with services like Amazon EC2, Lambda, and Redshift.
- **Third-Party Applications:** Can be used with various third-party tools and services.

**Access Methods:**
- **AWS Management Console:** Web-based interface for managing S3.
- **AWS CLI:** Command-line interface for scripting and automation.
- **AWS SDKs:** Libraries for integrating S3 with applications in different programming languages.
- **REST API:** Programmatic access to S3 services.
