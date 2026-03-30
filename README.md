📌 Overview
Project Nexus and Project Sentinel are two enterprise-grade solutions built as a single unified dashboard to tackle two critical problems:
ProjectProblem It SolvesNexusAutomates IT support tickets using GenAI with Human-in-the-Loop (HITL) escalationSentinelDetects and mitigates cloud identity threats in real time using predictive ML

✨ Features
Project Nexus — Intelligent Support

AI Ticket Analysis — Submit a ticket and GenAI streams a diagnosis instantly
Confidence Score Logic — Tickets scoring ≥90% are auto-resolved; below 90% triggers HITL escalation
HITL Review Queue — Human reviewers see all AI-drafted responses that need approval
Resolution Timeline — Full audit trail of every ticket and action taken
Category Breakdown — Visual breakdown of ticket types (Auth, Billing, Security, etc.)

Project Sentinel — Automated Cloud Guard

Real-Time Anomaly Alerts — Live stream of threats classified as Critical / High / Medium
Cloud Identity Heatmap — 8 AWS services × 24h time window, color-coded by risk level
Zero-Trust IAM Actions — Auto-blocks sessions, rotates credentials, strips over-privileged roles
Network Topology — Animated live map of your cloud architecture with data flows
Compliance Dashboard — SOC 2, ISO 27001, PCI DSS, GDPR, HIPAA, NIST scores

Threat Intelligence Tab

Active threat actor tracking (APT-41, Lazarus Group, Scattered Spider, etc.)
CVE feed with CVSS scores
Attack vector distribution (Credential Stuffing, Phishing, API Abuse, etc.)
Global geo-threat map with live pulsing indicators

UI Highlights

Bioluminescent deep-space theme with animated particle network background
Custom glowing cursor with trail
Live scrolling ticker with platform-wide status updates
Animated neural network canvas representing AI decision-making
Toast notifications for critical events
Fully responsive single-file HTML — no dependencies, no build step


🚀 Getting Started
Option 1 — Open directly in browser
bashgit clone https://github.com/your-username/nexus-sentinel.git
cd nexus-sentinel
open nexus-sentinel-v2.html
Option 2 — Live Server (VS Code)

Install the Live Server extension in VS Code
Right-click nexus-sentinel-v2.html
Click Open with Live Server


No npm, no dependencies, no build process required. It is a single HTML file.


📁 Project Structure
nexus-sentinel/
│
├── nexus-sentinel-v2.html     # Main application — everything in one file
└── README.md                  # You are here

🛠 Tech Stack
LayerTechnologyFrontendHTML5, CSS3, Vanilla JavaScriptFontsOrbitron, JetBrains Mono (Google Fonts)GraphicsCanvas API (particles + neural network)ChartsPure JS — no Chart.js dependencyIconsUnicode symbols + inline SVGAI (Simulated)Confidence Score Logic with HITL routing

📊 Key Metrics (Projected)
MetricTargetManual ticket reduction70%SLA response improvement50% fasterIdentity breach risk reduction99.9%AI auto-resolution rate83%+Zero-Trust Score9.4 / 10

🧭 How to Use

Overview Tab — See all live stats, submit a ticket, and watch alerts stream in
Project Nexus Tab — Browse the ticket queue, HITL review queue, and resolution timeline
Project Sentinel Tab — Explore the heatmap, ZT actions, topology, and compliance scores
Threat Intel Tab — View tracked threat actors, CVEs, attack vectors, and geo map

Submitting a Test Ticket

Go to the Overview tab
Fill in Subject, Priority, Category, and Description
Click Analyze with Nexus AI
Watch the AI type its response and the confidence score animate
If confidence < 90%, the HITL banner will appear automatically

Simulating a Threat

Go to Overview or Sentinel tab
Click + Simulate Threat in the Anomaly Alerts panel
A new alert will appear with severity classification and timestamp


🎯 Architecture (Conceptual)
User Request
     │
     ▼
 Nexus AI (GenAI)
     │
     ├── Confidence ≥ 90% ──► Auto-Resolved ✅
     │
     └── Confidence < 90% ──► HITL Review 👤
                                    │
                                    ▼
                             Human Approves ──► Resolved ✅

Cloud Events
     │
     ▼
 Sentinel ML
     │
     ├── Anomaly Detected ──► Alert Fired 🔴
     │
     └── Threat Confirmed ──► ZT Action ⚡
              │
              ├── Block Session
              ├── Rotate Credentials
              └── Strip IAM Role

📽 Demo
A 1-minute walkthrough video is available covering:

AI ticket submission with confidence scoring
HITL escalation trigger
Live anomaly alert simulation
Cloud identity heatmap
Threat intelligence dashboard


👨‍💻 Author
Built as part of an enterprise AI solutions proposal.

📄 License
This project is for demonstration and academic purposes.
