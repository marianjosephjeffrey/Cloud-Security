# ☁️ Cloud Security with Amazon AWS & Microsoft Azure  

## 📌 Overview  
As part of a **cloud security project at the University of Maryland**, I optimized a **healthcare company's cloud infrastructure**, focusing on **security, scalability, and risk mitigation**. The project involved implementing **AWS security tools**, developing **cloud architecture strategies**, and enhancing **compliance with best practices**.  

---

## 🛠 Key Contributions  

- 🔐 **Strengthened cloud security** using **AWS GuardDuty for threat detection** and **AWS WAF for web application protection**.  
- 🏗 **Documented and recommended AWS services**, including **AWS Lambda, CloudFormation, CLI, and Elastic Beanstalk** to optimize cloud infrastructure.  
- 🔄 **Implemented AWS Identity & Access Management (IAM)** to enforce **least privilege access control** and **secure authentication**.  
- ⚡ **Developed risk mitigation strategies**, ensuring a **secure and scalable cloud computing environment**.  
- 🌍 **Integrated Microsoft Azure security tools**, ensuring **cross-platform compatibility** for hybrid cloud environments.  
- 🛡 **Enhanced compliance** with **cloud security best practices**, ensuring **HIPAA and industry standards were met** for healthcare data protection.  

---

## 🛠 Tools & Technologies Used  

| Category                     | Tools & Technologies |
|------------------------------|----------------------|
| ☁️ Cloud Platforms           | AWS, Microsoft Azure |
| 🔍 Cloud Security Monitoring | AWS GuardDuty, Azure Security Center |
| 🔥 Web Security              | AWS WAF, Azure WAF |
| 🔐 Identity & Access Control | AWS IAM, Azure Active Directory |
| 🏗 Cloud Automation          | AWS CloudFormation, Azure Resource Manager |
| 🚀 Serverless Computing      | AWS Lambda, Azure Functions |
| 🔄 Deployment & Scaling      | AWS Elastic Beanstalk, Azure App Services |
| 💻 Cloud Management          | AWS CLI, Azure CLI |
| 📜 Compliance & Best Practices | NIST, HIPAA, CIS Benchmarks |

---

## ⚙️ Sample Configurations  

### 🔐 Enforcing IAM Least Privilege Policy in AWS  
```json
{
  "Version": "2012-10-17",
  "Statement": [
    {
      "Effect": "Allow",
      "Action": "s3:GetObject",
      "Resource": "arn:aws:s3:::secure-bucket/*"
    }
  ]
}
```
🏗 Deploying a CloudFormation Stack for a Secure Web Application
```yaml
Resources:
  WebServerInstance:
    Type: "AWS::EC2::Instance"
    Properties:
      ImageId: "ami-0abcdef1234567890"
      InstanceType: "t2.micro"
      SecurityGroups:
        - "WebServerSG"
```
🔍 Enabling AWS GuardDuty for Threat Detection
```bash
aws guardduty create-detector --enable
```

⸻

📋 Final Report & Evaluation

The project concluded with a comprehensive report detailing:

✅ Cloud security assessment, identifying risks in AWS and Azure environments.
✅ Implementation of security controls, including IAM, WAF, and GuardDuty.
✅ Cloud infrastructure optimization, using serverless computing and automated deployment strategies.
✅ Risk mitigation strategies, ensuring a secure and compliant cloud computing environment.
✅ Final presentation and documentation, summarizing findings and recommendations for scalability and security.

⸻

🎤 Presentation & Impact

I compiled the findings and security improvements into a technical presentation, demonstrating real-world cloud security applications for a healthcare organization.

⸻

💬 Have Questions?

Feel free to reach out or open an issue! 🚀🔐
