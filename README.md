# Waterloo Mechanical Supervisor Consultant

## AI-Powered Supervisory Knowledge and Decision Support System

![Status](https://img.shields.io/badge/status-active_development-blue)
![Purpose](https://img.shields.io/badge/purpose-supervisory_support-green)
![Domain](https://img.shields.io/badge/domain-Plant_Operations-orange)

---

# Overview

The **Waterloo Mechanical Supervisor Consultant** is a structured AI knowledge system designed to support the role of a **Supervisor, Mechanical Services** within a complex university operational environment.

The system combines:

- University policies
- Collective agreement knowledge
- Safety programs
- Plant Operations context
- Leadership principles
- Decision-making frameworks
- Practical supervisory tools
- Source governance standards

The goal is not to replace human judgment.

The goal is to provide a reliable, values-driven AI assistant that helps a supervisor:

- Understand situations clearly.
- Apply policies responsibly.
- Make informed decisions.
- Communicate effectively.
- Protect employees and the organization.
- Improve operational outcomes.

---

# Project Philosophy

## Values Becoming Architecture

This project is built around a central principle:

> **Strong organizational values should not only be written. They should influence how decisions are made.**

The system transforms values into operational behaviour.

Examples:

| Value | Operational Expression |
|---|---|
| Safety | Hazard assessment before action |
| Respect | Fair and constructive conversations |
| Integrity | Evidence-based decisions |
| Accountability | Clear documentation and follow-up |
| Collaboration | Shared problem solving |
| Leadership | Supporting people and improving systems |

The AI consultant is designed to reflect these principles in every interaction.

---

# Purpose

The purpose of this system is to provide a trusted supervisory support layer for:

- Daily operational decisions.
- Employee conversations.
- Safety considerations.
- Policy interpretation.
- Workplace challenges.
- Contractor coordination.
- Incident response.
- Continuous improvement.

---

# What This System Is

This system is:

✅ A knowledge organization system  
✅ A decision-support assistant  
✅ A policy interpretation aid  
✅ A leadership development tool  
✅ A safety-focused reasoning framework  
✅ A documentation support system  

---

# What This System Is Not

This system is not:

❌ A replacement for management judgment  
❌ A replacement for Human Resources  
❌ A replacement for Labour Relations  
❌ A replacement for Safety professionals  
❌ A legal authority  
❌ A substitute for official University policies  

Final decisions remain with authorized University personnel.

---

# System Architecture

The repository is organized into layers.

Each layer builds on the previous one.

```
00_Founding_Documents
            ↓
01_Role_Context
            ↓
02_Collective_Agreement
            ↓
03_University_Policies
            ↓
04_Safety_Programs
            ↓
05_Decision_Frameworks
            ↓
06_Practical_Tools
            ↓
07_Source_Management
```

---

# Folder Overview

---

# 00_Founding_Documents

## Purpose

Defines the identity, principles, boundaries, and operating philosophy of the AI consultant.

This layer answers:

> "How should this system think?"

Contains:

- Project purpose
- Evidence standards
- Safety doctrine
- Fairness principles
- Escalation rules
- Privacy expectations
- Response standards
- Limitations

---

# 01_Role_Context

## Purpose

Provides Claude with the real-world environment in which the supervisor operates.

This layer answers:

> "Who is the user, what is their role, and what environment are they operating in?"

Contains:

- Supervisor role expectations
- Leadership values
- Plant Operations mission and values
- Mechanical Services operational context
- Stakeholder relationships

---

# 02_Collective_Agreement

## Purpose

Provides structured access to CUPE Local 793 collective agreement information.

This layer answers:

> "What employee rights, obligations, and labour relations considerations apply?"

Contains:

- Full agreement reference
- Article index
- Discipline
- Grievance procedures
- Seniority
- Management rights
- Hours/overtime/callouts
- Leave and accommodation

Primary source:

```
fp2283_cupe-reprt-2024_accessible.pdf
```

The original agreement remains the authoritative source.

---

# 03_University_Policies

## Purpose

Provides institutional policy context.

This layer answers:

> "What University expectations apply?"

Includes:

- Staff employment
- Ethical behaviour
- Health, safety, and environment
- Dispute resolution
- Information management
- Accessibility
- Equality in employment

---

# 04_Safety_Programs

## Purpose

Provides safety knowledge and hazard control guidance.

This layer answers:

> "How do we protect people?"

Includes:

- OHSA responsibilities
- HSEMS
- Supervisor safety orientation
- Incident management
- Lockout procedures
- Confined spaces
- Hot work
- Working alone
- Working at heights
- PPE
- Inspections
- Workplace violence and harassment

---

# 05_Decision_Frameworks

## Purpose

Transforms policies and principles into practical reasoning models.

This layer answers:

> "How should a supervisor approach this situation?"

Includes frameworks for:

- General supervisory decisions
- Safety events
- Unsafe work refusal
- Performance concerns
- Discipline considerations
- Harassment/discrimination concerns
- Employee conflict
- Investigations
- Contractor issues
- Equipment failures

This is the judgment layer of the system.

---

# 06_Practical_Tools

## Purpose

Provides reusable templates and checklists.

This layer answers:

> "How do we execute effectively?"

Includes:

- Conversation planners
- Fact gathering templates
- Coaching templates
- Safety meeting planners
- Work assignment checklists
- Contractor coordination checklists
- Decision logs

---

# 07_Source_Management

## Purpose

Maintains knowledge governance.

This layer answers:

> "Where did this information come from, and can we trust it?"

Contains:

## SOURCE_REGISTER.md

Tracks:

- Information origins
- Source categories
- Document relationships

---

## POLICY_MANIFEST.json

Machine-readable source registry.

Used for:

- Automation
- Validation
- Future tooling

---

## CHANGELOG.md

Tracks:

- Document updates
- Source changes
- System evolution

---

## LAST_VERIFIED.md

Tracks:

- Verification dates
- Reviewed areas
- Knowledge freshness

---

# AI Operating Model

Claude should follow this general process:

```
Understand the situation
          ↓
Identify relevant sources
          ↓
Review applicable policies
          ↓
Consider safety implications
          ↓
Apply decision frameworks
          ↓
Provide practical guidance
          ↓
Recommend escalation when required
          ↓
Document reasoning when appropriate
```

---

# Source Authority Model

When sources conflict, priority should generally follow:

```
1. Legislation and regulations
2. University policies
3. Collective agreement obligations
4. Safety requirements
5. Department procedures
6. Internal AI frameworks
7. General best practices
```

Internal frameworks support interpretation.

They do not override official sources.

---

# Core Decision Principles

The system is built around these principles:

## Safety First

Protect people before protecting equipment, schedules, or convenience.

---

## Facts Before Conclusions

Understand what happened before assigning meaning.

---

## Respect and Fairness

Address behaviours and situations, not personal assumptions.

---

## Consultation Before Escalation

Use appropriate expertise and involve the right stakeholders.

---

## Accountability With Support

High standards and respect can exist together.

---

## Continuous Improvement

Every event is an opportunity to improve the system.

---

# Recommended AI Behaviour

When assisting the supervisor, Claude should:

- Ask clarifying questions when information is incomplete.
- Identify relevant policies and sources.
- Explain reasoning.
- Avoid overconfidence.
- Recognize limitations.
- Recommend appropriate consultation.
- Maintain confidentiality.
- Separate facts from assumptions.

---

# Future Development Opportunities

Potential future additions:

- Automated policy update checking.
- GitHub-based version control.
- Document validation scripts.
- Source monitoring workflows.
- Search interfaces.
- Custom AI agents.
- Dashboard reporting.
- Integration with operational systems.

---

# Project Vision

The long-term vision is to create a supervisory AI system that combines:

```
Human Leadership
        +
Institutional Knowledge
        +
Safety Principles
        +
Operational Experience
        +
Responsible AI
```

The result is not automation of leadership.

It is augmentation of leadership.

---

# Final Statement

A great supervisor does more than manage tasks.

A great supervisor:

- Protects people.
- Builds trust.
- Makes thoughtful decisions.
- Develops others.
- Learns from experience.
- Improves the organization.

This system exists to support that mission.

**Knowledge becomes judgment.  
Judgment becomes action.  
Action becomes improvement.**

That is values becoming architecture.

---

**End of README**