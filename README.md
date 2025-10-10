# Engineering Department Q1-Q2 2026 Action Plan
## Comprehensive 4-Month Strategic Roadmap

**Planning Period:** October 2025 - February 2026 (15 weeks)  
**Department:** Engineering  
**Document Version:** 1.0  
**Last Updated:** October 9, 2025  
**Status:** 🎯 Ready for Execution

---

## Table of Contents

- [Executive Summary](#executive-summary)
- [Strategic Objectives](#strategic-objectives)
  - [Primary Goals](#primary-goals)
- [Team Structure & Roles](#team-structure--roles)
  - [Engineering Team](#engineering-team-10-people)
  - [Products Team](#products-team-4-people)
  - [Delivery Team](#delivery-team-1-person)
- [Parallel Workstreams](#parallel-workstreams)
  - [Workstream 1: Plugin Handover](#workstream-1-plugin-handover-weeks-1-15)
  - [Workstream 2: IaC Deployment](#workstream-2-iac-deployment-weeks-1-12)
  - [Workstream 3: Automation & Tooling](#workstream-3-automation--tooling-ongoing)
- [Workstream 1: Plugin Handover - Detailed Plan](#workstream-1-plugin-handover---detailed-plan)
  - [Overview](#overview)
  - [Plugin List](#plugin-list)
  - [Weeks 1-2: Preparation Phase](#weeks-1-2-preparation-phase)
  - [Batch Cycle Pattern](#batch-cycle-pattern-2-weeks-per-batch)
  - [Week 15: Final Handover](#week-15-final-handover)
  - [Task Estimates](#task-estimates)
- [Workstream 2: IaC Deployment - Detailed Plan](#workstream-2-iac-deployment---detailed-plan)
  - [Overview](#overview-1)
  - [Week-by-Week Breakdown](#week-by-week-breakdown)
  - [IaC Post-Week 12: Support Mode](#iac-post-week-12-support-mode)
  - [Task Estimates](#task-estimates-1)
- [Workstream 3: Automation & Tooling - Detailed Plan](#workstream-3-automation--tooling---detailed-plan)
  - [Overview](#overview-2)
  - [Phase 1: Foundation](#phase-1-foundation-weeks-1-2)
  - [Phase 2: Continuous Support](#phase-2-continuous-support-weeks-3-15)
  - [Task Estimates](#task-estimates-2)
- [IaC Deployment Implementation Specification](#iac-deployment-implementation-specification)
- [GitLab Automated Delivery Pipeline Specification](#gitlab-automated-delivery-pipeline-specification)

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
**Key Milestones:** 
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

| Name | Role |
|------|------|
| **Xamek** | Chief Architect |
| **Mounir** | Senior Developer |
| **Alaa** | DevOps Engineer |
| **Marawan** | AI Developer |
| **Omar** | Developer |
| **Basem** | Developer |
| **Khadra** | Developer |
| **Hassan** | Developer |
| **Samy** | Developer |

### Products Team (4 people)

| Name | Role |
|------|------|
| **Amr** | CTO |
| **Hajar** | Product Owner |
| **Menna** | UX Designer |
| **QA Engineer** | QA Engineer (TBD) |

### Delivery Team (1 person)

| Name | Role |
|------|------|
| **Meslmany** | Solutions Engineer |

---

## Parallel Workstreams

### Workstream 1: Plugin Handover (Weeks 1-15)

**Objective:** Transfer 30 plugins to Products Team

**Timeline:** 15 weeks (2-week cycles per batch)
- Weeks 1-2: Preparation
- Weeks 3-14: 6 batches Ã— 2 weeks each
- Week 15: Final handover

**Team:** 5 developers + Hajar + Menna + Mounir + Xamek + Amr + QA

**Key Deliverables:**
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

**Key Deliverables:**
- 17 Ansible roles
- GitLab CI/CD pipeline
- JMeter performance tests
- Complete documentation

### Workstream 3: Automation & Tooling (Ongoing)

**Objective:** Support both workstreams with automation

**Timeline:** Weeks 1-12 (ongoing)

**Team:** Marawan

**Key Deliverables:**
- Paved roads compliance scripts
- User story coverage automation
- Code review automation
- Figma compliance checking
- CI/CD pipeline integration

---

## Workstream 1: Plugin Handover - Detailed Plan

### Overview
**Duration:** 15 weeks  
**Team:** 5 Developers (Omar, Basem, Khadra, Hassan, Samy), Hajar (Product Owner), Menna (UX Designer), Mounir (Code Reviews), Xamek (Technical Reviews), Amr (Code Reviews), QA Engineer, Meslmany (Story Reviews)  
**Objective:** Transfer 30 plugins to Products Team with Chakra UI refactoring

### Plugin List

| Developer | Batch 1 (Wk 3-4) | Batch 2 (Wk 5-6) | Batch 3 (Wk 7-8) | Batch 4 (Wk 9-10) | Batch 5 (Wk 11-12) | Batch 6 (Wk 13-14) |
|-----------|------------------|------------------|------------------|-------------------|--------------------|--------------------|
| **Omar** | Bookmarks | Measurement | TOC | Inbox | Data Inspector | Go To Point |
| **Basem** | Identify | Feature Selector | Charts | Cards | Find Nearest | Smart Indoor |
| **Khadra** | Advanced Search | Sketching | Reporting | Simple Search | Alarms | Classification |
| **Hassan** | Spatial Search | Fulltext Search | Export PDF | Geometry | Editing | Data Review |
| **Samy** | Driller | Timeline | Simple Import | Legend | Territory Manager | More Info |

### Weeks 1-2: Preparation Phase

**Focus:** Standards, tools, and example plugin

**Tasks:**


| Task | Role | Estimate | Calculation |
|------|------|----------|-------------|
| User Story Creation | Hajar | 60h | 15 plugins × 4h |
| User Story Review | Meslmany | 15h | 15 plugins × 1h |
| User Story Review | Xamek | 15h | 15 plugins × 1h |
| User Story Review | Mounir | 15h | 15 plugins × 1h |
| Plugin Review Checklist | Mounir | 2h | One-time task |
| Example Plugin | Mounir | 14h | One-time task |
| Figma Design Review | Mounir | 5h | 5 plugins × 1h |
| Figma Baseline | Menna | 8h | One-time task |
| Design System Docs | Menna | 6h | One-time task |
| Figma Designs | Menna | 40h | 5 plugins × 8h |
| Chakra Theme Setup | All Developers | 8h | One-time task |
| Linting & CI Setup | All Developers | 8h | One-time task |

**Deliverables:**
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
**Focus:** Development and design for next batch

**Tasks:**

| Task | Role | Estimate | Calculation |
|------|------|----------|-------------|
| User Story Creation (next batch) | Hajar | 20h | 5 plugins × 4h |
| User Story Review (next batch) | Meslmany | 5h | 5 plugins × 1h |
| User Story Review (next batch) | Xamek | 5h | 5 plugins × 1h |
| User Story Review (next batch) | Mounir | 5h | 5 plugins × 1h |
| Figma Designs (next batch) | Menna | 40h | 5 plugins × 8h |
| Figma Design Review (next batch) | Mounir | 5h | 5 plugins × 1h |
| Plugin Implementation (current batch) | 5 Developers | 210h | 5 plugins × 42h each |
| Code Review (current batch) | Mounir | 5h | 5 plugins × 1h |
| Code Review (current batch) | Amr | 5h | 5 plugins × 1h |

#### Week 2 (Testing & QA)
**Focus:** Bug fixing and quality assurance

**Tasks:**

| Task | Role | Estimate | Calculation |
|------|------|----------|-------------|
| Plugin Testing | QA Engineer | 30h | 5 plugins × 6h |
| Bug Fixing | 5 Developers | 130h | 5 plugins × 26h each |

**Deliverables per Batch:**
- ✅ 5 plugins refactored with Chakra UI (3 for Batch 6)
- ✅ 5 Figma designs (3 for Batch 6)
- ✅ User stories documented
- ✅ Code reviewed and approved by Mounir & Amr
- ✅ Test coverage >80%
- ✅ QA sign-off

---

### Week 15: Final Handover

**Focus:** Documentation and knowledge transfer

**Tasks:**

| Task | Role | Estimate | Calculation |
|------|------|----------|-------------|
| Compile handover materials | All Team | 50h | Combined effort |
| Final documentation review | Mounir + Xamek | Included | Part of handover |
| Knowledge transfer sessions | All Team | Included | Part of handover |
| Products Team acceptance testing | Products Team | Included | Part of handover |
| Sign-off and celebration | All | Included | Part of handover |

**Deliverables:**
- ✅ 30 plugins delivered
- ✅ Complete technical documentation
- ✅ All Figma designs
- ✅ Handover checklist completed
- ✅ Products Team sign-off

---

### Task Estimates

| Role | Task | Estimate |
|------|------|----------|
| **Hajar** | Create user story | 4h |
| **Meslmany** | Review user story | 1h |
| **Xamek** | Review user story | 1h |
| **Mounir** | Review user story | 1h |
| | Define plugin review checklist | 2h |
| | Create example plugin | 14h |
| | Review Figma design | 1h |
| | Code review | 1h |
| **Amr** | Code review | 1h |
| **Menna** | Establish Figma baseline | 8h |
| | Create design system docs | 6h |
| | Create Figma design | 8h |
| **Developer** | Setup Chakra theme | 8h |
| | Setup linting & CI | 8h |
| | Implement plugin | 42h |
| | Bug fixing | 26h |
| **QA Engineer** | Test plugin | 6h |

---

## Workstream 2: IaC Deployment - Detailed Plan

### Overview
**Duration:** 12 weeks  
**Team:** Alaa (DevOps lead), Marawan (AI automation), Meslmany (validation)  
**Objective:** Production-ready infrastructure automation

### Week-by-Week Breakdown

#### Week 1: Foundation Setup
**Focus:** Repository structure and planning

**Tasks:**

| Task | Role | Estimate | Calculation |
|------|------|----------|-------------|
| Repository scaffold & Ansible structure & bootstrap script | Alaa | 23h | Combined tasks |
| ADR template and documentation | Xamek | 3h | One-time task |
| Automation helper scripts | Marawan | 4h | One-time task |
| Bootstrap validation | Meslmany | 3h | One-time task |

**Deliverables:**
- ✅ GitLab repository: `iac-deployment-automation`
- ✅ Complete directory structure
- ✅ Bootstrap script tested on Ubuntu 22.04
- ✅ Environment strategy documented
- ✅ ADR-000 written

---

#### Week 2: GeoServer & Firewall
**Focus:** First infrastructure roles

**Tasks:**

| Task | Role | Estimate | Calculation |
|------|------|----------|-------------|
| GeoServer role + Firewall role & configuration | Alaa | 18h | 12h + 6h |
| Automated testing scripts | Marawan | 3h | One-time task |
| Deployment validation | Meslmany | 4h | One-time task |

**Deliverables:**
- ✅ `roles/geoserver/` (127 lines of Ansible YAML)
- ✅ `roles/firewall/` (68 lines of Ansible YAML)
- ✅ ADR-001 written
- ✅ Installation guide created

---

#### Week 3: PostgreSQL & Security
**Focus:** Database and security hardening

**Tasks:**

| Task | Role | Estimate | Calculation |
|------|------|----------|-------------|
| PostgreSQL & PostGIS setup + Security hardening & CIS benchmarks | Alaa | 18h | 10h + 8h |
| Backup automation scripts | Marawan | 3h | One-time task |
| DB validation and backup testing | Meslmany | 4h | One-time task |

**Deliverables:**
- ✅ `roles/postgres_postgis/` (156 lines)
- ✅ `roles/security_hardening/` (203 lines)
- ✅ Backup script: `pg_backup.sh`
- ✅ ADR-002 written

---

#### Week 4: Keycloak & Docker Swarm
**Focus:** Identity management and container orchestration

**Tasks:**

| Task | Role | Estimate | Calculation |
|------|------|----------|-------------|
| Docker & Swarm configuration + Keycloak installation & setup | Alaa | 22h | 12h + 10h |
| Container health check scripts | Marawan | 3h | One-time task |
| Keycloak and Docker validation | Meslmany | 4h | One-time task |

**Deliverables:**
- ✅ `roles/keycloak_install/` (134 lines)
- ✅ `roles/docker_swarm/` (98 lines)
- ✅ Docker Compose file for Keycloak
- ✅ ADR-003 written

---

#### Week 5: Application Services & Reverse Proxy
**Focus:** App containers and SSL/TLS

**Tasks:**

| Task | Role | Estimate | Calculation |
|------|------|----------|-------------|
| Application containers + Nginx & SSL/TLS configuration | Alaa | 18h | 8h + 10h |
| Config validation scripts | Marawan | 5h | One-time task |
| SSL validation and config testing | Meslmany | 5h | One-time task |

**Deliverables:**
- ✅ `roles/docker_containers/` (187 lines)
- ✅ `roles/db_config/` (112 lines)
- ✅ `roles/reverse_proxy/` (156 lines)
- ✅ Nginx config templates
- ✅ SQL initialization scripts
- ✅ ADR-004 written

---

#### Week 6: GeoServer Layers
**Focus:** Spatial data management

**Tasks:**

| Task | Role | Estimate | Calculation |
|------|------|----------|-------------|
| GeoServer layers & REST API | Alaa | 13h | One-time task |
| Layer validation scripts | Marawan | 4h | One-time task |
| Sample data preparation and layer validation | Meslmany | 5h | One-time task |

**Deliverables:**
- ✅ `roles/geoserver_layers/` (143 lines)
- ✅ Sample data (3 vector layers, 2 raster layers)
- ✅ SLD styles
- ✅ Validation script: `validate_layers.py`
- ✅ ADR-005 written

---

#### Week 7: Keycloak Configuration
**Focus:** Identity and access management

**Tasks:**

| Task | Role | Estimate | Calculation |
|------|------|----------|-------------|
| Keycloak realm & SSO configuration | Alaa | 11h | One-time task |
| User provisioning automation | Marawan | 4h | One-time task |
| User templates and login testing | Meslmany | 4h | One-time task |

**Deliverables:**
- ✅ `roles/keycloak_config/` (178 lines)
- ✅ Realm export: `gis_platform_realm.json`
- ✅ User templates
- ✅ Provisioning script: `provision_users.py`
- ✅ ADR-006 written

---

#### Week 8: Monitoring & Logging
**Focus:** Observability and ADR review

**Tasks:**

| Task | Role | Estimate | Calculation |
|------|------|----------|-------------|
| Monitoring stack + ADR logger & CI integration | Alaa | 21h | 16h + 5h |
| ADR review and finalization | Marawan | 6h | One-time task |
| Dashboard review and alert testing | Meslmany | 4h | One-time task |

**Deliverables:**
- ✅ `roles/monitoring/` (234 lines)
- ✅ `roles/logging/` (156 lines)
- ✅ `roles/adr_logger/` (89 lines)
- ✅ 8 Grafana dashboards
- ✅ 12 alert rules
- ✅ ADR-007 written
- ✅ All ADRs (000-007) reviewed and approved

---

#### Week 9: Testing & Backup
**Focus:** Comprehensive testing and backup automation

**Tasks:**

| Task | Role | Estimate | Calculation |
|------|------|----------|-------------|
| Backup & restore automation + Molecule tests & CI integration | Alaa | 18h | 12h + 6h |
| Test automation scripts | Marawan | 5h | One-time task |
| Test case definition and DR testing | Meslmany | 5h | One-time task |

**Deliverables:**
- ✅ `roles/backup_restore/` (198 lines)
- ✅ `playbooks/verify.yml` (156 lines)
- ✅ 189 Molecule tests (84% coverage)
- ✅ Backup scripts for all services
- ✅ ADR-008 written

---

#### Week 10: Master Playbook & CI/CD
**Focus:** Deployment automation and pipeline

**Tasks:**

| Task | Role | Estimate | Calculation |
|------|------|----------|-------------|
| Master playbooks + CI/CD pipeline & approval gates | Alaa | 19h | 12h + 7h |
| Deployment validation scripts | Marawan | 5h | One-time task |
| Staging deployment testing | Meslmany | 5h | One-time task |

**Deliverables:**
- ✅ `playbooks/deploy.yml` (234 lines)
- ✅ `playbooks/rollback.yml` (156 lines)
- ✅ Environment configs for dev/staging/prod
- ✅ `.gitlab-ci.yml` (187 lines)
- ✅ Deployment scripts
- ✅ ADR-009 written

---

#### Week 11: DR Testing & Documentation
**Focus:** Disaster recovery and comprehensive docs

**Tasks:**

| Task | Role | Estimate | Calculation |
|------|------|----------|-------------|
| n8n webhooks + JMeter & performance tests + Security audit | Alaa | 18h | 6h + 10h + 2h |
| Operator documentation | Marawan | 6h | One-time task |
| User documentation | Meslmany | 6h | One-time task |

**Deliverables:**
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
**Focus:** Production readiness and SE handover

**Tasks:**

| Task | Role | Estimate | Calculation |
|------|------|----------|-------------|
| README, guides & diagrams + E2E testing | Alaa | 22h | 10h + 12h |
| Final polish & packaging | Marawan | 5h | One-time task |
| SE acceptance testing | Meslmany | 6h | One-time task |

**Deliverables:**
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

**Weeks 13-15:**
- Alaa: 8h/week support and maintenance
- Deploy to 3+ client sites
- Gather feedback and iterate
- Minor enhancements and bug fixes
- Support plugin team as needed

---

### Task Estimates

| Role | Task | Estimate |
|------|------|----------|
| **Alaa** | Repository setup & Ansible structure | 23h |
| | GeoServer role (Java, Tomcat, GeoServer) | 12h |
| | Firewall role & configuration | 6h |
| | PostgreSQL & PostGIS setup | 10h |
| | Security hardening & CIS benchmarks | 8h |
| | Docker & Swarm configuration | 12h |
| | Keycloak installation & setup | 10h |
| | Application containers (backend/frontend) | 8h |
| | Nginx & SSL/TLS configuration | 10h |
| | GeoServer layers & REST API | 13h |
| | Keycloak realm & SSO configuration | 11h |
| | Monitoring stack (Prometheus, Grafana, Loki) | 16h |
| | ADR logger & CI integration | 5h |
| | Backup & restore automation | 12h |
| | Molecule tests & CI integration | 6h |
| | Master playbooks (deploy/rollback) | 12h |
| | CI/CD pipeline & approval gates | 7h |
| | n8n webhooks & notifications | 6h |
| | JMeter setup & performance tests | 10h |
| | Security audit | 2h |
| | README, guides & diagrams | 10h |
| **Xamek** | ADR templates & documentation | 3h |
| **Marawan** | Automation helper scripts | 4h |
| | Automated testing scripts | 13h |
| | Deployment validation scripts | 5h |
| | Final polish & packaging | 5h |
| **Meslmany** | Bootstrap validation | 3h |
| | Infrastructure validation | 18h |
| | DR testing procedures | 5h |
| | Staging deployment testing | 5h |
| **Marawan + Meslmany** | Operator & user documentation | 12h |
| **Alaa + Meslmany** | E2E testing & SE acceptance | 12h |

---

## Workstream 3: Automation & Tooling - Detailed Plan

### Overview
**Duration:** 15 weeks (ongoing)  
**Team:** Marawan (AI automation lead), Xamek (Week 1 architecture)  
**Objective:** Automation framework supporting both workstreams

### Phase 1: Foundation (Weeks 1-2)

#### Week 1: Architecture & Design
**Focus:** Design automation framework

**Tasks:**

| Task | Role | Estimate | Calculation |
|------|------|----------|-------------|
| Design automation architecture + Define paved roads standards | Xamek | 12h | 8h + 4h |

**Deliverables:**
- ✅ Automation architecture document
- ✅ Paved roads standards defined
- ✅ CI/CD integration plan

---

#### Week 2: Implementation & Integration
**Focus:** Build and deploy automation tools

**Tasks:**

| Task | Role | Estimate | Calculation |
|------|------|----------|-------------|
| Paved roads script + User story coverage + Code review automation + Figma compliance + CI/CD integration | Marawan | 32h | 8h + 6h + 6h + 4h + 8h |

**Deliverables:**
- ✅ `scripts/paved_roads_check.py` (automated compliance)
- ✅ `scripts/user_story_coverage.py` (requirement tracking)
- ✅ `scripts/code_review_automation.py` (PR automation)
- ✅ `scripts/figma_compliance_check.py` (design validation)
- ✅ `.gitlab-ci.yml` (CI/CD integration for all checks)
- ✅ Paved roads documentation published

---

### Phase 2: Continuous Support (Weeks 3-15)

#### Ongoing Activities

**Tasks:**

| Task | Role | Estimate | Calculation |
|------|------|----------|-------------|
| Automation support | Marawan | 6h/week | Weekly recurring |

**Activities:**
- Monitor CI/CD pipeline health
- Update automation scripts based on feedback
- Add new compliance rules as needed
- Troubleshoot automation failures
- Support plugin and IaC workstreams
- Optimize script performance
- Generate compliance reports

**Deliverables:**
- ✅ Weekly automation health reports
- ✅ Script updates and improvements
- ✅ Compliance reports for each plugin batch
- ✅ Continuous CI/CD optimization

---

### Task Estimates

| Role | Task | Estimate |
|------|------|----------|
| **Xamek** | Design automation architecture | 8h |
| | Define paved roads standards | 4h |
| **Marawan** | Create paved roads script | 8h |
| | Create user story coverage script | 6h |
| | Create code review automation | 6h |
| | Create Figma compliance script | 4h |
| | Integrate CI/CD | 8h |
| | Automation support | 6h |

---

## IaC Deployment Implementation Specification

This section provides the complete technical specification for the Infrastructure-as-Code deployment system that Alaa will build in Workstream 2.

### Strategic Goal
- Enable Solutions Engineers to deploy the entire system on client machines with a single, auditable script
- Embed traceability and governance at every step: provisioning, configuration, identity, orchestration
- Automate compliance checks, decision logging (ADRs), and institutional memory updates

### Modular Ansible Roles

| Role | Purpose | Governance Hooks |
|------|---------|------------------|
| geoserver | Install GeoServer and extensions | Logs version, port, extension list |
| postgres_postgis | Provision PostgreSQL with PostGIS | Logs database name, version, schema details |
| docker_swarm | Initialize Docker Swarm (single-node or cluster) | Logs swarm ID, join token |
| docker_containers | Pull images and run containers | Logs container name, image, ports, env vars |
| db_config | Create schemas, users, load initial SQL configuration | Logs config keys, schema ownership |
| geoserver_layers | Upload shapefiles & GeoTIFFs via GeoServer REST API | Logs workspace, store, and layer names |
| keycloak_config | Create realm, users, roles in Keycloak | Logs realm name, usernames, assigned roles |
| adr_logger | Generate Architectural Decision Records (ADRs) | Logs ADR ID, title, status, and decision metadata |
| backend / frontend | Deploy application services | Logs service URLs, health check results |
| security | Configure firewall, SSL, and network policies | Logs rule details, certificate fingerprints |
### Repository Structure
```
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

**Pipeline Stages:**
- validate
- deploy
- test
- governance
- notify

**Core CI Jobs:**

| Job | Stage | Command | Artifacts |
|-----|-------|---------|-----------|
| `syntax_check` | validate | `ansible-playbook --syntax-check deploy.yml` | - |
| `lint` | validate | `ansible-lint roles/` | - |
| `deploy_staging` | deploy | `ansible-playbook deploy.yml -i inventory/staging` | deployment logs |
| `verify` | test | `ansible-playbook tests/verify.yml` | test results |
| `check_adrs` | governance | Check for ADRs in `infra/adr/` | ADR report |
| `log_trace` | governance | Upload `/var/log/deploy_trace.log` | trace log |
| `tag_release` | governance | Create Git tag: `deploy-<client>-<env>-v<version>` | - |
| `notify_n8n` | notify | Trigger n8n webhook with deployment summary | - |

**Governance Policies:**
- Protect the `main` and `release/*` branches
- Require Architecture Review Board approval for merges
- Enforce presence of ADRs for new roles/modules
- Block merges on test failures

### n8n Automation Hooks

| Trigger | Workflow | Action |
|---------|----------|--------|
| Deployment success | `deployment_notify` | Send Slack notification, update RAGFlow KB |
| Deployment failure | `deployment_alert` | Alert team, create GitLab issue |
| ADR created | `adr_review` | Notify reviewers, schedule review meeting |
| Backup completed | `backup_notify` | Log to governance DB, verify backup integrity |
| Security alert | `security_incident` | Escalate to security team, log to SIEM |

### ADR Framework

**Storage**: Store ADRs in `infra/adr/` as `ADR-<###>-<short-title>.md`

**Template:**
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

**Enforcement**: CI job `check_adrs` enforces an ADR for every new role or major change

### Deployment Verification

**Central verify playbook**: `tests/verify.yml` imports test tasks from each role

**Role-level assertions:**
- **GeoServer**: `uri` module checks HTTP 200 on `/geoserver/web`
- **PostGIS**: `postgresql_query` verifies required tables/schema
- **Keycloak**: REST API calls confirm realm and user existence
- **Docker**: `docker_container` facts ensure containers are running
- **Molecule scenarios** (optional) for isolated role testing

### SE Deployment Workflow

**Step 1: Pre-flight**
```bash
# Check system requirements
./scripts/preflight_check.sh

# Review client requirements
cat group_vars/<client_id>.yml
```

**Step 2: Bootstrap**
```bash
# Run bootstrap script
./bootstrap.sh <client_id> <environment>
```

**Step 3: Deploy**
```bash
# Deploy full stack
ansible-playbook deploy.yml -i inventory/<client_id>_<env>.yml

# Or deploy specific roles
ansible-playbook deploy.yml -i inventory/<client_id>_<env>.yml --tags geoserver,postgres
```

**Step 4: Verify**
```bash
# Run verification tests
ansible-playbook tests/verify.yml -i inventory/<client_id>_<env>.yml
```

**Step 5: Handover**
- Review deployment summary report
- Verify all services are healthy
- Update client documentation
- Schedule follow-up review

### Rollback Procedures

**Tag-based rollback:**
```bash
# List available versions
git tag -l "deploy-<client>-<env>-*"

# Rollback to specific version
git checkout deploy-<client>-<env>-v1.2.3
ansible-playbook deploy.yml -i inventory/<client_id>_<env>.yml
```

**Backup-based rollback:**
```bash
# List available backups
./scripts/list_backups.sh <client_id>

# Restore from backup
ansible-playbook playbooks/restore.yml -i inventory/<client_id>_<env>.yml \
  -e "backup_date=2025-12-15"
```

### Monitoring & Alerting

**Metrics collected:**
- System metrics (CPU, memory, disk, network)
- Application metrics (response time, error rate, throughput)
- Database metrics (connections, query time, replication lag)
- GeoServer metrics (WMS/WFS requests, layer count)
- Keycloak metrics (login attempts, active sessions)

**Alert thresholds:**
- High CPU: >80% for 5 minutes
- High memory: >90% for 5 minutes
- Disk space low: <10% free
- Service down: 3 consecutive health check failures
- High error rate: >5% for 5 minutes
- SSL expiring: <30 days

### Security Hardening

**Applied by `security` role:**
- CIS benchmark compliance
- Firewall configuration (UFW/firewalld)
- SSH hardening (key-based auth, disable root login)
- fail2ban for intrusion prevention
- Automatic security updates
- Audit logging (auditd)
- SELinux/AppArmor enforcement
- SSL/TLS configuration (TLS 1.3 only)

### Backup Strategy

**Backup schedule:**
- PostgreSQL: Daily full + hourly incremental
- GeoServer data: Weekly full
- Keycloak realm: Daily
- Application configs: Daily
- Docker volumes: Weekly
- System configs: Daily

**Retention policy:**
- Local: 30 days
- Remote (S3/Azure): 90 days
- Compliance archives: 7 years (if required)

**Backup verification:**
- Automated restore test: Weekly
- Checksum verification: Daily
- Backup size monitoring: Daily

### Performance Testing with JMeter

**Test Plans:**
```
tests/performance/
├── api_load_test.jmx
├── geoserver_wms_test.jmx
├── geoserver_wfs_test.jmx
├── keycloak_auth_test.jmx
├── frontend_load_test.jmx
└── full_stack_test.jmx
```

**Test Scenarios:**

| Test Plan | Target | Scenario | Users | Duration |
{{ ... }}
|-----------|--------|----------|-------|----------|
| `api_load_test.jmx` | Backend API | CRUD operations on layers | 100-1000 | 30 min |
| `geoserver_wms_test.jmx` | GeoServer WMS | GetMap requests (various sizes) | 50-500 | 20 min |
| `geoserver_wfs_test.jmx` | GeoServer WFS | GetFeature requests | 50-300 | 20 min |
| `keycloak_auth_test.jmx` | Keycloak | Login/logout flows | 100-500 | 15 min |
| `frontend_load_test.jmx` | Frontend | Page loads, interactions | 200-1000 | 30 min |
| `full_stack_test.jmx` | All services | End-to-end user journeys | 100-500 | 60 min |

**Acceptance Criteria:**
- Average response time: <500ms for API, <200ms for WMS/WFS
- 95th percentile: <1000ms for API, <500ms for WMS/WFS
- Error rate: <1%
- Throughput: >100 req/sec for API, >50 req/sec for GeoServer
- System CPU: <80% under load
- System memory: <85% under load

### Documentation Deliverables

**For Solutions Engineers:**
- Quick-start guide
- Deployment checklist
- Troubleshooting FAQ
- Client customization guide
- Video walkthrough
- Performance testing guide

**For Operations:**
- Operator runbook
- Maintenance procedures
- Backup/restore procedures
- Disaster recovery plan
- Monitoring guide
- Performance baseline reports

**For Developers:**
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

| Column Name | Label Used | Purpose |
|-------------|------------|---------|
| Backlog | `backlog` | Placeholder for untriaged issues |
| User Story Review | `user-story-review` | PR open for `/docs/user-stories/*.md` |
| Fixing US Review Comments | `fix-us-comments` | PO or reviewers requested changes to user story |
| Design Review | `design-review` | PR open for `/designs/README.md` |
| Fixing Design Review Comments | `fix-design-comments` | UX or reviewers requested changes to Figma or README |
| Dev Review | `dev-review` | PR open for `/src/plugins/` |
| Fixing Code Review Comments | `fix-code-comments` | Dev or CTO requested changes during code review |
| Ready for QA | `ready-for-qa` | Dev complete â€” QA issue opened |
| QA In Progress | `qa-in-progress` | QA actively testing |
| Bug Fixing | `bug-fixing` | Bugs confirmed and assigned to Developer |
| QA Retest | `qa-retest` | QA verifying fixed bugs |
| QA Passed | `qa-passed` | All bugs resolved â€” QA passed |
| Ready for Release | `ready-for-release` | Approved for deployment |
| Done | `done` | Released to production |

### Roles & Responsibilities

| Role | Person | Responsibilities |
|------|--------|------------------|
| Product Owner | Hajar | User story creation, acceptance criteria |
| Solution Engineer | Meslmany | First review, feasibility assessment |
| Chief Architect | Xamek | Technical standards, architecture review |
| Senior Developer | Mounir | Code review, design review, spec validation |
| AI Developer | Marawan | Automation scripts, CI/CD integration |
| CTO | Amr | Final approval, technical sign-off |
| UX Designer | Menna | Figma designs, design system |
| Developers | Omar, Basem, Khadra, Hassan, Samy | Implementation, bug fixes |
| QA Engineer | TBD | Test planning, execution, bug reporting |

### Step 1: PO Creates User Story Document

**Branch**: `story/plugin-xyz` → `main`  
**File**: `/docs/user-stories/plugin-xyz.md`  
**Reviewers**: Solution Engineer, Senior Developer, Architect  
**Board Column**: `User Story Review`

**n8n Actions:**
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

**n8n Actions:**
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

**n8n Actions:**
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

**QA Workflow:**
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

**n8n Actions:**
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

**Release Workflow:**
- CTO (Amr) reviews QA results and approves release
- Release manager creates release branch
- Deployment to staging → production

**n8n Actions:**
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

| Script | Purpose | Exit Code on Failure |
|--------|---------|---------------------|
| `scripts/validate-user-story.sh` | Check US doc has required sections | 1 |
| `scripts/validate-figma-design.sh` | Verify Figma links, Chakra mapping | 2 |
| `scripts/check-test-coverage.sh` | Ensure unit test coverage â‰¥ 80% | 3 |
| `scripts/validate-us-coverage.sh` | Match implementation to user story | 4 |
| `scripts/validate-figma-coverage.sh` | Match UI components to Figma | 5 |
| `scripts/check-paved-roads.sh` | Verify coding standards compliance | 6 |
| `scripts/provision-qa-env.sh` | Create isolated QA environment | 7 |
| `scripts/cleanup-qa-env.sh` | Remove QA environment after release | 8 |
| `scripts/create-release.sh` | Generate release branch and notes | 9 |

**Integration**: All scripts integrated into GitLab CI pipeline (`.gitlab-ci.yml`)  
**Reporting**: Validation failures logged to `/logs/validation-failures/`

---

**Document Status:** ✅ Ready for Execution  
**Approval Required:** ARB, Chief Architect (Xamek)  
**Next Review:** Weekly during execution  
**Questions/Feedback:** Contact Xamek, Alaa (IaC), or Marawan (Automation)
