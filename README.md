# AWS EC2 Windows Server Configuration

This project was completed during **Week 3 of the CloudSec Network AWS Bootcamp**.  
It demonstrates how to **launch, configure, and connect to a Windows Server EC2 instance** using the AWS Management Console.

---

## 🧠 Objective
To deploy a Windows Server instance on AWS, configure its network access securely, and establish a successful Remote Desktop connection.

---

## ⚙️ Steps Performed

1. **Launched a Windows Server EC2 Instance**
   - Deployed a new EC2 instance using the **Amazon Windows Server 2019 Base AMI**.
   - Ensured the instance ran in a **public subnet** for accessibility.

2. **Configured Security Group**
   - Created and attached a Security Group to the EC2 instance.
   - Added an **inbound rule** to allow **RDP access (port 3389)**.
   - Restricted inbound RDP access to **only our public IP address** for enhanced security.

3. **Assigned a Name Tag**
   - Tagged the instance with:
     ```
     Name: CSN-Bootcamp-Week3
     ```

4. **Connected via Remote Desktop**
   - Retrieved the Administrator password using the key pair.
   - Used **Remote Desktop (RDP)** to connect to the instance.
   - Verified a secure and active connection.

---

## 📸 Deliverables
Screenshots are included in the `/screenshots` folder:
- Running Windows EC2 instance in AWS Console  
- Instance tagged as **CSN-Bootcamp-Week3**  
- Security Group showing **RDP (3389)** rule from specific IP  
- Successful Remote Desktop (RDP) connection

---

## 🧩 Skills Demonstrated
- EC2 Instance Deployment
- Windows Server Administration
- Security Group Configuration
- Remote Desktop Protocol (RDP)
- AWS Networking and Security Best Practices

---

## 🧰 Tools & Services Used
- AWS EC2  
- Windows Server 2019 AMI  
- Security Groups  
- Remote Desktop Connection (RDP)

---

## 📅 Week 3 of CloudSec Network AWS Bootcamp
This project concludes Week 3 of the AWS Bootcamp.

---

## 📚 Author
**Zibonele “Rone” Mabaso**  
Full Stack Developer | AWS Cloud Computing Student  
[LinkedIn Profile](www.linkedin.com/in/mpendulo-mabaso-50a1b8315) | [GitHub Profile](https://github.com/zibonelemabaso-jpg)
