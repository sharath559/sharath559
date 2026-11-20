<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/header-light.svg">
  <img src="assets/header-light.svg" width="100%" alt="Sharath Chandra — Senior Software Engineer. Enterprise software. Built for people.">
</picture>

<p align="center">
  <a href="#florida-blue--enterprise-impact">Featured achievement</a> &nbsp; / &nbsp;
  <a href="#selected-work">Selected work</a> &nbsp; / &nbsp;
  <a href="#engineering-toolkit">Engineering toolkit</a> &nbsp; / &nbsp;
  <a href="#credentials--recognition">Credentials &amp; recognition</a> &nbsp; / &nbsp;
  <a href="mailto:sharathy59@gmail.com">Get in touch</a>
</p>

<a id="florida-blue--enterprise-impact"></a>

## Featured achievement · Florida Blue Provider Portal

**Provider Portal / Medicare Provider Platform · 2018–2019**

<a href="https://raw.githubusercontent.com/sharath559/sharath559/main/assets/florida-blue/provider-portal-launch-announcement-2019.jpg"><img src="https://raw.githubusercontent.com/sharath559/sharath559/main/assets/florida-blue/provider-portal-launch-announcement-2019.jpg" width="100%" alt="Original 2019 Florida Blue Provider Portal launch announcement, including our team photographs, the consolidated provider application, Precision Health Management, and Care Team features"></a>

*Our Provider Portal launch announcement, featuring the team I worked with and the platform we delivered.*

**[Open the complete announcement at original size](https://raw.githubusercontent.com/sharath559/sharath559/main/assets/florida-blue/provider-portal-launch-announcement-2019.jpg)**

### 4 portals. 10–12 screens. One consolidated provider experience.

I contributed to **Florida Blue's Provider Portal modernization**, a major organizational achievement during 2018–2019. The initiative brought together information and workflows for **Florida Blue Commercial, Florida Blue Medicare, and Truli for Health**, helping providers spend less time navigating disconnected applications and find the information needed for patient care.

| Before the Provider Portal | What the team delivered |
| :--- | :--- |
| Patient lookup across **4 separate portals and 10–12 screens** | Relevant patient information consolidated into **one screen** |
| **Dozens of clicks** to locate information | A unified view with integrated search and filtering |
| Clinical, provider-performance, and financial information spread across systems | A consolidated portal connecting those areas with end-to-end workflows |

The historical launch announcement describes **Commercial going live in March 2019** and **Medicare launching October 1, 2019**.

### What made the platform valuable

- **A consolidated provider workspace.** Brought population-health data, clinical and actionable insights, provider performance, financial information, and related workflows into one portal.
- **Commercial and Medicare views.** Let providers choose the relevant business view and access rosters, patient/client information, and finances, with integrated smart search and filtering.
- **Precision Health Management (PHM).** Helped Medicare members aged 65 and older stay on track with health checkpoints. Overdue care, such as a diabetes exam, could create portal tasks for both the member and provider to support outreach and appointment scheduling.
- **Care Team support.** Enabled family members, friends, providers, specialists, and other designated supporters to help members manage care, including scheduling appointments and viewing tasks on their behalf. This supported members who needed help using online health tools.

### My contribution and recognition

- **Legacy modernization.** Helped bring fragmented legacy application workflows into a consolidated Florida Blue application.
- **SAML single sign-on from Availity.** Worked on the federated access flow so providers could enter the Florida Blue application through their existing sign-in.
- **Florida Blue Medicare recognition.** Received a **Certificate of Appreciation on September 30, 2019**, for outstanding and lasting contribution to the **Medicare Provider Platform (MyCare Community)**.

The capabilities above describe the **team's platform**; my contribution is identified separately here. The workflow comparison and product details come from the historical Provider Portal launch announcement.

**Business scale at the time:** Florida Blue reported **more than 5 million members statewide in July 2019**. This is the insurer's membership context; portal-specific adoption and measured financial savings are not documented. [Dated company source](https://www.floridablue.com/newsroom/Florida-Blue-Medicare-contract-with-The-Villages).

[Read the full project story](https://github.com/sharath559/sharath559/blob/main/docs/florida-blue-provider-platform.md)

## Software that earns trust.

I'm **Sharath Chandra**, a Senior Software Engineer with **10+ years of experience** building enterprise applications across healthcare, transportation, and business platforms.

My healthcare experience includes **working on the Florida Blue Provider Platform**, modernizing legacy workflows and integrating SAML single sign-on. My focus is **backend software engineering**: Java, Spring Boot, secure APIs, and dependable data flows. I also work across React and mobile interfaces. I'm expanding into **Claude integrations and agentic AI**, applying the same attention to data contracts, testability, and failure behavior.

<p>
  <a href="https://www.credly.com/badges/1eea3cda-c4cd-4c00-8aba-780c43594aa7/linked_in_profile"><img src="assets/claude-certification.svg" height="32" alt="Claude Certified Developer - Foundations. Verify the Anthropic credential on Credly."></a>
  &nbsp;
  <a href="https://www.kaggle.com/certification/badges/sharath559/108"><img src="assets/kaggle-course-link.svg" height="32" alt="Kaggle 5-Day AI Agents: Intensive Vibe Coding Course completion badge. View the earned badge."></a>
  &nbsp;
  <a href="https://github.com/sharath559/talentscout/actions/workflows/ci.yml"><img src="https://github.com/sharath559/talentscout/actions/workflows/ci.yml/badge.svg" alt="TalentScout Python checks"></a>
</p>

## Selected work

Recent independent projects, separate from my 2018–2019 Florida Blue work.

### [TalentScout](https://github.com/sharath559/talentscout) · Evidence for human reviewers

- Helps a reviewer trace candidate assessments to source quotes and explicit rubric criteria.
- Uses Claude structured outputs, local validation, token-budget checks, and a simulated human approval step to make the review process inspectable.
- **Status:** reproducible offline demo, with 61 tests and 93% local coverage documented in the repository; live model quality remains unmeasured.

[Architecture](https://github.com/sharath559/talentscout/blob/main/docs/ARCHITECTURE.md) · [Demo](https://github.com/sharath559/talentscout/blob/main/docs/demo.gif) · Python / Claude / Pydantic

### [FlowPilot Mobile](https://github.com/sharath559/FlowPilot-Mobile) · Keep collecting records offline

- Helps school and field staff capture student records when connectivity is unreliable, with local saves and a durable queue for cloud sync.
- Gives staff visible retry states, PDF/CSV exports, and organization-scoped access instead of hiding failed uploads.
- **Status:** private pilot; push sync is implemented, with two-way sync and conflict resolution planned.

[Architecture](https://github.com/sharath559/FlowPilot-Mobile/blob/main/docs/ARCHITECTURE.md) · [Sync design](https://github.com/sharath559/FlowPilot-Mobile/blob/main/docs/OFFLINE_SYNC.md) · React Native / TypeScript / SQLite / Supabase

### [DecisionDNA AI](https://github.com/sharath559/decision-dna-ai) · Explain why a decision changed

- Helps reviewers explore changes to healthcare policies, contracts, and rules through synthetic cases and traceable comparisons.
- Combines deterministic comparisons with optional Gemini-generated narratives. Security checks flag prompt-injection and sensitive-data patterns for review; these checks are prototype safeguards.
- **Status:** synthetic-data prototype for exploring decision changes and review workflows.

[Architecture](https://github.com/sharath559/decision-dna-ai/blob/main/docs/ARCHITECTURE.md) · [Security implementation](https://github.com/sharath559/decision-dna-ai/blob/main/src/agents/security_agent.py) · Python / Gemini / Google ADK

### [LaunchGuard AI](https://github.com/sharath559/-sharath-event-talks-app) · Make release gaps visible

- Helps developers review project specifications for authentication, configuration, logging, and deployment gaps.
- Turns transparent heuristic checks into an actionable readiness checklist.
- **Status:** portfolio dashboard with inspectable rules and a runnable implementation.

[Implementation](https://github.com/sharath559/-sharath-event-talks-app/blob/main/app.py) · [Run locally](https://github.com/sharath559/-sharath-event-talks-app#-getting-started) · Python / Flask / JavaScript

**Conversational AI:** [EchoAI](https://github.com/sharath559/echoAI) explores voice interaction with React, Node.js, OpenAI, and ElevenLabs. Conversational AI prototype.

## Engineering toolkit

| Area | Tools and practice |
| :--- | :--- |
| **Backend & APIs** | Java, Spring Boot, Spring Security, Python, Node.js, REST |
| **Data & identity** | PostgreSQL, Oracle, MongoDB, SQLite, Supabase, role-based access, SAML SSO |
| **Delivery & operations** | GitHub Actions, Jenkins, Docker, AWS, Google Cloud, logging and monitoring |
| **Web & mobile** | React, TypeScript, React Native, Expo, interface design |
| **Growing in AI** | Claude Messages API, structured outputs, agent workflows, evaluation, human review |

## Apple ecosystem · Learning focus

I'm interested in bringing my enterprise services experience to customer systems and applications across iOS and macOS. My current exploration areas are:

- **Swift and [SwiftUI](https://developer.apple.com/swiftui/):** native application structure, state, accessibility, and clear interactions.
- **[Apple interface materials](https://developer.apple.com/design/human-interface-guidelines/materials):** platform conventions and readable, accessible interfaces.
- **[Safari web extensions](https://developer.apple.com/documentation/safariservices/safari-web-extensions):** browser workflows using web technologies and app integration.
- **[Foundation Models](https://developer.apple.com/documentation/foundationmodels):** structured generation, tool calling, model availability, safety, and evaluation.

These are learning interests. My demonstrated mobile work uses React Native; my AI portfolio uses Claude and Gemini.

## How I work

- **Start with the person.** Make important states, errors, and next steps understandable.
- **Make boundaries explicit.** Define data contracts, permissions, and failure behavior early.
- **Show the evidence.** Connect technical claims to source code, tests, and documented tradeoffs.
- **Design for reality.** Account for unreliable networks, incomplete inputs, cost, and operational limits.

## Credentials & recognition

### Florida Blue Medicare · Certificate of Appreciation

**Awarded to Sharath Chandra Yakara · September 30, 2019**

Recognized for outstanding and lasting contribution to the **FloridaBlue Medicare Provider Platform (MyCare Community)**.

<a href="https://raw.githubusercontent.com/sharath559/sharath559/main/assets/florida-blue/certificate-of-appreciation-2019.png"><img src="https://raw.githubusercontent.com/sharath559/sharath559/main/assets/florida-blue/certificate-of-appreciation-2019.png" width="100%" alt="Full-size Florida Blue Medicare Certificate of Appreciation presented to Sharath Chandra Yakara on September 30, 2019 for contribution to the Medicare Provider Platform"></a>

**[Enlarge certificate image](https://raw.githubusercontent.com/sharath559/sharath559/main/assets/florida-blue/certificate-of-appreciation-2019.png)** &nbsp;·&nbsp; **[Open original PDF](https://github.com/sharath559/sharath559/blob/main/assets/florida-blue/certificate-of-appreciation-2019.pdf)**

### Recent AI credentials

<table>
  <tr>
    <td width="150" align="center" valign="middle">
      <a href="https://www.credly.com/badges/1eea3cda-c4cd-4c00-8aba-780c43594aa7/linked_in_profile"><img src="assets/claude-certified-developer-foundations.png" width="120" alt="Anthropic Claude Certified Developer - Foundations badge"></a>
    </td>
    <td valign="middle">
      <p><sub>DEVELOPER CERTIFICATION</sub></p>
      <strong>Claude Certified Developer - Foundations</strong>
      <p>Issued by <strong>Anthropic</strong> to Sharath Chandra Yakara.</p>
      <a href="https://www.credly.com/badges/1eea3cda-c4cd-4c00-8aba-780c43594aa7/linked_in_profile">Verify the credential on Credly →</a>
    </td>
  </tr>
  <tr>
    <td width="150" align="center" valign="middle">
      <a href="https://www.kaggle.com/certification/badges/sharath559/108"><img src="assets/kaggle-ai-agents-completion.svg" width="96" alt="Official Kaggle 5-Day AI Agents: Intensive Vibe Coding Course completion badge"></a>
    </td>
    <td valign="middle">
      <p><sub>COURSE COMPLETION BADGE</sub></p>
      <strong>5-Day AI Agents: Intensive Vibe Coding Course</strong>
      <p>Kaggle · With Google · Completed July 30, 2026.</p>
      <p>Hands-on learning in agent workflows, tools, memory, security, evaluation, and deployment, with assignments and a capstone project.</p>
      <a href="https://www.kaggle.com/certification/badges/sharath559/108">View the earned badge →</a> &nbsp;·&nbsp; <a href="https://www.kaggle.com/learn-guide/5-day-agents-vibecoding">Course guide</a>
    </td>
  </tr>
</table>

## Let's build something useful.

Open to **backend and senior software engineering** opportunities. Especially interested in API platforms, reliable services, and teams bringing AI capabilities into useful products.

**[Email me](mailto:sharathy59@gmail.com)** &nbsp; / &nbsp; **[Explore my repositories](https://github.com/sharath559?tab=repositories)** &nbsp; / &nbsp; **[Kaggle](https://www.kaggle.com/sharath559)**

<sub>Portfolio projects are presented with their implementation status and limitations. Production adoption, revenue, and savings are not claimed for these projects. Each repository contains the details.</sub>
