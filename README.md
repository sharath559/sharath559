<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/header-light.svg">
  <img src="assets/header-light.svg" width="100%" alt="Sharath Chandra — Senior Software Engineer. Enterprise software. Built for people.">
</picture>

<p align="center">
  <a href="#florida-blue--enterprise-impact">Florida Blue</a> &nbsp; / &nbsp;
  <a href="#selected-work">Selected work</a> &nbsp; / &nbsp;
  <a href="#engineering-toolkit">Engineering toolkit</a> &nbsp; / &nbsp;
  <a href="#credentials--recognition">Credentials &amp; recognition</a> &nbsp; / &nbsp;
  <a href="mailto:sharathy59@gmail.com">Get in touch</a>
</p>

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

## Florida Blue · Enterprise impact

**Provider Platform / MyCare Community · 2018–2019**

- **Simpler provider workflows.** Helped modernize legacy applications into one Florida Blue application. The team's launch announcement describes consolidating patient lookup from **four portals and 10–12 screens into one screen**.
- **One existing login.** Worked on **SAML single sign-on from Availity**, allowing providers to enter the Florida Blue application using their existing sign-in.
- **A healthcare business serving millions.** Florida Blue reported **5M+ members statewide in July 2019**. Company membership context; distinct from portal adoption. [2019 source](https://www.floridablue.com/newsroom/Florida-Blue-Medicare-contract-with-The-Villages).
- **Recognized contribution.** Received a **Florida Blue Medicare Certificate of Appreciation**, dated **September 30, 2019**, for contribution to the Medicare Provider Platform.

[Read the project story](docs/florida-blue-provider-platform.md) &nbsp;·&nbsp; [View the original certificate](assets/florida-blue/certificate-of-appreciation-2019.pdf)

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

### Florida Blue Medicare · September 2019

Recognition for contribution to the **Medicare Provider Platform (MyCare Community)**.

<a href="assets/florida-blue/certificate-of-appreciation-2019.pdf"><img src="assets/florida-blue/certificate-of-appreciation-2019.png" width="680" alt="Florida Blue Medicare Certificate of Appreciation awarded to Sharath Chandra Yakara on September 30, 2019"></a>

[Original certificate PDF](assets/florida-blue/certificate-of-appreciation-2019.pdf) · [Project story](docs/florida-blue-provider-platform.md)

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
