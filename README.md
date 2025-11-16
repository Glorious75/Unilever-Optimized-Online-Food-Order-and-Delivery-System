# Unilever-Optimized-Online-Food-Order-and-Delivery-System
Comprehensive Business Analysis portfolio project detailing the full life cycle for the Optimized Online Food Order and Delivery System (CODS).

# 📌 **Project Overview**
Unilever, one of the world’s largest FMCG companies with approximately 1,500 employees spread across 12 floors in the UK office, faces serious inefficiencies in its internal canteen operations. Employees waste **30–35 minutes daily** queueing for lunch, leading to productivity loss and dissatisfaction.

This project provides a **complete digital transformation solution** a web‑based Canteen Ordering & Delivery System. The solution enables pre‑ordering meals before 11 AM, desk delivery, payroll deductions, and automated inventory management.

# 🏢 **Current State Analysis**
### 🔍 Key Pain Points
- 60‑minute lunch cycle → reduces productivity
- 30–35 minutes spent queueing for food
- Limited seating in canteen (150 seats × 2)
- Food options often run out
- High food waste due to poor forecasting
- No online ordering; demand unpredictable
- Long elevator wait times

Employees eat for only **10–15 minutes** but lose **1 hour** each day.

# 🌟 **Future State Vision**
A digital platform that provides:
- Real‑time daily menu
- Online meal pre‑ordering (cut‑off 11 AM)
- Desk delivery by a meal deliverer
- Inventory summary for canteen staff
- Menu management for canteen team
- Payroll integration for salary deductions
- Feedback module for continuous improvement

# 👥 **Stakeholder Identification**
**Primary Stakeholders**
- Employees (end users)
- Menu Manager (canteen staff)
- Canteen Manager / Order Processor
- Meal Deliverers
- Payroll Department
- Chef / Kitchen Team

**Secondary Stakeholders**
- HR Department
- IT Support Team
- Finance Team
- Facilities / Admin
- Senior Management
- Business Analyst
- Project Manager
- QA/Testers

# 📊 **Stakeholder Analysis Matrix**
| Stakeholder | Interest | Influence | Justification |
|------------|----------|-----------|---------------|
| Employees | High | Medium | Primary system users; adoption required |
| Menu Manager | High | High | Manages menu & availability |
| Canteen Manager | High | High | Oversees prep & fulfilment |
| Meal Deliverer | Medium | Low | Last‑mile order handling |
| Chef/Kitchen Staff | High | Medium | Needs accurate daily demand |
| Payroll Dept | Medium | High | Handles deductions accurately |
| HR | Medium | Medium | Employee satisfaction impact |
| IT | High | High | Supports deployment, integration |
| Finance | Medium | High | Budget approval & ROI |
| Senior Management | High | High | Strategic decision‑making |
| BA | High | Medium | Requirement elicitation |
| PM | High | High | Project delivery |
| QA/Testers | Medium | Medium | Ensures quality |

# 💼 **Business Case**

## 📝 **A. Problem Statement**
Employees waste significant productive time due to long queues, limited seating, and unpredictable food availability.

## 🚀 **B. Proposed Solution**
A web‑based system enabling:
- Pre‑ordering before 11 AM
- Desk delivery
- Digital menu updates
- Inventory forecasting
- Feedback submission
- Payroll‑linked billing

## 📈 **C. Expected Benefits**
### **Quantitative Benefits**
- Reduce lunch time from **60 → 20 minutes**
- Save ~40 minutes × 1500 employees daily
- Significant productivity gains
- 35–50% reduction in food waste

### **Qualitative Benefits**
- Better employee experience
- Higher food availability
- Reduced congestion
- Better planning for chefs

## 💰 **Financial Impact Analysis and Estimated Costs**

| Cost Category | Estimated Cost (GBP) | Description |
|---------------|----------------------|-------------|
| System Development | £85,000 | End-to-end software build including frontend, backend, database, and integrations |
| Maintenance & Support | £12,000 / year | Ongoing updates, bug fixes, and technical support |
| Payroll Integration | £8,000 | API integration with existing payroll system |
| Training & Change Management | £5,000 | Training employees, canteen staff, and support teams |
| Infrastructure/Hosting | £3,000 / year | Cloud hosting, security, and server

## 🛠️ **E. Implementation Plan**

| Phase | Duration | Key Activities | Deliverables |
|-------|----------|----------------|--------------|
| **Phase 1: Discovery & Planning** | 4 Weeks | Requirements gathering, technical architecture design, UI/UX wireframes, development environment setup | Finalized requirements document, technical specification, UI/UX mockups, project plan |
| **Phase 2: Development & Testing** | 8 Weeks | Backend & database development, frontend UI implementation, API integration, unit & integration testing | Functional test environment, ordering module, menu management module, integration test reports |
| **Phase 3: Pilot Program** | 4 Weeks | Limited launch to one floor/department, collect feedback, refine system, staff training | Pilot launch report, enhanced system version, delivery process training |
| **Phase 4: Full Rollout & Closure** | 4 Weeks | Company-wide rollout, change management, training, documentation handover, project closure | Full system deployment, training materials, user manuals, project closure report |
| **Phase 5: Post-Implementation Support & Optimization** | 6 Weeks | System monitoring, bug fixes, user support, performance optimization, feature enhancements, usage analytics review | Stabilized system, optimization report, support model, enhancement backlog |

## ⚠️ **F. Risks & Mitigation**

A detailed assessment of major risks, their impact level, and mitigation strategies.

| **Risk** | **Impact** | **Mitigation Strategy** |
|----------|------------|--------------------------|
| System Downtime or Performance Failure | High | Conduct load and stress testing; implement server redundancy; enable real-time monitoring and alerts. |
| Data Security Breach | High | Implement data encryption, secure authentication, access controls, GDPR-compliant policies, and regular security audits. |
| Integration Issues with Payroll | High | Early involvement of Payroll & IT teams; parallel testing before go‑live; create fallback reconciliation procedures. |
| Delivery Delays | Medium | Implement delivery route optimization; assign backup deliverers; real-time tracking for escalations. |
| Incorrect Payroll Deductions | High | Automated calculation checks; monthly reconciliation; exception reporting. |
| Wrong or Missing Orders | Medium | Introduce order confirmation screens; enforce canteen-side QA checks; require delivery confirmation on closure. |
| Inaccurate Menu or Order Data | Medium | Establish validation checks; approval workflow for menu updates; audit logs for changes. |
| Staff Resistance to Change | Medium | Conduct awareness campaigns, hands‑on training, and phased adoption with user support. |
| Scope Creep | High | Implement strict change-control procedures; freeze requirements post‑signoff; maintain a prioritised backlog. |
| Budget Overruns | High | Maintain 10–15% contingency; milestone-based tracking; weekly financial reviews. |
| Vendor Reliability Issues | High | Conduct vendor due diligence; define SLAs and penalties; maintain alternative vendor options. |
| Low Return on Investment (ROI) | Medium | Increase user adoption through training; continuous improvement post-launch; monitor usage metrics. |
| Maintenance & Support Costs | Medium | Negotiate clear SLAs; define maintenance responsibilities; implement cost caps. |

## 🛑 Top 5 Critical Risks – Narrative Summary

### **1. System Downtime or Performance Failure (Score: 15)**
This risk poses operational disruption during peak ordering hours. Downtime may block employees from placing orders before 11AM, directly affecting the business case. High-impact mitigation requires redundancy, auto-scaling servers, and proactive monitoring.

### **2. Payroll Integration Failure (Score: 15)**
Integration errors may cause salary deduction conflicts, leading to employee dissatisfaction and financial inaccuracies. Early IT–Payroll collaboration and rigorous parallel testing are essential.

### **3. Scope Creep (Score: 15)**
Stakeholders may request additional features mid-development, affecting timelines and cost. Strict change-control processes, backlog prioritization, and PM enforcement are required.

### **4. Budget Overruns (Score: 15)**
Unexpected complexities or extended timelines may increase total project cost. A contingency budget (10–15%), milestone monitoring, and weekly financial reviews mitigate this.

### **5. Staff Resistance to Change (Score: 12)**
Employee adoption is critical for ROI. Low adoption reduces efficiency gains. Mitigation: strong change management, training, early communication, and support resources.

