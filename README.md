# Apatheia

<img width="1024" height="1024" alt="image" src="https://github.com/user-attachments/assets/f9651eb7-a3be-4cb8-8b33-9f73aa96cd48" />


> **An individual security hygiene protocol aligned with SOC 2 security principles.**

Apatheia is an open-source security hygiene framework that helps individuals build consistent cybersecurity habits through scheduled controls, documented procedures, and measurable compliance.

Unlike enterprise security frameworks, Apatheia focuses on **one person protecting one workstation** while following practices inspired by modern security programs such as SOC 2.

The objective is simple:

> **Make secure behavior repeatable, measurable, and easy to maintain.**

---

# Why Apatheia?

Most security incidents are caused by:

- Forgotten updates
- Weak credential hygiene
- Missing backups
- Configuration drift
- Lack of periodic security reviews

Apatheia turns these into a recurring protocol instead of relying on memory.

It is designed for:

- Security professionals
- Compliance analysts
- Remote employees
- Freelancers
- Consultants
- Developers
- Anyone managing their own workstation

---

# Design Principles

- Security should be boring.
- Security should be scheduled.
- Security should be documented.
- Security should be measurable.
- Automation should replace memory whenever possible.

---

# Alignment with SOC 2

Apatheia is **not a SOC 2 certification framework**.

Instead, it helps individuals adopt security practices that support many of the security objectives commonly found in SOC 2 environments, including:

- Logical access management
- System monitoring
- Change management
- Endpoint protection
- Backup verification
- Risk reduction
- Asset protection
- Incident preparedness

This makes it useful for professionals working in SOC 2 environments who want a repeatable personal security routine.

---

# Security Hygiene Protocol

## Daily Controls

These should require little or no manual effort.

### Endpoint Security

- Verify endpoint protection is running
- Verify EDR/AV signatures are current
- Review security notifications
- Confirm firewall is enabled

### System Health

- Verify operating system updates
- Verify application updates
- Review failed login attempts
- Verify time synchronization

### Data Protection

- Verify scheduled backups completed successfully
- Confirm cloud synchronization status
- Check available disk space

---

## Weekly Controls

These reduce configuration drift.

### Access Management

- Review MFA status
- Remove unused accounts
- Review browser extensions
- Review installed software

### Backup Validation

- Test restoring a backup
- Verify offline or immutable backup availability

### Security Review

- Review endpoint logs
- Check startup applications
- Review scheduled tasks
- Verify disk encryption remains enabled

### Network

- Review Wi-Fi devices
- Check router firmware availability
- Verify DNS configuration

---

## Monthly Controls

These improve long-term resilience.

### Identity Security

- Audit password manager
- Remove unused credentials
- Rotate privileged passwords if required
- Review recovery methods

### Device Hardening

- Verify BIOS/UEFI updates
- Review Secure Boot status
- Review BitLocker/FileVault status
- Verify screen lock policies

### Privacy

- Review application permissions
- Review browser privacy settings
- Remove unnecessary software

### Risk Management

- Review phishing awareness
- Review recent security incidents
- Review security documentation
- Update emergency recovery information

---

## Quarterly Controls

- Test full disaster recovery
- Review hardware inventory
- Review trusted devices
- Review security architecture
- Review authentication methods
- Replace aging backups if necessary

---

# Compliance Score

Each control has a severity.

| Severity | Weight |
|----------|--------:|
| Critical | 5 |
| High | 3 |
| Medium | 2 |
| Low | 1 |

Compliance is calculated using a weighted percentage.

```
Compliance = Completed Weight / Total Weight × 100
```

Status:

| Score | Status |
|--------|--------|
| 95–100% | Compliant |
| 80–94% | At Risk |
| Below 80% | Non-Compliant |

The objective is continuous improvement rather than perfection.

---

# Example Control

| Control | Frequency | Severity |
|----------|-----------|----------|
| Verify backups | Daily | Critical |
| Verify MFA | Weekly | High |
| Review browser extensions | Weekly | Medium |
| Test restore procedure | Monthly | Critical |

---

# Mapping to SOC 2 Security Principles

| Apatheia Control | SOC 2 Alignment |
|------------------|-----------------|
| MFA verification | Logical Access |
| Backup verification | Availability |
| Endpoint protection | System Operations |
| Update management | Change Management |
| Log review | Monitoring Activities |
| Password manager audit | Credential Security |
| Disk encryption | Data Protection |
| Device inventory | Asset Management |

---

# Automation

Apatheia is designed so repetitive tasks can be automated.

Possible integrations include:

- NinjaOne
- Microsoft Intune
- PowerShell
- Bash
- Windows Task Scheduler
- cron
- GitHub Actions
- Google Calendar reminders
- Notion databases
- Obsidian Tasks

Automation should generate alerts only when a control fails.

---

# Roadmap

## Apatheia Lite

A minimal version containing only Daily Controls.

## Compliance Dashboard

Simple weighted scoring with historical trends.

## Notion Template

Track controls and compliance visually.

## Printable Checklist

PDF version for offline use.

## YAML Configuration

Machine-readable control definitions.

## RMM Profiles

Ready-to-import policies for endpoint management platforms.

## CLI Version

Run scheduled security checks from the terminal.

---

# Who Is This For?

- SOC analysts
- Compliance professionals
- Remote workers
- Independent consultants
- Developers
- IT administrators
- MSP technicians
- Privacy-conscious individuals

---

# Non-Goals

Apatheia is **not**:

- an antivirus
- an EDR platform
- a vulnerability scanner
- a SIEM
- a compliance certification
- a replacement for organizational security policies

It is a **personal security hygiene protocol**.

---

# Philosophy

> Good security is rarely about knowing more.
>
> It is about forgetting less.

Apatheia exists to make secure habits consistent, measurable, and sustainable.


---

## Future Ideas

- JSON control definitions
- YAML policies
- Risk scoring engine
- Compliance history
- Automated evidence collection
- Markdown audit reports
- Browser extension
- Desktop reminder application
- Mobile companion app
- Public control library
