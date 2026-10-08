# Ethical Hacking – Milestone 2
## Legal Scope and Isolated Lab

### Objective
Create an isolated, beginner-friendly security testing laboratory and define clear Rules of Engagement (RoE). Testing is restricted to systems that I own or have explicit authorization to test.

### Lab Target
Recommended target: **OWASP Juice Shop** running locally.

Alternative: DVWA running locally.

### Scope
**In scope**
- The intentionally vulnerable local lab target.
- Security testing performed from the designated lab machine.
- Only techniques explicitly allowed by the Rules of Engagement.

**Out of scope**
- Public websites and Internet-facing systems.
- College/university systems.
- Employer/client systems without written authorization.
- Other people's devices, accounts, Wi-Fi networks, servers, APIs, or cloud resources.
- Any target discovered accidentally outside the lab.

### Isolation
The lab should run locally and should not expose the vulnerable target directly to the public Internet.

### Topology
See `Lab-Topology.png`.

### Evidence
Add your own screenshots to the `screenshots/` folder. Do not use fabricated screenshots.

Suggested evidence:
1. Vulnerable application running locally.
2. Local target address/port.
3. Virtual machine/container or local isolation configuration.
4. Network configuration showing the intended isolated setup.
5. Final lab test showing the target is reachable only as intended.

### Stop Conditions
Testing must stop immediately if:
- The target is no longer the intended lab target.
- Traffic leaves the authorized lab environment unexpectedly.
- A real third-party system is encountered.
- The activity could affect systems or data outside the authorized scope.
- The lab owner/instructor asks testing to stop.

### Safety Statement
This repository documents an authorized practice environment only. No testing is intended against systems that I do not own or control or for which I do not have explicit permission.
