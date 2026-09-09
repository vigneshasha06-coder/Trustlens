# TrustLens

## AI-Powered Job & Internship Scam Detection and Verification

**TrustLens** is an individual web application developed by **Vignesh G** to help students and job seekers evaluate suspicious job and internship opportunities before they apply, make payments, or share personal information.

Instead of giving only a simple **SCAM / NOT SCAM** result, TrustLens analyzes multiple signals such as URLs, opportunity content, company information, recruiter details, screenshots, OCR-extracted text, and threat intelligence to produce a clear, risk-oriented assessment.

> **Important:** TrustLens is a decision-support tool. Its results are indicators that can help users investigate an opportunity further. It does not guarantee that an opportunity is legitimate or fraudulent.

---

## 👨‍💻 Developer

| Project Information | Details |
|---|---|
| **Project Name** | **TrustLens** |
| **Project Type** | **Individual Project** |
| **Developer** | **Vignesh G** |
| **Domain** | **Artificial Intelligence + Cybersecurity** |
| **Development Progress** | **45%** |
| **Target Users** | **Students and Job Seekers** |
| **Platform** | **Web Application** |
| **Primary Goal** | **Job & Internship Opportunity Verification** |

---

## 🎯 Project Objective

Online job and internship scams can be difficult to identify because suspicious opportunities may look professional and may be shared through websites, messages, emails, or documents.

TrustLens aims to make the verification process easier by bringing multiple checks into one platform and presenting the findings in an understandable way.

### Main Objectives

- Analyze suspicious job and internship URLs.
- Identify potentially risky URL and domain characteristics.
- Verify available company information.
- Analyze recruiter-related information.
- Extract text from screenshots and images using OCR.
- Analyze opportunity content for warning signals.
- Combine multiple signals into a risk assessment.
- Provide AI-assisted explanations of detected risks.
- Generate a structured verification report.
- Help users make informed decisions before proceeding.

---

## 🚨 Problem Statement

Students and job seekers frequently receive job and internship opportunities through career websites, social media, messaging applications, email, and direct recruiter communication.

Manually verifying every opportunity can be time-consuming because relevant information is distributed across different sources. Users may also find it difficult to understand whether a suspicious URL, recruiter, company claim, payment request, or offer document should be trusted.

**TrustLens addresses this problem by providing a centralized platform for evidence-based opportunity verification.**

---

## 💡 Proposed Solution

TrustLens accepts information related to a job or internship opportunity and processes it through multiple verification stages.

### Input Types

- Job or internship URL
- Screenshot or image
- Pasted opportunity text
- Offer-letter or document evidence
- Company information
- Recruiter information

### Analysis Areas

| Area | Purpose |
|---|---|
| URL Analysis | Identifies suspicious URL and domain signals |
| Content Analysis | Examines opportunity content for warning signs |
| OCR | Extracts text from screenshots/images |
| Company Verification | Checks available company-related information |
| Recruiter Verification | Evaluates recruiter-related details |
| Threat Intelligence | Supports investigation of suspicious indicators |
| Risk Engine | Combines signals into a risk-oriented assessment |
| AI Assistance | Explains findings in a user-friendly manner |
| Reporting | Presents analysis results in a structured format |

---

## 🔄 System Workflow

```text
                    USER
                      |
                      v
              Evidence Submission
                      |
          +-----------+-----------+
          |           |           |
          v           v           v
        URL       Screenshot      Text
          |           |           |
          v           v           v
    URL Analysis     OCR      Content Analysis
          |           |           |
          +-----------+-----------+
                      |
                      v
          +-------------------------+
          | Company Verification    |
          | Recruiter Verification  |
          +------------+------------+
                       |
                       v
             Threat Intelligence
                       |
                       v
                  Risk Engine
                       |
                       v
             AI-Assisted Explanation
                       |
                       v
               Verification Report
```

---

## 🧠 Why TrustLens Uses Multiple Signals

A single indicator is not always enough to determine whether an opportunity is suspicious.

For example, a new company website does not automatically mean that the company is fraudulent. Similarly, a professional-looking offer letter does not prove that an opportunity is genuine.

TrustLens therefore combines different categories of evidence before producing a risk-oriented result.

```text
URL Signals
     +
Company Signals
     +
Recruiter Signals
     +
Content Signals
     +
Evidence Signals
     +
Threat Intelligence
     |
     v
Risk Processing
     |
     v
Explainable Assessment
```

---

## 🤖 AI-Assisted Analysis

TrustLens uses AI as an assistance layer rather than treating AI output as unquestionable truth.

The AI layer can help:

- Summarize detected warning signals.
- Explain technical findings in simpler language.
- Organize evidence into understandable observations.
- Help users understand why a risk indicator was generated.

### Responsible AI Approach

```text
Input Evidence
      |
      v
Structured Analysis
      |
      v
AI-Assisted Explanation
      |
      v
Human Review / User Decision
```

AI-generated explanations may contain errors, so results should be interpreted together with the available evidence.

---

## ✨ Key Features

### 1. URL Analysis

Analyzes submitted job or internship URLs and identifies relevant URL/domain signals.

### 2. Evidence Analysis

Processes submitted evidence such as screenshots, images, and opportunity information.

### 3. OCR-Based Text Extraction

Uses **Tesseract.js** to extract text from images so visible opportunity details can be analyzed.

### 4. Company Verification

Analyzes available company information and identifies verification-related signals.

### 5. Recruiter Verification

Provides a dedicated module for analyzing recruiter-related information.

### 6. Threat Intelligence

Uses threat-intelligence and URL-intelligence modules to support suspicious indicator analysis.

### 7. Risk Assessment

Combines different signals instead of relying on a single check.

### 8. AI-Assisted Explanation

Converts technical analysis results into explanations that are easier for users to understand.

### 9. Authentication

Provides user authentication and protected application areas using Supabase.

### 10. Verification Report

Presents analysis findings in a structured report so users can review the evidence before making a decision.

---

## 🛠️ Technology Stack

| Category | Technology |
|---|---|
| Framework | Next.js 16 |
| Frontend | React 19 |
| Programming Language | TypeScript 5 |
| Styling | Tailwind CSS 4 |
| Authentication & Database | Supabase |
| OCR | Tesseract.js |
| Icons | Lucide React |
| Linting | ESLint 9 |
| Package Manager | npm |
| Version Control | Git & GitHub |

---

## 🏗️ Application Architecture

### API Layer

```text
src/app/api/
├── analyze-ai/
├── analyze-evidence/
├── analyze-url/
└── verify-company/
```

### Core Processing Modules

```text
src/lib/
├── ai/
├── analytics/
├── company-intelligence/
├── content-intelligence/
├── evidence/
├── recruiter-verification/
├── report/
├── risk/
├── risk-engine/
├── security/
├── supabase/
├── threat-intel/
└── url-intelligence/
```

---

## 🖥️ Application Flow

```text
Landing Page
     |
     v
Authentication
     |
     v
Dashboard
     |
     v
Submit Opportunity
     |
     v
Select Evidence
     |
     v
Run Analysis
     |
     v
Review Risk Signals
     |
     v
AI Explanation
     |
     v
Final Report
```

---

## 📂 Project Structure

```text
Trustlens/
├── .env.example
├── .gitignore
├── AGENTS.md
├── CLAUDE.md
├── README.md
├── eng.traineddata
├── eslint.config.mjs
├── next.config.ts
├── package.json
├── package-lock.json
├── postcss.config.mjs
├── public/
├── scripts/
│   ├── debug-screenshot-analysis.ts
│   ├── run-all-tests.ts
│   ├── test-ocr-all-scenarios.ts
│   ├── test-ocr.ts
│   ├── test-server-ocr-flow.ts
│   ├── test-tesseract-local.ts
│   └── verify-tesseract-paths.ts
├── src/
│   ├── app/
│   │   ├── api/
│   │   ├── auth/
│   │   ├── dashboard/
│   │   ├── login/
│   │   ├── report/
│   │   └── signup/
│   ├── components/
│   ├── context/
│   ├── lib/
│   └── types/
└── supabase/
```

---

## ⚙️ Installation

### Prerequisites

- Node.js LTS
- npm
- Git
- A Supabase project

### 1. Clone the Repository

```bash
git clone https://github.com/vigneshasha06-coder/Trustlens.git
cd Trustlens
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Environment Variables

Create a local environment file using the provided example:

```bash
cp .env.example .env.local
```

Add the required configuration values to `.env.local`.

> **Security:** Never commit API keys, database credentials, access tokens, or other secrets to GitHub.

### 4. Start the Development Server

```bash
npm run dev
```

### 5. Production Build

```bash
npm run build
npm start
```

### 6. Run Linting

```bash
npm run lint
```

---

## 🧪 Testing

The repository contains scripts for testing OCR and analysis-related functionality.

```text
scripts/
├── run-all-tests.ts
├── test-ocr.ts
├── test-ocr-all-scenarios.ts
├── test-server-ocr-flow.ts
├── test-tesseract-local.ts
└── verify-tesseract-paths.ts
```

### Recommended Test Areas

| Test | Purpose |
|---|---|
| URL Analysis | Check URL processing and error handling |
| Evidence Analysis | Validate submitted evidence processing |
| OCR | Verify text extraction from images |
| Company Verification | Validate company-related checks |
| Authentication | Test login and signup flows |
| Invalid Input | Verify safe handling of invalid data |
| Risk Processing | Check aggregation of multiple signals |
| Report Generation | Verify final analysis output |

Before an academic or production release, record actual test results rather than assuming that every test passes.

---

## 🔐 Security & Privacy

TrustLens is intended to handle potentially sensitive opportunity evidence responsibly.

### Security Practices

- Keep secrets in environment variables.
- Never commit production credentials.
- Validate user-provided input.
- Handle external service failures safely.
- Restrict access to protected application areas.

### Privacy Practices

- Avoid collecting unnecessary personal information.
- Do not publish private recruiter or participant information.
- Anonymize research participants when documenting user studies.
- Store submitted evidence only when required by the application workflow.

---

## ⚠️ Limitations

TrustLens is not a guaranteed scam detector.

- Results depend on the quality and availability of evidence.
- External company and domain information may change.
- Some legitimate opportunities may contain unusual characteristics.
- Sophisticated scams may not produce obvious warning signals.
- False positives and false negatives are possible.
- OCR accuracy depends on image quality and document layout.
- AI-generated explanations can contain mistakes.
- External services may have availability or rate-limit restrictions.

Users should independently verify important opportunities before taking financial or other significant actions.

---

## 🚀 Future Enhancements

Planned improvements can include:

- More comprehensive company verification.
- Improved recruiter verification.
- Domain history and reputation analysis.
- Multilingual OCR.
- Improved offer-letter and document analysis.
- Browser extension for quick opportunity checking.
- Mobile application.
- Community-based scam reporting.
- Historical scam-case database.
- Evidence provenance and audit trails.
- Improved risk scoring and explainability.
- More automated testing and evaluation.

---

## 🎓 Academic Project

TrustLens is an **individual academic project developed by Vignesh G**. The project demonstrates the application of web development, artificial intelligence, cybersecurity concepts, OCR, evidence processing, risk assessment, and user-oriented reporting.

Any interviews, observations, user feedback, screenshots, or evaluation results included in an academic submission should represent **actual project evidence** and should not be fabricated.

---

## 📌 Project Summary

---

## 📄 License

This project is developed by **Vignesh G** for educational and project-development purposes.

---

## 👤 Author

### Vignesh G

**TrustLens — Verify Before You Trust.**

© 2026 Vignesh G. All rights reserved.
