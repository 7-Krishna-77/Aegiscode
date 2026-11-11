# AegisCode 🛡️
> Client-Side Zero-Trust Script & Dependency Shield

AegisCode is a **shift-left security tool** that brings the **zero-trust paradigm ("Never Trust, Always Verify")** directly into the developer workflow. Instead of catching vulnerabilities too late in production, it analyzes pasted scripts and dependencies in real-time to intercept hardcoded secrets, injection risks, and unsafe execution vectors.

---

## 🚀 Key Features

* **Real-Time Zero-Trust Inspection:** Evaluates source code against security checks including exposed API secrets, dangerous `eval()` execution, unencrypted HTTP endpoints, weak cryptographic algorithms, and unsanitized DOM injections.
* **Dynamic Risk Scoring:** Computes an immediate **Trust Score (0–100)** alongside line-by-line threat telemetry and severity badges (`CRITICAL`, `WARNING`, `INFO`).
* **1-Click Automated Remediation:** Features a self-healing engine that automatically patches flagged vulnerabilities live (abstracting secrets to environment variables, converting `eval` to `JSON.parse`, and upgrading HTTP to HTTPS).
* **Zero-Dependency Client Architecture:** Runs 100% locally in the browser with no backend dependencies or external server overhead.

---

## 🛠️ Tech Stack & Architecture

* **Frontend:** HTML5, Modern ES6+ JavaScript
* **Styling:** Tailwind CSS (Custom Dark SOC Theme)
* **Security Engine:** Custom client-side pattern scanner simulating Abstract Syntax Tree (AST) vulnerability parsing
* **Execution Model:** Zero-Trust Least-Privilege Verification Framework

---

   
