<div align="center">

  <!-- Header Banner -->
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=1,12,24,36&height=220&section=header&text=Vishal%20Yadav&fontSize=52&fontAlignY=38&animation=twinkling&desc=Aspiring%20DevOps%20%26%20Cloud%20Engineer&descFontSize=20&descAlignY=62" width="100%" alt="Vishal Yadav Banner" />

  <!-- Animated Typing Subtitle -->
  <a href="https://github.com/vishalnik002-git">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&pause=1000&color=00D2FF&center=true&vCenter=true&width=680&lines=Aspiring+DevOps+%26+Cloud+Engineer;MCA+Student+%40+Galgotias+University;Hands-on+with+Terraform+%26+Microsoft+Azure;Automating+CI%2FCD+with+Pipelines+%26+IaC" alt="Typing SVG" />
  </a>

  <p align="center">
    <a href="https://www.linkedin.com/in/vishal-yadav002">
      <img src="https://img.shields.io/badge/LinkedIn-Vishal_Yadav-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    <a href="mailto:Vishalnik002@gmail.com">
      <img src="https://img.shields.io/badge/Email-Vishalnik002%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
    </a>
    <img src="https://komarev.com/ghpvc/?username=vishalnik002-git&label=PROFILE%20VIEWS&color=0078D4&style=for-the-badge" alt="Profile Views" />
  </p>

</div>

---

### 👨‍💻 About Me

- 🎓 **Education:** Master of Computer Applications (MCA) at **Galgotias University** with an **8.0+ CGPA**.
- 🛠️ **Training & Experience:** DevOps & Cloud Trainee at **DevOps Insiders** | Virtual Intern at **AICTE EduSkills**.
- ☁️ **Specialization:** Focus on **Infrastructure as Code (Terraform)**, **Microsoft Azure**, and automated **CI/CD delivery pipelines**.
- 🎯 **Philosophy:** Bridging software delivery and infrastructure with consistent automation, security best practices, and cost-efficient cloud designs.
- ⚡ **Current Focus:** Sharpening automated multi-environment infrastructure provisioning and enterprise-grade pipeline security.

---

### 🛠️ Technical Skills

#### 🚀 Core Skills (Strong Hands-On)
<p align="left">
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" alt="Terraform" />
  <img src="https://img.shields.io/badge/Microsoft_Azure-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white" alt="Microsoft Azure" />
  <img src="https://img.shields.io/badge/Azure_DevOps_Pipelines-0078D7?style=for-the-badge&logo=azure-devops&logoColor=white" alt="Azure DevOps Pipelines" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
</p>

#### 🧰 Basics & Supporting Tools
<p align="left">
  <img src="https://img.shields.io/badge/Docker_(Basics)-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker Basics" />
  <img src="https://img.shields.io/badge/Kubernetes_(Basics)-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes Basics" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white" alt="PowerShell" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
</p>

---

### 🔄 Production CI/CD Workflow

```mermaid
flowchart LR
    A["Git Push<br/><code>feature/*</code>"] --> B["CI Checks<br/><code>fmt, validate, TFLint, tfsec</code>"]
    B --> C["Pull Request<br/>to <code>main</code>"]
    C --> D["Terraform Plan<br/>Execution"]
    D --> E["Manual Approval<br/>Gate"]
    E --> F["Terraform Apply<br/><code>Azure Infra Live</code>"]
    F --> G["Remote State<br/><code>Azure Blob Storage</code>"]
```

---

### 📂 Featured Hands-On Projects

| Project | Tech Stack | Architecture & Key Deliverables |
| :--- | :--- | :--- |
| **Multi-Environment Azure Infra with Terraform & CI/CD** | `Terraform` `Azure` `Azure DevOps` `Git` `TFLint` `tfsec` | • Built automated, isolated **Dev & Prod** environments (Resource Groups, Virtual Networks, Subnets, NSGs, and Linux VMs running Nginx).<br/>• Structured with modular, DRY Terraform architecture with parameter-driven variables.<br/>• State persistence configured via **Azure Blob Remote State** with state lease locking.<br/>• Automated pre-commit & CI checks: syntax formatting, validation, `TFLint`, security scans with `tfsec`, and mandatory manual gate before apply. |
| **Automated Cloud Cost Cleaner (Azure Automation)** | `Microsoft Azure` `PowerShell Runbooks` `Resource Locks` | • Developed scheduled serverless **PowerShell Runbooks** executing every 2 hours.<br/>• Automatically detects and terminates ephemeral/idle lab Resource Groups to eliminate stray compute billing.<br/>• Enforces **Azure Delete Locks** on persistent baselines and critical storage resources to guarantee zero accidental deletions. |
| **Containerized Web App Deployment** | `Python Flask` `Docker` `GitHub Actions` `Azure Container Registry` `Azure App Service` | • Packaged a responsive Python Flask dashboard application into multi-stage, hardened Docker images.<br/>• Automated unit test execution (`pytest`) directly inside GitHub Actions CI runner on code push.<br/>• Triggered automated container pushes to **Azure Container Registry (ACR)** and continuous deployments to **Azure App Service**. |

---

### 📊 GitHub Activity & Analytics

<div align="center">
  <table border="0">
    <tr>
      <td>
        <img src="https://github-readme-stats.vercel.app/api?username=vishalnik002-git&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Vishal's GitHub Stats" />
      </td>
      <td>
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=vishalnik002-git&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" />
      </td>
    </tr>
    <tr>
      <td colspan="2" align="center">
        <img src="https://streak-stats.demolab.com/?user=vishalnik002-git&theme=tokyonight&hide_border=true" alt="GitHub Streak Stats" />
      </td>
    </tr>
  </table>
</div>

---

<div align="center">

  <p><b>✨ <i>"Write Clean IaC • Automate with Pipelines • Keep Cloud Costs Zero"</i> ✨</b></p>

  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=1,12,24,36&height=100&section=footer" width="100%" alt="Footer Wave" />

</div>
