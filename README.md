# Unilever-Optimized-Online-Food-Order-and-Delivery-System
Comprehensive Business Analysis portfolio project detailing the full life cycle for the Optimized Online Food Order and Delivery System (CODS).

# 📌 **Project Overview**
Unilever PLC, one of the world’s largest FMCG companies with approximately 1,500 employees spread across 12 floors in the UK office, faces serious inefficiencies in its internal canteen operations. Employees waste **30–35 minutes daily** queueing for lunch, leading to productivity loss and dissatisfaction.

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

## 🛑 Top 5 Critical Risks

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

## 📊 G.   Monitoring & Evaluation 

The project’s success is continuously measured against **SMART objectives** and **Key Performance Indicators (KPIs)** to ensure efficiency, user satisfaction, and operational excellence.

| KPI | Measurement | Frequency | Target | Responsible Party |
|-----|------------|----------|--------|-----------------|
| Average Lunch Time | Weekly Survey / Spot Check | Weekly | < 25 minutes | Business Analyst |
| Food Waste Percentage | Inventory Report | Daily / Weekly | 60% Reduction | Canteen Management |
| User Adoption Rate | System Log-in / Order Count | Daily | 90% of eligible employees | System Administrator |
| Customer Complaint Volume | Complaint Log | Daily | < 1% of total orders | Canteen Support Team |
| Order Fulfillment Accuracy | Weekly Audit | Weekly | 99% accuracy (correct dish, correct location) | Canteen Management |

**Note:** KPIs are monitored regularly to ensure the project aligns with business goals and maintains high operational standards.

## ✅ **F. Recommendation**
The Online Ordering and Delivery System is a strategic investment that aligns with modern workplace efficiency standards and directly responds to employee demand for better service. 
By implementing this system, Unilever Plc will improve ROI, save costs, boost employee morale, and reclaim valuable productive time.

# 🗂️ **RACI Matrix: Roles & Responsibilities**

A **RACI (Responsible, Accountable, Consulted, Informed) Matrix** clarifies roles and responsibilities for key project activities and stakeholders.

| Activity | Unilever Senior Management | Finance Department | HR Department | IT/Technology Department | Canteen Management / Menu Manager | Kitchen Chef & Staff | Delivery Personnel | Facilities Management | Employees / Canteen Users |
|----------|----------------------------|------------------|---------------|--------------------------|---------------------------------|-------------------|-----------------|----------------------|---------------------------|
| Project Funding & Approval | A | C | C | I | I | I | I | I | I |
| Defining/Refining Business Requirements | C | I | C | C | A | C | I | C | R |
| System Development & Deployment | I | I | I | A, R | C | I | I | I | I |
| Payroll/Payment Integration & Testing | I | C | A | R | I | I | I | I | I |
| Creating & Updating Daily Menu | I | I | I | C | A, R | C | I | I | C |
| Order Processing & Inventory | I | I | I | I | A, R | C | C | I | I |
| Training: Canteen Staff Workflow | I | I | C | C | A | R | R | I | I |
| Training: Employee System Use | I | I | A | C | C | I | I | I | R |
| Placing Online Orders | I | I | I | I | I | I | I | I | A, R |
| Delivering Orders to Workstations | I | I | I | I | C | I | A, R | C | I |
| Monitoring Productivity & ROI Metrics | A | R | C | I | C | I | I | I | I |
| Defining Delivery Logistics & Flow | I | I | I | I | C | I | C | A, R | I

# 🧩 System Features to be developed 

## ⭐ Functional Requirements

| Feature Area               | Key Features |
|----------------------------|--------------|
| **Employee Features**      | - View updated daily menu<br>- Add/edit dishes before checkout<br>- Order cut‑off at 11AM<br>- Order tracking<br>- Feedback module<br>- Salary‑deduction enrollment |
| **Canteen Features**       | - Menu updates by Menu Manager<br>- View orders by employee<br>- Automatic inventory aggregation<br>- Delivery request management<br>- Order status updates |
| **System Integrations**    | - Payroll auto‑deduction<br>- Secure login & permissions<br>- Reporting dashboards |

## 🔹 Non-Functional Requirements (NFRs)

| NFR Category               | Requirements |
|----------------------------|--------------|
| **Performance**            | - Fast response time (< 2s per action)<br>- Support up to 10,000 concurrent users<br>- Optimized database queries |
| **Availability**           | - 99.9% system uptime<br>- Scheduled maintenance during off-peak hours<br>- Real-time monitoring and alerts |
| **Scalability**            | - Horizontal & vertical scaling<br>- Cloud-based dynamic resource allocation |
| **Adaptability**           | - Easy integration with new payment gateways or delivery services<br>- Configurable menus and promotions without downtime |
| **Usability**              | - Intuitive, mobile-first UI<br>- Multi-language support<br>- Simple navigation for all users |
| **Security**               | - HTTPS encryption & secure data storage<br>- Multi-factor authentication (MFA)<br>- Regular security audits and vulnerability testing |
| **Maintainability**        | - Modular architecture for easy updates<br>- Clear developer documentation<br>- Automated testing & CI/CD pipelines |
| **Auditability**           | - Comprehensive activity and transaction logging<br>- Regulatory compliance reporting<br>- Log retention for at least 12 months |
| **Accessibility**          | - WCAG 2.1 AA compliance<br>- Screen reader & keyboard navigation support<br>- Alternative text for images |
| **Disaster Recovery**       | - Daily backups of critical data<br>- Recovery Time Objective (RTO): 4 hours<br>- Recovery Point Objective (RPO): 1 hour<br>- Redundant servers &failover mechanisms |

# 🚀 Future Process Flow using Swimlane Diagram  
The diagram below illustrates the optimized future-state process for the Unilever Online Food Order & Delivery System.  

It highlights clear responsibilities across **Employees**, **Canteen Manager**, **Menu manager**, **Chef/Kitchen**, **Delivery Team**, **System/DB** and **HR/Payroll System**,

![Unilever Online food ordering_swimlane diagram](https://github.com/user-attachments/assets/cc9e3497-ed8c-4363-b275-a0591e0a065e)

# 🧾 TO-BE Requirements Translated into User Stories

| **EPIC** | **Goal** | **User Story (ID)** | **Acceptance Criteria** |
|---|---|---:|---|
| **Epic 1: User Onboarding & Enrollment** | Enable employees to register, secure their account, and manage salary deduction enrollment | **US01:** As an Employee, I want to sign up and create a secure account. | - User can register with email/employee ID<br>- Password rules enforced (min length, complexity)<br>- Email/ID verification or confirmation notification sent |
|  |  | **US02:** As an Employee, I want to enroll in salary deduction during sign-up. | - Salary deduction option visible during signup<br>- Enrollment flag sent to payroll system/API<br>- Employee receives confirmation of enrollment |
|  |  | **US03:** As an Employee, I want to update or opt out of salary deductions. | - User can toggle deduction on/off in profile settings<br>- Payroll receives updated status within defined SLA<br>- UI shows current deduction status and last update timestamp |
| **Epic 2: Menu Management** | Maintain accurate, timely, and authorised menu content | **US04:** As a Menu Manager, I want to upload the daily menu. | - Menu upload UI available to authorised users only<br>- Uploaded menu visible to employees within expected propagation time (< 2 min)<br>- Upload errors surface clear messages |
|  |  | **US05:** As a Menu Manager, I want to update pricing. | - Price edit UI for authorised users<br>- Price updates reflect instantly to employees<br>- System logs price changes with user and timestamp |
|  |  | **US06:** As a Menu Manager, I want to edit or remove menu items. | - Manager can edit/delete items and save changes<br>- Deleted items no longer appear to employees immediately<br>- Change history/audit trail recorded |
| **Epic 3: Order Placement** | Allow employees to view menus and place orders with customization and clear cut-off rules | **US07:** As an Employee, I want to view today’s menu. | - Today's menu loads within 2s<br>- Menu shows item name, image, price, dietary info |
|  |  | **US08:** As an Employee, I want to select dishes. | - Items can be added to cart with quantity and options<br>- Cart updates totals in real time |
|  |  | **US09:** As an Employee, I want to edit or remove dishes before checkout. | - User can edit quantities/remove items from cart before checkout<br>- Totals and taxes update correctly after edits |
|  |  | **US10:** As an Employee, I want ordering to close at 11AM. | - System enforces 11:00 cut-off (timezone-aware)<br>- Attempts after cut-off are blocked with explanatory message<br>- Users receive reminders/notifications before cut-off (optional) |
| **Epic 4: Order Processing** | Enable canteen staff to receive, prioritise and manage orders and inventory | **US11:** As a Canteen Manager, I want to view all employee orders. | - Orders listed with employee, time, items, and status<br>- Filters for date, department, and status available |
|  |  | **US12:** As a Canteen Manager, I want to generate an aggregated inventory list. | - System aggregates quantities by ingredient/item for the shift/day<br>- Inventory export available (CSV/Excel/PDF) |
|  |  | **US13:** As a Canteen Manager, I want to update order status. | - Manager can set statuses (Received → Preparing → Ready → Dispatched)<br>- Status changes trigger notifications to employees and delivery staff |
| **Epic 5: Delivery** | Ensure timely, trackable delivery or pickup and clear handover for deliverers | **US14:** As Delivery Personnel, I want to view assigned orders. | - Delivery app/list auto-populates assigned orders with pickup location and time window<br>- Order details include employee contact/pickup point |
|  |  | **US15:** As Delivery Personnel, I want to mark deliveries as completed. | - Deliverer can mark order delivered with timestamp and optional proof (photo/signature)<br>- Delivery status updates visible to employee and canteen |
|  |  | **US16:** As an Employee, I want real-time delivery tracking. | - Tracking shows statuses: Preparing → Out for Delivery → Delivered<br>- Estimated time of arrival (ETA) made available where possible |
| **Epic 6: Payroll Integration** | Automate and reconcile salary deductions for ordered meals | **US17:** As Payroll Staff, I want monthly order totals. | - System produces monthly summary per employee and aggregated totals<br>- Reports exportable in payroll-ready format (CSV/Excel) |
|  |  | **US18:** As an Employee, I want automatic salary deductions. | - Orders eligible for deduction tagged correctly<br>- Monthly totals align with deduction amounts shown to employee pre-payroll run |
|  |  | **US19:** As Payroll Staff, I want reconciliation reports. | - Reconciliation report shows orders, deductions, adjustments, and exceptions<br>- Discrepancies flagged for review |
| **Epic 7: Feedback & Experience** | Capture service feedback and deliver actionable insights to improve quality | **US20:** As an Employee, I want to submit feedback. | - Feedback/rating available after delivery or pickup<br>- Confirmation message shown after submission |
|  |  | **US21:** As a Canteen Manager, I want to review feedback. | - Feedback dashboard lists ratings, comments, and trends<br>- Filters for date, meal, rating available |
| **Epic 8: System & Security** | Ensure secure access, role-based permissions, compliance, and operational performance | **US22:** As a User, I want secure login authentication. | - Login requires valid credentials and enforces password policy<br>- MFA available/required per policy<br>- Failed login attempts logged and rate-limited |
|  |  | **US23:** As an Administrator, I want role-based access control. | - Roles defined (Employee, Menu Manager, Canteen Manager, Delivery, Payroll, Admin)<br>- Permissions enforced per role; unauthorised actions blocked and logged |

# 📌 Unilever Optimizied Online Food Order & Delivery System (UOOFODS) Jira Project: Product Backlog & Agile Board

👉 ## Access the full project backlog, sprint board, and workflow tracking via the Jira Software board link below:

[https://glorianjorteah.atlassian.net/jira/software/projects/UOOFODS/boards/35/backlog](https://glorianjorteah.atlassian.net/jira/software/projects/UOOFODS/boards/35/backlog)


