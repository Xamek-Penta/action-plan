# Engineering Department Q1-Q2 2026 Action Plan

## Comprehensive 4-Month Strategic Roadmap

**Planning Period:** October 2025 - February 2026 (15 weeks)  
**Department:** Engineering  
**Document Version:** 1.0  
**Last Updated:** October 9, 2025  
**Status:** 🎯 Ready for Execution

---

## Table of Contents

- [Engineering Department Q1-Q2 2026 Action Plan](#engineering-department-q1-q2-2026-action-plan)
  - [Comprehensive 4-Month Strategic Roadmap](#comprehensive-4-month-strategic-roadmap)
  - [Table of Contents](#table-of-contents)
  - [Executive Summary](#executive-summary)
    - [Key Milestones](#key-milestones)
  - [Strategic Objectives](#strategic-objectives)
    - [Primary Goals](#primary-goals)
  - [Team Structure \& Roles](#team-structure--roles)
    - [Engineering Team (10 people)](#engineering-team-10-people)
    - [Products Team (4 people)](#products-team-4-people)
    - [Delivery Team (1 person)](#delivery-team-1-person)
  - [Parallel Workstreams](#parallel-workstreams)
    - [Workstream 1: Plugin Handover (Weeks 1-15)](#workstream-1-plugin-handover-weeks-1-15)
      - [Key Deliverables](#key-deliverables)
    - [Workstream 2: IaC Deployment (Weeks 1-12)](#workstream-2-iac-deployment-weeks-1-12)
      - [Key Deliverables](#key-deliverables-1)
    - [Workstream 3: Automation \& Tooling (Ongoing)](#workstream-3-automation--tooling-ongoing)
      - [Key Deliverables](#key-deliverables-2)
  - [Workstream 1: Plugin Handover - Detailed Plan](#workstream-1-plugin-handover---detailed-plan)
    - [Workstream 1 Overview](#workstream-1-overview)
    - [Plugin List](#plugin-list)
    - [Weeks 1-2: Preparation Phase](#weeks-1-2-preparation-phase)
      - [Focus](#focus)
      - [Tasks](#tasks)
      - [Deliverables](#deliverables)
    - [Batch Cycle Pattern (2 weeks per batch)](#batch-cycle-pattern-2-weeks-per-batch)
      - [Week 1 (Implementation)](#week-1-implementation)
      - [Focus](#focus-1)
      - [Tasks](#tasks-1)
      - [Week 2 (Testing \& QA)](#week-2-testing--qa)
      - [Focus](#focus-2)
      - [Tasks](#tasks-2)
      - [Deliverables per Batch](#deliverables-per-batch)
    - [Week 15: Final Handover](#week-15-final-handover)
      - [Focus](#focus-3)
      - [Tasks](#tasks-3)
      - [Deliverables](#deliverables-1)
    - [Workstream 1 Task Estimates](#workstream-1-task-estimates)
  - [Workstream 2: IaC Deployment - Detailed Plan](#workstream-2-iac-deployment---detailed-plan)
    - [Workstream 2 Overview](#workstream-2-overview)
    - [Week-by-Week Breakdown](#week-by-week-breakdown)
      - [Week 1: Foundation Setup](#week-1-foundation-setup)
      - [Focus](#focus-4)
      - [Tasks](#tasks-4)
      - [Deliverables](#deliverables-2)
      - [Week 2: GeoServer \& Firewall](#week-2-geoserver--firewall)
      - [Focus](#focus-5)
      - [Tasks](#tasks-5)
      - [Deliverables](#deliverables-3)
      - [Week 3: PostgreSQL \& Security](#week-3-postgresql--security)
      - [Focus](#focus-6)
      - [Tasks](#tasks-6)
      - [Deliverables](#deliverables-4)
      - [Week 4: Keycloak \& Docker Swarm](#week-4-keycloak--docker-swarm)
      - [Focus](#focus-7)
      - [Tasks](#tasks-7)
      - [Deliverables](#deliverables-5)
      - [Week 5: Application Services \& Reverse Proxy](#week-5-application-services--reverse-proxy)
      - [Focus](#focus-8)
      - [Tasks](#tasks-8)
      - [Deliverables](#deliverables-6)
      - [Week 6: GeoServer Layers](#week-6-geoserver-layers)
      - [Focus](#focus-9)
      - [Tasks](#tasks-9)
      - [Deliverables](#deliverables-7)
      - [Week 7: Keycloak Configuration](#week-7-keycloak-configuration)
      - [Focus](#focus-10)
      - [Tasks](#tasks-10)
      - [Deliverables](#deliverables-8)
      - [Week 8: Monitoring \& Logging](#week-8-monitoring--logging)
      - [Focus](#focus-11)
      - [Tasks](#tasks-11)
      - [Deliverables](#deliverables-9)
      - [Week 9: Testing \& Validation](#week-9-testing--validation)
      - [Focus](#focus-12)
      - [Tasks](#tasks-12)
      - [Deliverables](#deliverables-10)
      - [Week 10: Master Playbook \& CI/CD](#week-10-master-playbook--cicd)
      - [Focus](#focus-13)
      - [Tasks](#tasks-13)
      - [Deliverables](#deliverables-11)
      - [Week 11: DR Testing \& Documentation](#week-11-dr-testing--documentation)
      - [Focus](#focus-14)
      - [Tasks](#tasks-14)
      - [Deliverables](#deliverables-12)
      - [Week 12: Final Integration \& Handover](#week-12-final-integration--handover)
      - [Focus](#focus-15)
      - [Tasks](#tasks-15)
      - [Deliverables](#deliverables-13)
    - [IaC Post-Week 12: Support Mode](#iac-post-week-12-support-mode)
      - [Weeks 13-15](#weeks-13-15)
    - [Workstream 2 Task Estimates](#workstream-2-task-estimates)
    - [Implementation Specification](#implementation-specification)
  - [Workstream 3: Automation \& Tooling - Detailed Plan](#workstream-3-automation--tooling---detailed-plan)
    - [Workstream 3 Overview](#workstream-3-overview)
    - [Phase 1: Foundation (Weeks 1-2)](#phase-1-foundation-weeks-1-2)
      - [Week 1: Architecture \& Design](#week-1-architecture--design)
      - [Focus](#focus-16)
      - [Tasks](#tasks-16)
      - [Deliverables](#deliverables-14)
      - [Week 2: Implementation \& Integration](#week-2-implementation--integration)
      - [Focus](#focus-17)
      - [Tasks](#tasks-17)
      - [Deliverables](#deliverables-15)
    - [Phase 2: Continuous Support (Weeks 3-15)](#phase-2-continuous-support-weeks-3-15)
      - [Ongoing Activities](#ongoing-activities)
      - [Tasks](#tasks-18)
      - [Activities](#activities)
      - [Deliverables](#deliverables-16)
    - [Workstream 3 Task Estimates](#workstream-3-task-estimates)
    - [Pipeline Specification](#pipeline-specification)
  - [Appendix: Detailed Specifications](#appendix-detailed-specifications)
  - [IaC Deployment Implementation Specification](#iac-deployment-implementation-specification)
    - [Strategic Goal](#strategic-goal)
    - [Modular Ansible Roles](#modular-ansible-roles)
    - [Repository Structure](#repository-structure)
    - [GitLab CI/CD Integration](#gitlab-cicd-integration)
      - [Pipeline Stages](#pipeline-stages)
      - [Core CI Jobs](#core-ci-jobs)
      - [Governance Policies](#governance-policies)
    - [n8n Automation Hooks](#n8n-automation-hooks)
    - [ADR Framework](#adr-framework)
      - [Storage](#storage)
      - [Template](#template)
      - [Enforcement](#enforcement)
    - [Deployment Verification](#deployment-verification)
      - [Central verify playbook](#central-verify-playbook)
      - [Role-level assertions](#role-level-assertions)
    - [SE Deployment Workflow](#se-deployment-workflow)
      - [Step 1: Pre-flight](#step-1-pre-flight)
      - [Step 2: Bootstrap](#step-2-bootstrap)
      - [Step 3: Deploy](#step-3-deploy)
      - [Step 4: Verify](#step-4-verify)
      - [Step 5: Handover](#step-5-handover)
    - [Rollback Procedures](#rollback-procedures)
      - [Tag-based rollback](#tag-based-rollback)
      - [Backup-based rollback](#backup-based-rollback)
    - [Monitoring \& Alerting](#monitoring--alerting)
      - [Metrics collected](#metrics-collected)
      - [Alert thresholds](#alert-thresholds)
    - [Security Hardening](#security-hardening)
      - [Applied by `security` role](#applied-by-security-role)
    - [Backup Strategy](#backup-strategy)
      - [Backup schedule](#backup-schedule)
      - [Retention policy](#retention-policy)
      - [Backup verification](#backup-verification)
    - [Performance Testing with JMeter](#performance-testing-with-jmeter)
      - [Test Plans](#test-plans)
      - [Test Scenarios](#test-scenarios)
      - [Acceptance Criteria](#acceptance-criteria)
    - [Documentation Deliverables](#documentation-deliverables)
      - [For Solutions Engineers](#for-solutions-engineers)
      - [For Operations](#for-operations)
      - [For Developers](#for-developers)
  - [GitLab Automated Delivery Pipeline Specification](#gitlab-automated-delivery-pipeline-specification)
    - [GitLab Board Columns](#gitlab-board-columns)
    - [Roles \& Responsibilities](#roles--responsibilities)
    - [Step 1: PO Creates User Story Document](#step-1-po-creates-user-story-document)
      - [n8n Actions](#n8n-actions)
    - [Step 2: UX Designer Creates \& Updates Figma Design](#step-2-ux-designer-creates--updates-figma-design)
      - [n8n Actions](#n8n-actions-1)
    - [Step 3: Developer Implementation](#step-3-developer-implementation)
      - [n8n Actions](#n8n-actions-2)
    - [Step 4: QA Testing](#step-4-qa-testing)
      - [QA Workflow](#qa-workflow)
      - [n8n Actions](#n8n-actions-3)
    - [Step 5: Release \& Deployment](#step-5-release--deployment)
      - [Release Workflow](#release-workflow)
      - [n8n Actions](#n8n-actions-4)
    - [Reusable Workflows](#reusable-workflows)
      - [`pr_review_cycle` (n8n sub-workflow)](#pr_review_cycle-n8n-sub-workflow)
      - [`update_kb` (n8n sub-workflow)](#update_kb-n8n-sub-workflow)
    - [Validation Scripts (by Marawan)](#validation-scripts-by-marawan)

---

## Executive Summary

This comprehensive action plan coordinates three major engineering initiatives over a 15-week period (4 months):

**Workstream 1: Plugin Handover (15 weeks)**  
Transfer 30 plugins from Engineering to Products Team with complete refactoring, Chakra UI implementation, and comprehensive documentation. Runs for the full 15-week duration.

**Workstream 2: Infrastructure-as-Code (12 weeks)**  
Build production-ready IaC deployment automation enabling Solutions Engineers to deploy full stack infrastructure with a single command. Completes by Week 12, then transitions to support mode.

**Workstream 3: Automation & Tooling (ongoing)**  
Develop automation scripts, CI/CD pipelines, and governance frameworks to support both workstreams. Continuous throughout the 15 weeks.

**Total Team Size:** 13 people  
**Total Duration:** 15 weeks (~4 months)  
**Total Estimated Hours:** 2,800-3,000 hours

### Key Milestones

- Week 2: Automation framework & CI/CD pipelines operational
- Week 12: IaC deployment complete
- Week 15: All 30 plugins delivered

---

## Strategic Objectives

### Primary Goals

1. **Enable Self-Service Deployment**

   - Solutions Engineers can deploy full infrastructure independently
   - Deployment time: <45 minutes from scratch
   - Zero-touch automation with governance built-in

2. **Modernize Plugin Architecture**

   - All 30 plugins refactored with Chakra UI
   - Complete ownership transfer to Products Team
   - Comprehensive documentation and testing

3. **Automation & Tooling (Ongoing)**
   - Automation framework for plugin delivery
   - CI/CD pipelines for workstreams 1 & 2
   - Governance frameworks for code review & compliance
   - Automated compliance checking
   - Performance testing infrastructure

---

## Team Structure & Roles

### Engineering Team (10 people)

| Name        | Role             |
| ----------- | ---------------- |
| **Xamek**   | Chief Architect  |
| **Mounir**  | Senior Developer |
| **Alaa**    | DevOps Engineer  |
| **Marawan** | AI Developer     |
| **Omar**    | Developer        |
| **Basem**   | Developer        |
| **Khadra**  | Developer        |
| **Hassan**  | Developer        |
| **Samy**    | Developer        |

### Products Team (4 people)

| Name            | Role              |
| --------------- | ----------------- |
| **Amr**         | CTO               |
| **Hajar**       | Product Owner     |
| **Menna**       | UX Designer       |
| **QA Engineer** | QA Engineer (TBD) |

### Delivery Team (1 person)

| Name         | Role               |
| ------------ | ------------------ |
| **Meslmany** | Solutions Engineer |

---

## Parallel Workstreams

### Workstream 1: Plugin Handover (Weeks 1-15)

**Objective:** Transfer 30 plugins to Products Team

**Timeline:** 15 weeks (2-week cycles per batch)

- Weeks 1-2: Preparation
- Weeks 3-14: 6 batches × 2 weeks each
- Week 15: Final handover

**Team:** 5 developers + Hajar + Menna + Mounir + Xamek + Amr + QA

#### Key Deliverables

- 30 refactored plugins with Chakra UI
- Complete documentation (user stories, technical docs)
- Figma designs for all UIs

### Workstream 2: IaC Deployment (Weeks 1-12)

**Objective:** Build production-ready infrastructure automation

**Timeline:** 12 weeks

- Weeks 1-2: Foundation & planning
- Weeks 3-10: Role development & testing
- Weeks 11-12: Integration & documentation

**Team:** Alaa + Meslmany + Marawan + Xamek

#### Key Deliverables

- 17 Ansible roles
- GitLab CI/CD pipeline
- JMeter performance tests
- Complete documentation

### Workstream 3: Automation & Tooling (Ongoing)

**Objective:** Support both workstreams with automation

**Timeline:** Weeks 1-12 (ongoing)

**Team:** Marawan

#### Key Deliverables

- Paved roads compliance scripts
- User story coverage automation
- Code review automation
- Figma compliance checking
- CI/CD pipeline integration

---

## Workstream 1: Plugin Handover - Detailed Plan

### Workstream 1 Overview

**Duration:** 15 weeks  
**Team:** 5 Developers (Omar, Basem, Khadra, Hassan, Samy), Hajar (Product Owner), Menna (UX Designer), Mounir (Code Reviews), Xamek (Technical Reviews), Amr (Code Reviews), QA Engineer, Meslmany (Story Reviews)  
**Objective:** Transfer 30 plugins to Products Team with Chakra UI refactoring

### Plugin List

| Developer  | Batch 1 (Wk 3-4) | Batch 2 (Wk 5-6) | Batch 3 (Wk 7-8) | Batch 4 (Wk 9-10) | Batch 5 (Wk 11-12) | Batch 6 (Wk 13-14) |
| ---------- | ---------------- | ---------------- | ---------------- | ----------------- | ------------------ | ------------------ |
| **Omar**   | Bookmarks        | Measurement      | Find Nearest     | Editing           | Data Inspector     | Go To Point        |
| **Basem**  | Identify         | Feature Selector | Charts           | Cards             | Alarms             | Smart Indoor       |
| **Khadra** | Advanced Search  | Sketching        | Reporting        | More Info         | TOC                | Classification     |
| **Hassan** | Driller          | Timeline         | Export PDF       | Geometry          | Legend             | Data Review        |
| **Samy**   | Spatial Search   | Fulltext Search  | Simple Import    | Simple Search     | Territory Manager  | Inbox              |

### Weeks 1-2: Preparation Phase

#### Focus

Standards, tools, and example plugin

#### Tasks

| Task                    | Role | Estimate | Calculation     |
| ----------------------- | ---- | -------- | --------------- |
| **Hajar**               |      |          |                 |
| User Story Creation     |      | 60h      | 15 plugins × 4h |
| **Meslmany**            |      |          |                 |
| User Story Review       |      | 15h      | 15 plugins × 1h |
| **Xamek**               |      |          |                 |
| User Story Review       |      | 15h      | 15 plugins × 1h |
| **Mounir**              |      |          |                 |
| User Story Review       |      | 15h      | 15 plugins × 1h |
| Plugin Review Checklist |      | 2h       | One-time task   |
| Example Plugin          |      | 14h      | One-time task   |
| Figma Design Review     |      | 5h       | 5 plugins × 1h  |
| **Menna**               |      |          |                 |
| Figma Baseline          |      | 8h       | One-time task   |
| Design System Docs      |      | 6h       | One-time task   |
| Figma Designs           |      | 40h      | 5 plugins × 8h  |
| **All Developers**      |      |          |                 |
| Chakra Theme Setup      |      | 8h       | One-time task   |
| Linting & CI Setup      |      | 8h       | One-time task   |

#### Deliverables

- ✅ Example plugin with Chakra UI, Penta Grid, Penta Form Builder
- ✅ Plugin review checklist
- ✅ Figma design system
- ✅ User stories for first 15 plugins (Batches 1-3)
- ✅ Figma designs for Batch 1 (5 plugins)
- ✅ Development environment ready

---

### Batch Cycle Pattern (2 weeks per batch)

Each batch follows the same pattern:

#### Week 1 (Implementation)

#### Focus

Development and design for next batch

#### Tasks

| Task                                  | Role | Estimate | Calculation          |
| ------------------------------------- | ---- | -------- | -------------------- |
| **Hajar**                             |      |          |                      |
| User Story Creation (next batch)      |      | 20h      | 5 plugins × 4h       |
| **Meslmany**                          |      |          |                      |
| User Story Review (next batch)        |      | 5h       | 5 plugins × 1h       |
| **Xamek**                             |      |          |                      |
| User Story Review (next batch)        |      | 5h       | 5 plugins × 1h       |
| **Mounir**                            |      |          |                      |
| User Story Review (next batch)        |      | 5h       | 5 plugins × 1h       |
| Figma Design Review (next batch)      |      | 5h       | 5 plugins × 1h       |
| Code Review (current batch)           |      | 5h       | 5 plugins × 1h       |
| **Menna**                             |      |          |                      |
| Figma Designs (next batch)            |      | 40h      | 5 plugins × 8h       |
| **5 Developers**                      |      |          |                      |
| Plugin Implementation (current batch) |      | 210h     | 5 plugins × 42h each |
| **Amr**                               |      |          |                      |
| Code Review (current batch)           |      | 5h       | 5 plugins × 1h       |

#### Week 2 (Testing & QA)

#### Focus

Bug fixing and quality assurance

#### Tasks

| Task             | Role | Estimate | Calculation          |
| ---------------- | ---- | -------- | -------------------- |
| **QA Engineer**  |      |          |                      |
| Plugin Testing   |      | 30h      | 5 plugins × 6h       |
| **5 Developers** |      |          |                      |
| Bug Fixing       |      | 130h     | 5 plugins × 26h each |

#### Deliverables per Batch

- ✅ 5 plugins refactored with Chakra UI
- ✅ 5 Figma designs
- ✅ User stories documented
- ✅ Code reviewed and approved by Mounir & Amr
- ✅ QA sign-off

---

### Week 15: Final Handover

#### Focus

Documentation and knowledge transfer

#### Tasks

| Task                        | Role | Estimate | Calculation      |
| --------------------------- | ---- | -------- | ---------------- |
| **All Team**                |      |          |                  |
| Compile handover materials  |      | 50h      | Combined effort  |
| Knowledge transfer sessions |      | Included | Part of handover |
| Sign-off and celebration    |      | Included | Part of handover |
| **Mounir + Xamek**          |      |          |                  |
| Final documentation review  |      | Included | Part of handover |
| **Products Team**           |      |          |                  |
| Acceptance testing          |      | Included | Part of handover |

#### Deliverables

- ✅ 30 plugins delivered
- ✅ Complete technical documentation
- ✅ All Figma designs
- ✅ Handover checklist completed
- ✅ Products Team sign-off

---

### Workstream 1 Task Estimates

| Role            | Task                           | Estimate |
| --------------- | ------------------------------ | -------- |
| **Hajar**       | Create user story              | 4h       |
| **Meslmany**    | Review user story              | 1h       |
| **Xamek**       | Review user story              | 1h       |
| **Mounir**      | Review user story              | 1h       |
|                 | Define plugin review checklist | 2h       |
|                 | Create example plugin          | 14h      |
|                 | Review Figma design            | 1h       |
|                 | Code review                    | 1h       |
| **Amr**         | Code review                    | 1h       |
| **Menna**       | Establish Figma baseline       | 8h       |
|                 | Create design system docs      | 6h       |
|                 | Create Figma design            | 8h       |
| **Developer**   | Setup Chakra theme             | 8h       |
|                 | Setup linting & CI             | 8h       |
|                 | Implement plugin               | 42h      |
|                 | Bug fixing                     | 26h      |
| **QA Engineer** | Test plugin                    | 6h       |

---

## Workstream 2: IaC Deployment - Detailed Plan

### Workstream 2 Overview

**Duration:** 12 weeks  
**Team:** Alaa (DevOps lead), Marawan (AI automation), Meslmany (validation)  
**Objective:** Production-ready infrastructure automation

### Week-by-Week Breakdown

#### Week 1: Foundation Setup

#### Focus

Repository structure and planning

#### Tasks

| Task                                                       | Role | Estimate | Calculation    |
| ---------------------------------------------------------- | ---- | -------- | -------------- |
| **Alaa**                                                   |      |          |                |
| Repository scaffold & Ansible structure & bootstrap script |      | 23h      | Combined tasks |
| **Xamek**                                                  |      |          |                |
| ADR template and documentation                             |      | 3h       | One-time task  |
| **Marawan**                                                |      |          |                |
| Automation helper scripts                                  |      | 4h       | One-time task  |
| **Meslmany**                                               |      |          |                |
| Bootstrap validation                                       |      | 3h       | One-time task  |

#### Deliverables

- ✅ GitLab repository: `iac-deployment-automation`
- ✅ Complete directory structure
- ✅ Bootstrap script tested on Ubuntu 22.04
- ✅ Environment strategy documented
- ✅ ADR-000 written

---

#### Week 2: GeoServer & Firewall

#### Focus

First infrastructure roles

#### Tasks

| Task                                           | Role | Estimate | Calculation   |
| ---------------------------------------------- | ---- | -------- | ------------- |
| **Alaa**                                       |      |          |               |
| GeoServer role + Firewall role & configuration |      | 18h      | 12h + 6h      |
| **Marawan**                                    |      |          |               |
| Automated testing scripts                      |      | 13h      | One-time task |
| **Meslmany**                                   |      |          |               |
| Deployment validation                          |      | 4h       | One-time task |

#### Deliverables

- ✅ `roles/geoserver/` (127 lines of Ansible YAML)
- ✅ `roles/firewall/` (68 lines of Ansible YAML)
- ✅ ADR-001 written
- ✅ Installation guide created

---

#### Week 3: PostgreSQL & Security

#### Focus

Database and security hardening

#### Tasks

| Task                                                                                                          | Role | Estimate | Calculation        |
| ------------------------------------------------------------------------------------------------------------- | ---- | -------- | ------------------ |
| **Alaa**                                                                                                      |      |          |                    |
| PostgreSQL & PostGIS setup + DB config role + Security hardening & CIS benchmarks + Backup automation scripts |      | 30h      | 10h + 4h + 8h + 8h |
| **Meslmany**                                                                                                  |      |          |                    |
| DB validation and backup testing                                                                              |      | 4h       | One-time task      |

#### Deliverables

- ✅ `roles/postgres_postgis/` (156 lines)
- ✅ `roles/db_config/` (89 lines - schemas, users, initial SQL)
- ✅ `roles/security_hardening/` (203 lines)
- ✅ Backup script: `pg_backup.sh`
- ✅ ADR-002 written

---

#### Week 4: Keycloak & Docker Swarm

#### Focus

Identity management and container orchestration

#### Tasks

| Task                                                         | Role | Estimate | Calculation   |
| ------------------------------------------------------------ | ---- | -------- | ------------- |
| **Alaa**                                                     |      |          |               |
| Docker & Swarm configuration + Keycloak installation & setup |      | 22h      | 12h + 10h     |
| **Marawan**                                                  |      |          |               |
| Container health check scripts                               |      | 3h       | One-time task |
| **Meslmany**                                                 |      |          |               |
| Keycloak and Docker validation                               |      | 4h       | One-time task |

#### Deliverables

- ✅ `roles/keycloak_install/` (134 lines)
- ✅ `roles/docker_swarm/` (98 lines)
- ✅ Docker Compose file for Keycloak
- ✅ ADR-003 written

---

#### Week 5: Application Services & Reverse Proxy

#### Focus

App containers and SSL/TLS

#### Tasks

| Task                                                   | Role | Estimate | Calculation   |
| ------------------------------------------------------ | ---- | -------- | ------------- |
| **Alaa**                                               |      |          |               |
| Application containers + Nginx & SSL/TLS configuration |      | 18h      | 8h + 10h      |
| **Marawan**                                            |      |          |               |
| Config validation scripts                              |      | 5h       | One-time task |
| **Meslmany**                                           |      |          |               |
| SSL validation and config testing                      |      | 5h       | One-time task |

#### Deliverables

- ✅ `roles/docker_containers/` (187 lines)
- ✅ `roles/db_config/` (112 lines)
- ✅ `roles/reverse_proxy/` (156 lines)
- ✅ Nginx config templates
- ✅ SQL initialization scripts
- ✅ ADR-004 written

---

#### Week 6: GeoServer Layers

#### Focus

Spatial data management

#### Tasks

| Task                                         | Role | Estimate | Calculation   |
| -------------------------------------------- | ---- | -------- | ------------- |
| **Alaa**                                     |      |          |               |
| GeoServer layers & REST API                  |      | 13h      | One-time task |
| **Marawan**                                  |      |          |               |
| Layer validation scripts                     |      | 4h       | One-time task |
| **Meslmany**                                 |      |          |               |
| Sample data preparation and layer validation |      | 5h       | One-time task |

#### Deliverables

- ✅ `roles/geoserver_layers/` (143 lines)
- ✅ Sample data (3 vector layers, 2 raster layers)
- ✅ SLD styles
- ✅ Validation script: `validate_layers.py`
- ✅ ADR-005 written

---

#### Week 7: Keycloak Configuration

#### Focus

Identity and access management

#### Tasks

| Task                               | Role | Estimate | Calculation   |
| ---------------------------------- | ---- | -------- | ------------- |
| **Alaa**                           |      |          |               |
| Keycloak realm & SSO configuration |      | 11h      | One-time task |
| **Marawan**                        |      |          |               |
| User provisioning automation       |      | 4h       | One-time task |
| **Meslmany**                       |      |          |               |
| User templates and login testing   |      | 4h       | One-time task |

#### Deliverables

- ✅ `roles/keycloak_config/` (178 lines)
- ✅ Realm export: `gis_platform_realm.json`
- ✅ User templates
- ✅ Provisioning script: `provision_users.py`
- ✅ ADR-006 written

---

#### Week 8: Monitoring & Logging

#### Focus

Observability and ADR review

#### Tasks

| Task                                           | Role | Estimate | Calculation   |
| ---------------------------------------------- | ---- | -------- | ------------- |
| **Alaa**                                       |      |          |               |
| Monitoring stack + ADR logger & CI integration |      | 21h      | 16h + 5h      |
| **Marawan**                                    |      |          |               |
| ADR review and finalization                    |      | 6h       | One-time task |
| **Meslmany**                                   |      |          |               |
| Dashboard review and alert testing             |      | 4h       | One-time task |

#### Deliverables

- ✅ `roles/monitoring/` (234 lines)
- ✅ `roles/logging/` (156 lines)
- ✅ `roles/adr_logger/` (89 lines)
- ✅ 8 Grafana dashboards
- ✅ 12 alert rules
- ✅ ADR-007 written
- ✅ All ADRs (000-007) reviewed and approved

---

#### Week 9: Testing & Validation

#### Focus

Comprehensive testing and restore procedures

#### Tasks

| Task                                                              | Role | Estimate | Calculation   |
| ----------------------------------------------------------------- | ---- | -------- | ------------- |
| **Alaa**                                                          |      |          |               |
| Restore procedures & validation + Molecule tests & CI integration |      | 12h      | 6h + 6h       |
| **Marawan**                                                       |      |          |               |
| Test automation scripts                                           |      | 5h       | One-time task |
| **Meslmany**                                                      |      |          |               |
| Test case definition and DR testing                               |      | 5h       | One-time task |

#### Deliverables

- ✅ `playbooks/restore.yml` (restore procedures)
- ✅ `playbooks/verify.yml` (156 lines)
- ✅ 189 Molecule tests (84% coverage)
- ✅ Restore validation scripts
- ✅ ADR-008 written

---

#### Week 10: Master Playbook & CI/CD

#### Focus

Deployment automation and pipeline

#### Tasks

| Task                                               | Role | Estimate | Calculation   |
| -------------------------------------------------- | ---- | -------- | ------------- |
| **Alaa**                                           |      |          |               |
| Master playbooks + CI/CD pipeline & approval gates |      | 19h      | 12h + 7h      |
| **Marawan**                                        |      |          |               |
| Deployment validation scripts                      |      | 5h       | One-time task |
| **Meslmany**                                       |      |          |               |
| Staging deployment testing                         |      | 5h       | One-time task |

#### Deliverables

- ✅ `playbooks/deploy.yml` (234 lines)
- ✅ `playbooks/rollback.yml` (156 lines)
- ✅ Environment configs for dev/staging/prod
- ✅ `.gitlab-ci.yml` (187 lines)
- ✅ Deployment scripts
- ✅ ADR-009 written

---

#### Week 11: DR Testing & Documentation

#### Focus

Disaster recovery and comprehensive docs

#### Tasks

| Task                                                       | Role | Estimate | Calculation   |
| ---------------------------------------------------------- | ---- | -------- | ------------- |
| **Alaa**                                                   |      |          |               |
| n8n webhooks + JMeter & performance tests + Security audit |      | 18h      | 6h + 10h + 2h |
| **Marawan**                                                |      |          |               |
| Operator documentation                                     |      | 6h       | One-time task |
| **Meslmany**                                               |      |          |               |
| User documentation                                         |      | 6h       | One-time task |

#### Deliverables

- ✅ 5 n8n workflows
- ✅ DR procedures (89 pages)
- ✅ Performance report
- ✅ Security audit report
- ✅ User guide (42 pages)
- ✅ Operator runbook (67 pages)
- ✅ Troubleshooting guide (34 pages)
- ✅ ADR-010 written

---

#### Week 12: Final Integration & Handover

#### Focus

Production readiness and SE handover

#### Tasks

| Task                      | Role | Estimate | Calculation   |
| ------------------------- | ---- | -------- | ------------- |
| **Alaa**                  |      |          |               |
| README, guides & diagrams |      | 10h      | One-time task |
| E2E testing               |      | 6h       | One-time task |
| **Marawan**               |      |          |               |
| Final polish & packaging  |      | 5h       | One-time task |
| **Meslmany**              |      |          |               |
| SE acceptance testing     |      | 6h       | One-time task |

#### Deliverables

- ✅ Complete README with quick-start
- ✅ Installation checklist
- ✅ 8 architecture diagrams
- ✅ Final project report
- ✅ Retrospective notes
- ✅ Handover document
- ✅ **SE ACCEPTANCE SIGN-OFF**
- ✅ **🎉 PROJECT COMPLETE**

---

### IaC Post-Week 12: Support Mode

#### Weeks 13-15

- Alaa: 8h/week support and maintenance
- Deploy to 3+ client sites
- Gather feedback and iterate
- Minor enhancements and bug fixes
- Support plugin team as needed

---

### Workstream 2 Task Estimates

| Role                   | Task                                         | Estimate |
| ---------------------- | -------------------------------------------- | -------- |
| **Alaa**               | Repository setup & Ansible structure         | 23h      |
|                        | GeoServer role (Java, Tomcat, GeoServer)     | 12h      |
|                        | Firewall role & configuration                | 6h       |
|                        | PostgreSQL & PostGIS setup                   | 10h      |
|                        | DB config role (schemas, users, initial SQL) | 4h       |
|                        | Security hardening & CIS benchmarks          | 8h       |
|                        | Backup automation scripts                    | 8h       |
|                        | Docker & Swarm configuration                 | 12h      |
|                        | Keycloak installation & setup                | 10h      |
|                        | Application containers (backend/frontend)    | 8h       |
|                        | Nginx & SSL/TLS configuration                | 10h      |
|                        | GeoServer layers & REST API                  | 13h      |
|                        | Keycloak realm & SSO configuration           | 11h      |
|                        | Monitoring stack (Prometheus, Grafana, Loki) | 16h      |
|                        | ADR logger & CI integration                  | 5h       |
|                        | Restore procedures & validation              | 6h       |
|                        | Molecule tests & CI integration              | 6h       |
|                        | Master playbooks (deploy/rollback)           | 12h      |
|                        | CI/CD pipeline & approval gates              | 7h       |
|                        | n8n webhooks & notifications                 | 6h       |
|                        | JMeter setup & performance tests             | 10h      |
|                        | Security audit                               | 2h       |
|                        | README, guides & diagrams                    | 10h      |
| **Xamek**              | ADR templates & documentation                | 3h       |
| **Marawan**            | Automation helper scripts                    | 4h       |
|                        | Automated testing scripts                    | 13h      |
|                        | Config validation scripts                    | 5h       |
|                        | Deployment validation scripts                | 5h       |
|                        | Final polish & packaging                     | 5h       |
| **Meslmany**           | Bootstrap validation                         | 3h       |
|                        | Infrastructure validation                    | 18h      |
|                        | DR testing procedures                        | 5h       |
|                        | Staging deployment testing                   | 5h       |
| **Marawan + Meslmany** | Operator & user documentation                | 12h      |
| **Alaa + Meslmany**    | E2E testing & SE acceptance                  | 12h      |

### Implementation Specification

_See detailed technical specification below in the [IaC Deployment Implementation Specification](#iac-deployment-implementation-specification) section._

---

## Workstream 3: Automation & Tooling - Detailed Plan

### Workstream 3 Overview

**Duration:** 15 weeks (ongoing)  
**Team:** Marawan (AI automation lead), Xamek (Week 1 architecture)  
**Objective:** Automation framework supporting both workstreams

### Phase 1: Foundation (Weeks 1-2)

#### Week 1: Architecture & Design

#### Focus

Design automation framework

#### Tasks

| Task                                                          | Role | Estimate | Calculation |
| ------------------------------------------------------------- | ---- | -------- | ----------- |
| **Xamek**                                                     |      |          |             |
| Design automation architecture + Define paved roads standards |      | 12h      | 8h + 4h     |

#### Deliverables

- ✅ Automation architecture document
- ✅ Paved roads standards defined
- ✅ CI/CD integration plan

---

#### Week 2: Implementation & Integration

#### Focus

Build and deploy automation tools

#### Tasks

| Task                                                                                         | Role | Estimate | Calculation        |
| -------------------------------------------------------------------------------------------- | ---- | -------- | ------------------ |
| **Marawan**                                                                                  |      |          |                    |
| Validation scripts (9 scripts) + n8n workflows + GitLab board automation + CI/CD integration |      | 44h      | 24h + 8h + 4h + 8h |

#### Deliverables

- ✅ **Validation Scripts (9 total):**
  - `scripts/validate-user-story.sh`
  - `scripts/validate-figma-design.sh`
  - `scripts/check-test-coverage.sh`
  - `scripts/validate-us-coverage.sh`
  - `scripts/validate-figma-coverage.sh`
  - `scripts/check-paved-roads.sh`
  - `scripts/provision-qa-env.sh`
  - `scripts/cleanup-qa-env.sh`
  - `scripts/create-release.sh`
- ✅ **n8n Workflows:**
  - `pr_review_cycle` (reusable workflow)
  - `update_kb` (RAGFlow integration)
  - GitLab board automation
  - Notification workflows
- ✅ `.gitlab-ci.yml` (CI/CD pipeline integration)
- ✅ Paved roads documentation published

---

### Phase 2: Continuous Support (Weeks 3-15)

#### Ongoing Activities

#### Tasks

| Task               | Role | Estimate | Calculation      |
| ------------------ | ---- | -------- | ---------------- |
| **Marawan**        |      |          |                  |
| Automation support |      | 6h/week  | Weekly recurring |

#### Activities

- Monitor CI/CD pipeline health
- Update automation scripts based on feedback
- Add new compliance rules as needed
- Troubleshoot automation failures
- Support plugin and IaC workstreams
- Optimize script performance
- Generate compliance reports

#### Deliverables

- ✅ Weekly automation health reports
- ✅ Script updates and improvements
- ✅ Compliance reports for each plugin batch
- ✅ Continuous CI/CD optimization

---

### Workstream 3 Task Estimates

| Role        | Task                                     | Estimate |
| ----------- | ---------------------------------------- | -------- |
| **Xamek**   | Architecture & design                    | 8h       |
|             | Define paved roads standards             | 4h       |
| **Marawan** | Validation scripts (9 scripts total)     | 24h      |
|             | n8n workflows (PR cycle, KB integration) | 8h       |
|             | GitLab board automation                  | 4h       |
|             | CI/CD pipeline integration               | 8h       |
|             | Automation support (weekly, ongoing)     | 6h/week  |

### Pipeline Specification

_See detailed pipeline specification below in the [GitLab Automated Delivery Pipeline Specification](#gitlab-automated-delivery-pipeline-specification) section._

---

## Appendix: Detailed Specifications

This appendix contains the complete technical specifications for Workstream 2 and Workstream 3. These specifications provide detailed implementation guidance for the development teams.

---

## IaC Deployment Implementation Specification

This section provides the complete technical specification for the Infrastructure-as-Code deployment system that Alaa will build in Workstream 2.

### Strategic Goal

- Enable Solutions Engineers to deploy the entire system on client machines with a single, auditable script
- Embed traceability and governance at every step: provisioning, configuration, identity, orchestration
- Automate compliance checks, decision logging (ADRs), and institutional memory updates

### Modular Ansible Roles

| Role               | Purpose                                               | Governance Hooks                                  |
| ------------------ | ----------------------------------------------------- | ------------------------------------------------- |
| geoserver          | Install GeoServer and extensions                      | Logs version, port, extension list                |
| postgres_postgis   | Provision PostgreSQL with PostGIS                     | Logs database name, version, schema details       |
| docker_swarm       | Initialize Docker Swarm (single-node or cluster)      | Logs swarm ID, join token                         |
| docker_containers  | Pull images and run containers                        | Logs container name, image, ports, env vars       |
| db_config          | Create schemas, users, load initial SQL configuration | Logs config keys, schema ownership                |
| geoserver_layers   | Upload shapefiles & GeoTIFFs via GeoServer REST API   | Logs workspace, store, and layer names            |
| keycloak_config    | Create realm, users, roles in Keycloak                | Logs realm name, usernames, assigned roles        |
| adr_logger         | Generate Architectural Decision Records (ADRs)        | Logs ADR ID, title, status, and decision metadata |
| backend / frontend | Deploy application services                           | Logs service URLs, health check results           |
| security           | Configure firewall, SSL, and network policies         | Logs rule details, certificate fingerprints       |

### Repository Structure

```text
deploy/
├── deploy.yml
├── inventory/
│   ├── dev.yml
│   ├── staging.yml
│   └── production.yml
├── group_vars/
│   ├── all.yml
│   └── <client_id>.yml
├── roles/
│   ├── geoserver/
│   ├── postgres_postgis/
│   ├── docker_swarm/
│   └── ...
├── infra/
│   └── adr/
│       ├── ADR-000-foundation.md
│       ├── ADR-001-geoserver-firewall.md
│       └── ...
├── tests/
│   └── verify.yml
├── bootstrap.sh
└── README.md
```

**bootstrap.sh** installs Ansible, clones the repo, bootstraps inventory, and runs:

```bash
ansible-playbook deploy.yml -i inventory/<client_env>
```

**Client overrides**: Define environment-specific variables in `group_vars/<client_id>.yml`

### GitLab CI/CD Integration

#### Pipeline Stages

- validate
- deploy
- test
- governance
- notify

#### Core CI Jobs

| Job              | Stage      | Command                                            | Artifacts       |
| ---------------- | ---------- | -------------------------------------------------- | --------------- |
| `syntax_check`   | validate   | `ansible-playbook --syntax-check deploy.yml`       | -               |
| `lint`           | validate   | `ansible-lint roles/`                              | -               |
| `deploy_staging` | deploy     | `ansible-playbook deploy.yml -i inventory/staging` | deployment logs |
| `verify`         | test       | `ansible-playbook tests/verify.yml`                | test results    |
| `check_adrs`     | governance | Check for ADRs in `infra/adr/`                     | ADR report      |
| `log_trace`      | governance | Upload `/var/log/deploy_trace.log`                 | trace log       |
| `tag_release`    | governance | Create Git tag: `deploy-<client>-<env>-v<version>` | -               |
| `notify_n8n`     | notify     | Trigger n8n webhook with deployment summary        | -               |

#### Governance Policies

- Protect the `main` and `release/*` branches
- Require Architecture Review Board approval for merges
- Enforce presence of ADRs for new roles/modules
- Block merges on test failures

### n8n Automation Hooks

| Trigger            | Workflow            | Action                                        |
| ------------------ | ------------------- | --------------------------------------------- |
| Deployment success | `deployment_notify` | Send Slack notification, update RAGFlow KB    |
| Deployment failure | `deployment_alert`  | Alert team, create GitLab issue               |
| ADR created        | `adr_review`        | Notify reviewers, schedule review meeting     |
| Backup completed   | `backup_notify`     | Log to governance DB, verify backup integrity |
| Security alert     | `security_incident` | Escalate to security team, log to SIEM        |

### ADR Framework

#### Storage

Store ADRs in `infra/adr/` as `ADR-<###>-<short-title>.md`

#### Template

```markdown
# ADR-003: Use Docker Swarm for Orchestration

## Status

Accepted

## Context

Client-deployed environments need lightweight orchestration.

## Decision

Adopt Docker Swarm for container management.

## Consequences

- Simplifies networking and scaling
- Requires token management and health-check flows
```

#### Enforcement

CI job `check_adrs` enforces an ADR for every new role or major change

### Deployment Verification

#### Central verify playbook

`tests/verify.yml` imports test tasks from each role

#### Role-level assertions

- **GeoServer**: `uri` module checks HTTP 200 on `/geoserver/web`
- **PostGIS**: `postgresql_query` verifies required tables/schema
- **Keycloak**: REST API calls confirm realm and user existence
- **Docker**: `docker_container` facts ensure containers are running
- **Molecule scenarios** (optional) for isolated role testing

### SE Deployment Workflow

#### Step 1: Pre-flight

```bash
# Check system requirements
./scripts/preflight_check.sh

# Review client requirements
cat group_vars/<client_id>.yml
```

#### Step 2: Bootstrap

```bash
# Run bootstrap script
./bootstrap.sh <client_id> <environment>
```

#### Step 3: Deploy

```bash
# Deploy full stack
ansible-playbook deploy.yml -i inventory/<client_id>_<env>.yml

# Or deploy specific roles
ansible-playbook deploy.yml -i inventory/<client_id>_<env>.yml --tags geoserver,postgres
```

#### Step 4: Verify

```bash
# Run verification tests
ansible-playbook tests/verify.yml -i inventory/<client_id>_<env>.yml
```

#### Step 5: Handover

- Review deployment summary report
- Verify all services are healthy
- Update client documentation
- Schedule follow-up review

### Rollback Procedures

#### Tag-based rollback

```bash
# List available versions
git tag -l "deploy-<client>-<env>-*"

# Rollback to specific version
git checkout deploy-<client>-<env>-v1.2.3
ansible-playbook deploy.yml -i inventory/<client_id>_<env>.yml
```

#### Backup-based rollback

```bash
# List available backups
./scripts/list_backups.sh <client_id>

# Restore from backup
ansible-playbook playbooks/restore.yml -i inventory/<client_id>_<env>.yml \
  -e "backup_date=2025-12-15"
```

### Monitoring & Alerting

#### Metrics collected

- System metrics (CPU, memory, disk, network)
- Application metrics (response time, error rate, throughput)
- Database metrics (connections, query time, replication lag)
- GeoServer metrics (WMS/WFS requests, layer count)
- Keycloak metrics (login attempts, active sessions)

#### Alert thresholds

- High CPU: >80% for 5 minutes
- High memory: >90% for 5 minutes
- Disk space low: <10% free
- Service down: 3 consecutive health check failures
- High error rate: >5% for 5 minutes
- SSL expiring: <30 days

### Security Hardening

#### Applied by `security` role

- CIS benchmark compliance
- Firewall configuration (UFW/firewalld)
- SSH hardening (key-based auth, disable root login)
- fail2ban for intrusion prevention
- Automatic security updates
- Audit logging (auditd)
- SELinux/AppArmor enforcement
- SSL/TLS configuration (TLS 1.3 only)

### Backup Strategy

#### Backup schedule

- PostgreSQL: Daily full + hourly incremental
- GeoServer data: Weekly full
- Keycloak realm: Daily
- Application configs: Daily
- Docker volumes: Weekly
- System configs: Daily

#### Retention policy

- Local: 30 days
- Remote (S3/Azure): 90 days
- Compliance archives: 7 years (if required)

#### Backup verification

- Automated restore test: Weekly
- Checksum verification: Daily
- Backup size monitoring: Daily

### Performance Testing with JMeter

#### Test Plans

```
tests/performance/
├── api_load_test.jmx
├── geoserver_wms_test.jmx
├── geoserver_wfs_test.jmx
├── keycloak_auth_test.jmx
├── frontend_load_test.jmx
└── full_stack_test.jmx
```

#### Test Scenarios

| Test Plan                | Target        | Scenario                        | Users    | Duration |
| ------------------------ | ------------- | ------------------------------- | -------- | -------- |
| `api_load_test.jmx`      | Backend API   | CRUD operations on layers       | 100-1000 | 30 min   |
| `geoserver_wms_test.jmx` | GeoServer WMS | GetMap requests (various sizes) | 50-500   | 20 min   |
| `geoserver_wfs_test.jmx` | GeoServer WFS | GetFeature requests             | 50-300   | 20 min   |
| `keycloak_auth_test.jmx` | Keycloak      | Login/logout flows              | 100-500  | 15 min   |
| `frontend_load_test.jmx` | Frontend      | Page loads, interactions        | 200-1000 | 30 min   |
| `full_stack_test.jmx`    | All services  | End-to-end user journeys        | 100-500  | 60 min   |

#### Acceptance Criteria

- Average response time: <500ms for API, <200ms for WMS/WFS
- 95th percentile: <1000ms for API, <500ms for WMS/WFS
- Error rate: <1%
- Throughput: >100 req/sec for API, >50 req/sec for GeoServer
- System CPU: <80% under load
- System memory: <85% under load

### Documentation Deliverables

#### For Solutions Engineers

- Quick-start guide
- Deployment checklist
- Troubleshooting FAQ
- Client customization guide
- Video walkthrough
- Performance testing guide

#### For Operations

- Operator runbook
- Maintenance procedures
- Backup/restore procedures
- Disaster recovery plan
- Monitoring guide
- Performance baseline reports

#### For Developers

- Architecture overview
- API documentation
- Database schema
- Configuration reference
- Development setup guide
- JMeter test plan documentation

---

## GitLab Automated Delivery Pipeline Specification

This section describes the complete automated workflow that Marawan will implement as part of Workstream 3.

### GitLab Board Columns

| Column Name                   | Label Used            | Purpose                                              |
| ----------------------------- | --------------------- | ---------------------------------------------------- |
| Backlog                       | `backlog`             | Placeholder for untriaged issues                     |
| User Story Review             | `user-story-review`   | PR open for `/docs/user-stories/*.md`                |
| Fixing US Review Comments     | `fix-us-comments`     | PO or reviewers requested changes to user story      |
| Design Review                 | `design-review`       | PR open for `/designs/README.md`                     |
| Fixing Design Review Comments | `fix-design-comments` | UX or reviewers requested changes to Figma or README |
| Dev Review                    | `dev-review`          | PR open for `/src/plugins/`                          |
| Fixing Code Review Comments   | `fix-code-comments`   | Dev or CTO requested changes during code review      |
| Ready for QA                  | `ready-for-qa`        | Dev complete â€” QA issue opened                     |
| QA In Progress                | `qa-in-progress`      | QA actively testing                                  |
| Bug Fixing                    | `bug-fixing`          | Bugs confirmed and assigned to Developer             |
| QA Retest                     | `qa-retest`           | QA verifying fixed bugs                              |
| QA Passed                     | `qa-passed`           | All bugs resolved â€” QA passed                      |
| Ready for Release             | `ready-for-release`   | Approved for deployment                              |
| Done                          | `done`                | Released to production                               |

### Roles & Responsibilities

| Role              | Person                            | Responsibilities                            |
| ----------------- | --------------------------------- | ------------------------------------------- |
| Product Owner     | Hajar                             | User story creation, acceptance criteria    |
| Solution Engineer | Meslmany                          | First review, feasibility assessment        |
| Chief Architect   | Xamek                             | Technical standards, architecture review    |
| Senior Developer  | Mounir                            | Code review, design review, spec validation |
| AI Developer      | Marawan                           | Automation scripts, CI/CD integration       |
| CTO               | Amr                               | Final approval, technical sign-off          |
| UX Designer       | Menna                             | Figma designs, design system                |
| Developers        | Omar, Basem, Khadra, Hassan, Samy | Implementation, bug fixes                   |
| QA Engineer       | TBD                               | Test planning, execution, bug reporting     |

### Step 1: PO Creates User Story Document

**Branch**: `story/plugin-xyz` → `main`  
**File**: `/docs/user-stories/plugin-xyz.md`  
**Reviewers**: Solution Engineer, Senior Developer, Architect  
**Board Column**: `User Story Review`

#### n8n Actions

- On PR opened:
  - Trigger: `pr_review_cycle` workflow (reusable)
  - Move issue to `user-story-review`
  - Update RAGFlow KB with: user story content, acceptance criteria
- On PR review comment added:
  - Label `fix-us-comments`
  - Move issue to `fix-us-comments`
- On PR updated and re-approved:
  - Remove `fix-us-comments`
  - Move back to `user-story-review`
- On PR merged:
  - Run validation script: `scripts/validate-user-story.sh`
  - If valid:
    - Add GitLab tag: `usdoc-finalized-plugin-xyz`
    - Notify: UX Designer (Menna)
    - Update RAGFlow KB with: finalized status
  - If invalid:
    - Open issue: `fix-usdoc-format-plugin-xyz`
    - Label: `validation-failed`
    - Assign: Product Owner (Hajar)
    - Move to: `fix-us-comments`

### Step 2: UX Designer Creates & Updates Figma Design

**Branch**: `design/plugin-xyz` → `main`  
**File**: `/designs/plugin-xyz/README.md`  
**Reviewers**: Senior Developer, Product Owner  
**Board Column**: `Design Review`  
**Prerequisites**: GitLab tag `usdoc-finalized-plugin-xyz` exists

#### n8n Actions

- On PR opened:
  - Trigger: `pr_review_cycle` workflow (reusable)
  - Move issue to `design-review`
  - Update RAGFlow KB with: Figma links, component mapping
- On PR review comment added:
  - Label `fix-design-comments`
  - Move issue to `fix-design-comments`
- On PR updated and re-approved:
  - Remove `fix-design-comments`
  - Move back to `design-review`
- On PR merged:
  - Run validation script: `scripts/validate-figma-design.sh`
  - If valid:
    - Add GitLab tag: `figma-finalized-plugin-xyz`
    - Notify: Assigned Developer
    - Update RAGFlow KB with: finalized design specs
  - If invalid:
    - Open issue: `fix-figma-readme-plugin-xyz`
    - Label: `validation-failed`
    - Assign: UX Designer (Menna)
    - Move to: `fix-design-comments`

### Step 3: Developer Implementation

**Branch**: `feature/plugin-xyz` → `main`  
**Location**: `/src/plugins/plugin-xyz/`  
**Reviewers**: Senior Developer (Mounir), CTO (Amr)  
**Board Column**: `Dev Review`  
**Prerequisites**: GitLab tags `usdoc-finalized-plugin-xyz` and `figma-finalized-plugin-xyz` exist

#### n8n Actions

- On PR opened:
  - Trigger: `pr_review_cycle` workflow (reusable)
  - Move issue to `dev-review`
  - Update RAGFlow KB with: implementation approach, tech stack
- On PR review comment added:
  - Label `fix-code-comments`
  - Move issue to `fix-code-comments`
- On PR updated and re-approved:
  - Remove `fix-code-comments`
  - Move back to `dev-review`
- On PR merged:
  - Trigger CI pipeline (GitLab CI)
  - Run Marawan's automation scripts:
    - `scripts/check-test-coverage.sh` (â‰¥ 80%)
    - `scripts/validate-us-coverage.sh` (vs user story)
    - `scripts/validate-figma-coverage.sh` (vs design)
    - `scripts/check-paved-roads.sh` (compliance)
  - If all pass:
    - Add GitLab tag: `dev-complete-plugin-xyz`
    - Provision QA environment: `scripts/provision-qa-env.sh plugin-xyz`
    - Open issue: `test-plugin-xyz`
    - Assign: QA Engineer
    - Move to: `ready-for-qa`
    - Update RAGFlow KB with: implementation details, test results
  - If any fail:
    - Open issue: `fix-compliance-plugin-xyz`
    - Label: `compliance-failed`
    - Assign: Original Developer
    - Move to: `fix-code-comments`
    - Comment: Link to failed validation reports

### Step 4: QA Testing

**Trigger**: Issue `test-plugin-xyz` opened by n8n  
**Milestone**: `QA plugin-xyz v1.0`  
**Board Column**: `QA In Progress` → `Bug Fixing` → `QA Retest` → `QA Passed`  
**Prerequisites**: GitLab tag `dev-complete-plugin-xyz` exists, QA environment provisioned

#### QA Workflow

- QA Engineer begins testing only after:
  - Issue `test-plugin-xyz` is assigned to them
  - GitLab tags exist: `usdoc-finalized-plugin-xyz`, `figma-finalized-plugin-xyz`, `dev-complete-plugin-xyz`
  - QA environment URL provided in issue description
- Test cases derived from:
  - User story acceptance criteria
  - Figma design specifications
  - Technical documentation
- Bugs logged as GitLab issues using `.gitlab/issue_templates/QA_Bug_Report.md`
- Each bug must include:
  - Label: `qa-bug` (severity: `qa-blocker`, `qa-critical`, `qa-major`, `qa-minor`)
  - Assigned to: Original Developer
  - Linked to: Milestone `QA plugin-xyz v1.0`
  - Parent issue: `test-plugin-xyz`
  - References: User story section, Figma component, code file

#### n8n Actions

- On `test-plugin-xyz` opened:
  - Schedule QA kickoff meeting (attendees: QA Engineer, Developer, Mounir)
  - Move parent issue to: `qa-in-progress`
  - Update RAGFlow KB with: QA start date, environment URL
- On QA bug issue opened:
  - Validate bug template completeness
  - Auto-link to milestone: `QA plugin-xyz v1.0`
  - Set parent issue: `test-plugin-xyz`
  - Notify: Assigned Developer
  - Move bug issue to: `bug-fixing`
  - Update RAGFlow KB with: bug details, severity
- On bug issue labeled `bug-fixed`:
  - Notify: QA Engineer
  - Move bug issue to: `qa-retest`
  - Add comment: "Developer marked as fixed, ready for retest"
- On bug issue labeled `retest-passed`:
  - Close bug issue
  - Add comment: "QA verified fix"
- On bug issue labeled `retest-failed`:
  - Increment retry counter (custom field)
  - If retry count > 3:
    - Label: `escalation-needed`
    - Notify: CTO (Amr), Senior Developer (Mounir)
  - Else:
    - Move back to: `bug-fixing`
    - Notify: Developer
- On `test-plugin-xyz` closed with label `qa-passed`:
  - Verify all linked bugs are closed
  - Add GitLab tag: `qa-passed-plugin-xyz`
  - Move parent issue to: `qa-passed`
  - Update RAGFlow KB with: QA completion date, test summary
  - Notify: CTO (Amr) for release approval
- On `test-plugin-xyz` closed with label `qa-failed`:
  - Label: `escalation-needed`
  - Notify: CTO (Amr), Chief Architect (Xamek)
  - Require: Root cause analysis document

### Step 5: Release & Deployment

**Trigger**: Issue moved to `qa-passed`  
**Board Column**: `Ready for Release` → `Done`  
**Prerequisites**: GitLab tag `qa-passed-plugin-xyz` exists

#### Release Workflow

- CTO (Amr) reviews QA results and approves release
- Release manager creates release branch
- Deployment to staging → production

#### n8n Actions

- On issue moved to `qa-passed`:
  - Create release approval request
  - Assign: CTO (Amr)
  - Notify: Release manager
- On release approved:
  - Add GitLab tag: `release-approved-plugin-xyz`
  - Move issue to: `ready-for-release`
  - Trigger: `scripts/create-release.sh plugin-xyz`
  - Update RAGFlow KB with: release version, approval date
- On deployment completed:
  - Add GitLab tag: `deployed-plugin-xyz-v1.0`
  - Move issue to: `done`
  - Close issue
  - Cleanup QA environment: `scripts/cleanup-qa-env.sh plugin-xyz`
  - Update RAGFlow KB with: deployment date, production URL
  - Send notification: All stakeholders

### Reusable Workflows

#### `pr_review_cycle` (n8n sub-workflow)

**Trigger**: PR opened for any step  
**Actions**:

1. Parse PR metadata (plugin name, step, reviewers)
2. Schedule review meeting:
   - Step 1: Joint review (PO, SE, Architect, Sr Dev)
   - Step 2: Design review (UX, Sr Dev, PO)
   - Step 3: Technical review (Sr Dev, CTO)
3. Send calendar invites with PR link
4. Create meeting agenda from template
5. On meeting end:
   - Generate AI summary (from recording/notes)
   - Log to: `/logs/meeting-summaries/YYYY-MM-DD-plugin-xyz-step-N.md`
   - Post summary as PR comment

#### `update_kb` (n8n sub-workflow)

**Trigger**: Any significant state change  
**Actions**:

1. Extract relevant content based on event type
2. Format for RAGFlow ingestion
3. Update RAGFlow KB with categorized content:
   - User stories → `kb/user-stories/`
   - Designs → `kb/designs/`
   - Implementation → `kb/implementations/`
   - QA results → `kb/qa-results/`
   - Releases → `kb/releases/`
4. Add metadata: timestamp, plugin name, step, status

### Validation Scripts (by Marawan)

| Script                               | Purpose                             | Exit Code on Failure |
| ------------------------------------ | ----------------------------------- | -------------------- |
| `scripts/validate-user-story.sh`     | Check US doc has required sections  | 1                    |
| `scripts/validate-figma-design.sh`   | Verify Figma links, Chakra mapping  | 2                    |
| `scripts/check-test-coverage.sh`     | Ensure unit test coverage â‰¥ 80%   | 3                    |
| `scripts/validate-us-coverage.sh`    | Match implementation to user story  | 4                    |
| `scripts/validate-figma-coverage.sh` | Match UI components to Figma        | 5                    |
| `scripts/check-paved-roads.sh`       | Verify coding standards compliance  | 6                    |
| `scripts/provision-qa-env.sh`        | Create isolated QA environment      | 7                    |
| `scripts/cleanup-qa-env.sh`          | Remove QA environment after release | 8                    |
| `scripts/create-release.sh`          | Generate release branch and notes   | 9                    |

**Integration**: All scripts integrated into GitLab CI pipeline (`.gitlab-ci.yml`)  
**Reporting**: Validation failures logged to `/logs/validation-failures/`

---

**Document Status:** ✅ Ready for Execution  
**Approval Required:** ARB, Chief Architect (Xamek)  
**Next Review:** Weekly during execution  
**Questions/Feedback:** Contact Xamek, Alaa (IaC), or Marawan (Automation)
