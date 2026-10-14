## 🧠 الخريطة الذهنية لمسؤوليات الفريق (Team Synergy Matrix)

يوضح الرسم البياني التالي توزيع الأدوار والمسؤوليات بين أعضاء الفريق لضمان التكامل التام أمام لجنة التحكيم[span_1](start_span)[span_1](end_span):

`mermaid
graph TD
    SUP[🎓 Academic Supervisor<br/><b>Eng. Ahmed Abd Elhafez</b>] --> AI
    SUP --> DEV
    SUP --> QA
    subgraph 🧠 Core AI Engine
        AI[<b>Lead AI/ML Engineer</b><br/>Ahmed Sherif]
    end
    subgraph 💻 System Engineering
        DEV1[<b>Senior Backend Engineer</b><br/>Abd Elrahman Esmat]
        DEV2[<b>Lead Frontend Engineer</b><br/>Jana Elshemy]
    end
    subgraph 🛡️ Quality & Delivery
        QA1[<b>Lead SQA Engineer</b><br/>Hana Alaa]
        QA2[<b>Project Manager</b><br/>Ahmed Omar]
    end

🎯 البطاقات الاحترافية للأدوار (Role Cards)
1️⃣ Hana Alaa – Lead Software Quality Assurance (SQA) & System Architecture
 * اللقب الوظيفي: قائد جودة البرمجيات ومهندس معمارية النظام.
 * مجال التركيز: QA Strategy, Test Case Design, API & Integration Validation, System KPIs Tracking.
 * المهام الرئيسية:
   * تصميم وتوثيق خطة الاختبار الشاملة (Software Test Plan - STP) واستراتيجية اختبارات الـ QA.
   * تصميم حالات الاختبار (Test Cases & Test Suites) لضمان تغطية النظام بالكامل (Test Coverage = 100%).
   * إجراء التحقق من واجهات البرمجة (API Validation & Integration Testing) لربط الـ Backend بفرز الذكاء الاصطناعي.
   * قياس ومتابعة مؤشرات أداء الجودة (System Quality KPIs) مثل Pass Rate و Defect Removal Efficiency.
 * المخرجات الأساسية (Core Deliverables):
   * Software_Test_Plan.md
   * Test_Cases_and_Execution_Report.xlsx
   * API_Validation_Postman_Collection.json
2️⃣ Ahmed Omar – Project Manager & Scrum Master
 * اللقب الوظيفي: مدير المشروع ومسؤول التخطيط (Project Planner).
 * مجال التركيز: Agile Management, WBS, Timeline, Risk Management.
 * المهام الرئيسية:
   * بناء هيكل تجزئة العمل (Work Breakdown Structure - WBS) وتحديد المراحل الرئيسية (Milestones).
   * متابعة الجدول الزمني للمشروع وتحديد المواعيد النهائية (Deadlines & Deliverables).
   * إعداد خطة إدارة المخاطر وتسهيل التواصل اليومي والتنسيق بين أعضاء الفريق.
 * المخرجات الأساسية (Core Deliverables):
   * PROJECT_PHASES_AND_TOOLS.md
   * TIMELINE_AND_DELIVERABLES.md
   * Gantt_Chart_and_Sprint_Backlog
3️⃣ Ahmed Sherif – Lead AI / ML Engineer
 * اللقب الوظيفي: مهندس الذكاء الاصطناعي وتعلم الآلة.
 * مجال التركيز: NLP Models, Bug Categorization, Severity/Priority Prediction, Duplicate Detection.
 * المهام الرئيسية:
   * جمع وتجهيز معالجة البيانات النصية للعيوب البرمجية (Dataset Preprocessing & Cleaning).
   * تدريب وبناء نماذج معالجة اللغات الطبيعية (NLP Models) للتنبؤ بدرجة أولوية وخطورة الباجات تلقائياً.
   * تطوير خوارزمية كشف العيوب المكررة (Duplicate Bug Detection Algorithm).
   * تحسين دقة النموذج لتلبية مؤشرات أداء الذكاء الاصطناعي (AI KPIs ≥ 80% Classification Accuracy).
 * المخرجات الأساسية (Core Deliverables):
   * AI_Triage_Engine_Model.pkl
   * Duplicate_Detection_Pipeline.py
   * AI_Performance_Evaluation_Report.pdf
4️⃣ Abd Elrahman Esmat – Senior Backend Engineer & Database Architect
 * اللقب الوظيفي: مطور الخوادم وقواعد البيانات.
 * مجال التركيز: RESTful APIs, Database Design, System Security, AI Model Integration.
 * المهام الرئيسية:
   * تصميم قواعد البيانات الهيكلية لتخزين العيوب، التقارير، وحسابات المستخدمين (Database Schema Design).
   * بناء وتطوير واجهات البرمجة التطبيقية (RESTful APIs) لنظام الإبلاغ عن الأخطاء وتتبعها.
   * دمج محرك الذكاء الاصطناعي (AI Engine) مع نظام الـ Backend لضمان سرعة الاستجابة.
   * تطبيق صلاحيات المستخدمين والأدوار (Authentication & Role-Based Access Control - RBAC).
 * المخرجات الأساسية (Core Deliverables):
   * Backend_Core_Services_API
   * Database_ERD_and_Migration_Scripts
   * Swagger_API_Documentation
5️⃣ Jana Elshemy – Lead Frontend Engineer & UX Specialist
* اللقب الوظيفي: مطورة واجهات المستخدم وتجربة المستخدم* مجال التركيز: Dashboard UI, Data Visualization, Responsive Design, User-Centric Workflows.
 * المهام الرئيسية:
   * تصميم وتطوير لوحة التحكم التفاعلية (Interactive QA & Triage Dashboard).
   * بناء واجهات سهلة الاستخدام للإبلاغ عن الأخطاء وتتبع حالة التذاكر (Tickets Workflow).
   * تقديم التوصيات المقترحة من الذكاء الاصطناعي (AI Suggestions) بشكل واضح ومبسط للـ QA والـ Developer.
   * الربط السلس مع الـ Backend APIs وضمان استجابة الشاشات لكافة الأجهزة (Responsive UI).
 * المخرجات الأساسية (Core Deliverables):
   * QA_Dashboard_UI_Application
   * Figma_Design_System_and_Prototypes
📊 ثالثاً: مصفوفة المسؤوليات (RACI Matrix)
يوضح الجدول التالي توزيع المهام طبقاً لمعيار RACI العالمي:
(R: Responsible التنفيذي | A: Accountable المسؤول المباشر | C: Consulted المستشار | I: المطلع)
| مرحلة / مهمة العمل (Project Phase / Task) | Hana Alaa (SQA) | Ahmed Omar (PM) | Ahmed Sherif (AI) | Abd Elrahman (Backend) | Jana Elshemy (Frontend) |
|---|---|---|---|---|---|
| Requirements & Project Charter | C | A / R | C | C | C |
| AI Model Training & Optimization | C | I | A / R | C | I |
| Database Architecture & APIs | C | I | C | A / R | C |
| Frontend UI/UX & Dashboard | C | I | I | C | A / R |
| Software Test Plan & Test Execution | A / R | I | C | C | C |
| AI Triage & Integration Testing | A / R | I | R | R | R |
| Final Project Delivery & Pitch | R | A / R | R | R | R |
📌 رابعاً: نقاط إبداعية للعرض أمام لجنة التحكيم (Jury Pitch Tips)
 * الربط والتكامل (Traceability): إظهار أن كل عضو بالمهام المحددة له يساهم مباشرة في تحقيق الـ KPIs الموضوعة للمشروع بدون أي تداخل أو إهدار للوقت.
 * الروح الاحترافية (Enterprise Standards): استخدام معيار RACI Matrix والـ Role Cards يعطي انطباعاً بأن الفريق يعمل وفق أعلى معايير إدارة المشاريع البرمجية المتبعة في الشركات العالمية.
