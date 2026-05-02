# 📊 QTC Project Portfolio Monitoring System

A structured framework for daily monitoring and analysis of project portfolio status, focusing on QTC (Quote → Tooling → Commercialization) milestones to enhance execution visibility and decision-making.

---

## 🧠 Background

In project-driven organizations, tracking progress across multiple milestones (RFQ, Quotation, Nomination, SOP/EOP) is often fragmented, manual, and reactive.

This project aims to establish a standardized and scalable monitoring approach to improve transparency, risk control, and execution efficiency.

---

## 🎯 Objectives

* Establish a **daily tracking mechanism** for project portfolios
* Provide **end-to-end visibility** across QTC stages
* Identify **schedule deviations and execution risks early**
* Enable **data-driven decision-making**

---

## 🔍 Scope

The monitoring framework focuses on key milestones in the QTC lifecycle:

* RFQ (Request for Quotation)
* Quotation Submission
* Nomination
* SOP (Start of Production)
* EOP (End of Production)

---

## ⚙️ Methodology

### 1. Data Collection

* Source: Internal project tracking files (Excel / PPT reports)
* Key fields:

  * Project Title
  * QTC milestone dates (planned vs. actual)
  * Status indicators

---

### 2. Data Processing

* Project matching based on **Project Title**
* Standardization of milestone formats
* Parsing of combined fields (e.g., SOP / EOP)
* Handling of missing or unmatched records

---

### 3. Daily Monitoring Logic

The system performs daily updates and checks:

* 📅 Status refresh
* 🔄 Comparison with previous snapshot
* ⚠️ Risk detection:

  * Delayed milestones
  * Missing updates
  * Timeline inconsistencies

---

### 4. Output

* Structured Excel reports
* Highlighted exceptions:

  * ❗ Unmatched projects
  * ⚠️ Delayed milestones
  * 🔵 Newly added entries

---

## 📈 Key Insights

* Project pipeline health
* Stage distribution across QTC lifecycle
* Delay patterns and bottlenecks
* Execution efficiency trends

---

## 📁 Project Structure (Planned)

QTC-Monitoring/
│
├── data/        # Raw input files
├── output/      # Processed reports
├── scripts/     # Data processing scripts (future)
├── config/      # Mapping rules & configurations
└── README.md

---

## 🚀 Roadmap

* [ ] Automate data extraction from PPT
* [ ] Develop Python-based processing scripts
* [ ] Build visualization dashboards (Power BI / Python)
* [ ] Enable historical trend analysis
* [ ] Implement alert mechanism for critical risks

---

## 🧩 Future Enhancements

* Predictive analytics for delay risks
* Resource allocation optimization
* Integration with ERP / PLM systems

---

## 🤝 Use Cases

* Project review meetings
* Weekly / monthly reporting
* Management dashboards
* Operational risk monitoring

---

## 📄 License

This repository is intended for methodology sharing and demonstration purposes.
