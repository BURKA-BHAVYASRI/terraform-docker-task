# terraform-docker-task
Here’s a well-structured `README.md` file based on the content you provided:

---

````markdown
🌐 DevOps Internship - Task 3: Terraform & Docker

🧩 Project Overview
This project showcases how to use **Terraform**, an Infrastructure as Code (IaC) tool, to automate the provisioning of a local **Nginx Docker container**. It’s a great starting point for learning automated infrastructure management!

✅ Features
- Pulls the official Nginx Docker image
- Launches a container with port mapping
- Automates setup and teardown
- Demonstrates key DevOps concepts using real tools

---

🛠️ Tools Used
- **Terraform (v1.5+)** – Infrastructure as Code
- **Docker** – Containerization platform
- **Git/GitHub** – Version control system

---

🚀 Getting Started
1. Clone the Repository
```bash
git clone https://github.com/your-username/terraform-docker-task.git
cd terraform-docker-task
````

2. Initialize Terraform

```bash
terraform init
```

3. Preview the Infrastructure Plan

```bash
terraform plan
```

4. Apply Configuration (Provision Container)

```bash
terraform apply
# Type 'yes' when prompted
```

5. Verify Setup

Check running Docker containers:

```bash
docker ps
```

Open your browser and visit:
[http://localhost:8000](http://localhost:8000)

6. Clean Up Resources

```bash
terraform destroy
# Type 'yes' to confirm
```

---

📂 Project Structure

| File         | Description                        |
| ------------ | ---------------------------------- |
| `main.tf`    | Terraform configuration for Docker |
| `.gitignore` | Excludes sensitive or local files  |

---

💡 Key Learnings

* **Infrastructure as Code (IaC):** Automate infrastructure using config files.
* **Terraform Workflow:** `init` → `plan` → `apply` → `destroy`
* **Docker Fundamentals:** Containers, images, and port mapping.

---


 ⚠️ Troubleshooting

* **Docker not running?** Start Docker Desktop or Engine first.
* **Port 8000 in use?** Change the external port in `main.tf`.
* **Permission denied?** Run with `sudo` (Linux/macOS) or as Admin (Windows).

---

🎉 Bonus Challenges

Try enhancing the project by modifying `main.tf` to:

* Use Apache (`httpd`) instead of Nginx
* Add environment variables
* Mount Docker volumes for data persistence

Pull requests are welcome!

---

> *"Automation isn't lazy—it’s smart engineering."*
> — Every DevOps Engineer Ever

---

---

```

Let me know if you want me to generate a sample `main.tf` to go along with this!
```
