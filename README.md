<p align="center">
  <img src="https://raw.githubusercontent.com/anandkrishna25/anandkrishna25/main/profile-banner.png" width="100%" />
</p>
<!-- ============================================================
     GitHub Profile README — anandkrishna25
     AWS Cloud Security Engineer | DevSecOps | Security Automation
     ============================================================ -->


<!-- ANIMATED TYPING BANNER -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=FF9900&center=true&vCenter=true&width=700&lines=AWS+Cloud+Security+Engineer;DevSecOps+%7C+Security+Automation;Building+Self-Healing+Cloud+Infrastructure;Event-Driven+Threat+Remediation;NON_COMPLIANT+%E2%86%92+COMPLIANT+in+%3C3+Minutes)](https://git.io/typing-svg)

<!-- HEADLINE BADGES -->
[![AWS](https://img.shields.io/badge/AWS-Cloud_Security-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)](https://github.com/anandkrishna25)
[![DevSecOps](https://img.shields.io/badge/DevSecOps-Practitioner-2ea043?style=for-the-badge&logo=springsecurity&logoColor=white)](https://github.com/anandkrishna25)
[![Python](https://img.shields.io/badge/Python-3.12-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://github.com/anandkrishna25)
[![Open to Work](https://img.shields.io/badge/Open_to-Security_Roles-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/anandkrishna25)

</div>

---

## `$ whoami`

```python
engineer = {
    "name"     : "Anand Krishna",
    "location" : "Nellore, India",
    "focus"    : ["AWS Cloud Security", "DevSecOps", "Security Automation"],
    "building" : "Enterprise SOAR pipelines on AWS",
    "mttr"     : "< 3 minutes (NON_COMPLIANT → COMPLIANT, zero manual steps)",
    "approach" : "Detect → Automate → Remediate → Document",
    "status"   : "Open to Cloud Security / DevSecOps roles"
}
```

> I build **event-driven, self-healing AWS security systems** that detect misconfigurations
> and automatically fix them — faster than any human security team can respond.
> My work is grounded in real debugging, not just tutorials.

---

## `$ cat featured_project.txt`

<div align="center">

### 🛡️ AWS Cloud Security Auto-Healing Platform

</div>

```
Architecture:
  S3 misconfiguration → AWS Config (NON_COMPLIANT)
      → EventBridge (event routing)
          → Lambda (auto-remediation)
              → SNS (security alert)
                  → AWS Config (COMPLIANT ✓)

MTTR: < 3 minutes | Zero manual intervention | 100% AWS Free Tier
```

**What makes this project real:**

Two production bugs discovered and resolved through CloudWatch Logs analysis:

| Bug | Symptom | Root Cause | Fix |
|-----|---------|-----------|-----|
| `AttributeError` | Lambda crashes silently | Wrong boto3 method: `put_bucket_public_access_block()` doesn't exist | Use `put_public_access_block()` |
| Still `NON_COMPLIANT` | Config shows violation despite block enabled | Config evaluates raw policy text, not block settings | Add `delete_bucket_policy()` as Step 1 |

**Services used:**
`AWS Organizations` · `CloudTrail` · `AWS Config` · `Config Aggregator` · `EventBridge`
`Lambda (Python 3.12)` · `SNS` · `CloudWatch` · `Security Hub` · `IAM / SCPs`

[![View Project](https://img.shields.io/badge/View_Project-aws--cloud--security--auto--healing-FF9900?style=for-the-badge&logo=github&logoColor=white)](https://github.com/anandkrishna25/aws-cloud-security-auto-healing)
[![Post-Mortem](https://img.shields.io/badge/Read-Incident_Post--Mortem-red?style=for-the-badge&logo=googledocs&logoColor=white)](https://github.com/anandkrishna25/aws-cloud-security-auto-healing/blob/main/docs/INCIDENT_POST_MORTEM.md)

---

## `$ ls tech-stack/`

<div align="center">

### AWS Security Services

![AWS Config](https://img.shields.io/badge/AWS_Config-Compliance_Monitoring-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![EventBridge](https://img.shields.io/badge/EventBridge-Event_Routing-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Lambda](https://img.shields.io/badge/Lambda-Auto_Remediation-FF9900?style=flat-square&logo=awslambda&logoColor=white)
![CloudTrail](https://img.shields.io/badge/CloudTrail-Audit_Logging-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Security Hub](https://img.shields.io/badge/Security_Hub-CSPM-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![CloudWatch](https://img.shields.io/badge/CloudWatch-Monitoring-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![SNS](https://img.shields.io/badge/SNS-Alerting-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![IAM](https://img.shields.io/badge/IAM_%2F_SCPs-Governance-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![S3](https://img.shields.io/badge/S3-Storage_%26_Remediation-FF9900?style=flat-square&logo=amazons3&logoColor=white)
![Organizations](https://img.shields.io/badge/Organizations-Multi--Account-FF9900?style=flat-square&logo=amazonaws&logoColor=white)

### Languages & Tools

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Boto3](https://img.shields.io/badge/boto3-AWS_SDK-FF9900?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-Scripting-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Git](https://img.shields.io/badge/Git-Version_Control-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-Portfolio-181717?style=flat-square&logo=github&logoColor=white)
![JSON](https://img.shields.io/badge/JSON-Policies_%26_Rules-000000?style=flat-square&logo=json&logoColor=white)

### Security Concepts

![DevSecOps](https://img.shields.io/badge/DevSecOps-Practitioner-2ea043?style=flat-square)
![SOAR](https://img.shields.io/badge/SOAR-Security_Automation-8B0000?style=flat-square)
![CSPM](https://img.shields.io/badge/CSPM-Cloud_Posture-1E3A5F?style=flat-square)
![IaC Security](https://img.shields.io/badge/IaC_Security-Policy_as_Code-6B21A8?style=flat-square)
![CIS Benchmark](https://img.shields.io/badge/CIS-AWS_Foundations_1.4-003087?style=flat-square)
![Least Privilege](https://img.shields.io/badge/IAM-Least_Privilege-FF6B35?style=flat-square)

</div>

---

## `$ git log --oneline projects/`

| Project | Description | Stack | Status |
|---------|-------------|-------|--------|
| [aws-cloud-security-auto-healing](https://github.com/anandkrishna25/aws-cloud-security-auto-healing) | SOAR-style S3 & IAM auto-remediation platform | Config · EventBridge · Lambda · SNS | ✅ Complete |
| aws-devsecops-pipeline *(coming)* | CI/CD pipeline with SAST, IaC scanning, secret detection | GitHub Actions · Python · AWS | 🔨 Building |
| iam-privilege-monitor *(coming)* | Real-time IAM escalation detection & auto-revoke | CloudTrail · EventBridge · Lambda | 📋 Planned |
| cloudtrail-threat-hunter *(coming)* | CloudWatch metric filters for threat hunting | CloudWatch · CloudTrail · Python | 📋 Planned |

---

## `$ cat github_stats.md`

<div align="center">

[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=anandkrishna25&show_icons=true&theme=github_dark&hide_border=true&bg_color=0D1117&title_color=FF9900&icon_color=FF9900&text_color=C9D1D9&ring_color=FF9900)](https://github.com/anandkrishna25)

[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=anandkrishna25&layout=compact&theme=github_dark&hide_border=true&bg_color=0D1117&title_color=FF9900&text_color=C9D1D9)](https://github.com/anandkrishna25)

[![GitHub Streak](https://streak-stats.demolab.com?user=anandkrishna25&theme=github-dark-blue&hide_border=true&background=0D1117&stroke=FF9900&ring=FF9900&fire=FF9900&currStreakLabel=FF9900)](https://github.com/anandkrishna25)

</div>

---

## `$ cat key_learnings.log`

```
[INFO]  AWS Config evaluates RAW bucket policy text — not just Public Access Block settings
[INFO]  boto3 S3 API is inconsistent: get_bucket_public_access_block() vs put_public_access_block()
[INFO]  Auto-remediation requires COMPLETE cleanup logic, not just partial fixes
[INFO]  CloudWatch Logs is the essential debugging tool for production Lambda pipelines
[INFO]  Testing full closed-loop (event → detect → remediate → re-evaluate) is mandatory
[INFO]  Mean Time To Remediation matters more than alert volume in real security operations
```

---

## `$ ping me`

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/anandkrishna25)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/anandkrishna25)
[![Email](https://img.shields.io/badge/Email-Hire_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:your@email.com)

**Open to:** Cloud Security Engineer · DevSecOps Engineer · AWS Security Architect roles

</div>

---

<div align="center">
<sub>Built with real AWS debugging experience · 100% Free Tier · Hyderabad, India</sub>
</div>
