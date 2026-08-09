# OSINT & Digital Forensics Investigation

> **Open-Source Intelligence techniques and tools for digital crime investigations**

![Cybersecurity](https://img.shields.io/badge/Domain-Cybersecurity-red)
![OSINT](https://img.shields.io/badge/Focus-OSINT-blue)
![Digital Forensics](https://img.shields.io/badge/Focus-Digital%20Forensics-purple)
![Maltego](https://img.shields.io/badge/Tool-Maltego-orange)
![Shodan](https://img.shields.io/badge/Tool-Shodan-black)

## 📌 Overview

This project explores the use of **Open-Source Intelligence (OSINT)** techniques and tools within **digital crime and forensic investigations**.

The project evaluates how publicly available information can be collected, analysed, and correlated to support investigative decision-making. It examines several OSINT approaches and tools, with particular focus on **Maltego** for graphical link analysis and **Shodan** for internet-connected device discovery.

The practical investigation demonstrates how **Maltego** can be used to begin with a single entity or identifier and progressively map relationships between publicly available digital entities.

The project also considers the benefits, limitations, ethical concerns, and operational challenges associated with using OSINT during digital investigations.

---

## 🎯 Objectives

The main objectives of this project were to:

* Examine the role of OSINT in digital crime investigations.
* Evaluate the effectiveness of selected OSINT tools.
* Investigate how publicly available information can support digital investigations.
* Compare the capabilities and limitations of **Maltego** and **Shodan**.
* Demonstrate an OSINT investigation workflow using Maltego.
* Explore entity and relationship mapping during an investigation.
* Identify potential digital connections between online entities.
* Consider ethical, privacy, and data-access limitations associated with OSINT.
* Evaluate how OSINT can support investigative decision-making.

---

## 🧠 What is OSINT?

**Open-Source Intelligence (OSINT)** involves the systematic collection and analysis of information that is publicly available from sources such as:

* Websites
* Social media platforms
* Search engines
* Public databases
* Online records
* Technical infrastructure
* Publicly accessible repositories

Within digital investigations, OSINT can help investigators identify relationships, online activity, digital infrastructure, and other information relevant to an investigation.

However, information being publicly accessible does not necessarily mean that it is unrestricted, reliable, or appropriate to use without consideration of legal and ethical requirements.

This project therefore considers both the **investigative value and potential risks of OSINT**.

---

## 🛠️ Tools & Technologies

### Maltego

**Maltego** was selected as the primary investigation tool because of its graphical link-analysis capabilities.

The project explores how Maltego can be used to:

* Create investigation graphs.
* Represent individuals and other entities.
* Run transforms against entities.
* Discover relationships between entities.
* Map aliases and online identities.
* Investigate publicly available online profiles.
* Visualise complex relationships.

Maltego was particularly useful because relationships can be represented visually, allowing investigators to expand an initial lead into potentially connected entities.

### Shodan

**Shodan** was evaluated as a complementary OSINT tool for discovering internet-connected devices and systems.

The project examined capabilities including:

* Device discovery.
* Internet-facing infrastructure analysis.
* Port-based searches.
* Organisation-based searches.
* Network exposure monitoring.

The project also identified limitations such as potentially outdated information, false positives, and the fact that Shodan primarily provides technical metadata rather than the deeper relationship mapping available through Maltego.

### Additional OSINT Techniques

The research also considers:

* Search-engine intelligence
* Google Dorks
* Social-media intelligence
* Public-record research
* Website analysis
* GitHub research
* Entity correlation
* Digital infrastructure analysis

---

## 🔬 Methodology

The project used a combination of **qualitative research and technical evaluation** of selected OSINT tools.

The investigation methodology focused on evaluating tools according to their:

1. **Usability**
2. **Functionality**
3. **Data collection capabilities**
4. **Relationship analysis**
5. **Investigation usefulness**
6. **Limitations and potential risks**

The overall investigation process can be represented as:

```text
Initial Investigation Lead
          │
          ▼
   Tool Selection
          │
          ▼
   Maltego Configuration
          │
          ▼
    Create New Graph
          │
          ▼
     Add Entity
          │
          ▼
   Run Transforms
          │
          ▼
   Collect Results
          │
          ▼
 Relationship Mapping
          │
          ▼
Analysis & Verification
          │
          ▼
 Investigation Report
```

The report identifies three broad stages within the practical workflow:

* **Configuration**
* **Data collection and analysis**
* **Analysis and verification**

---

## 🕵️ Practical Investigation

The practical component used **Maltego** to investigate an alias and demonstrate how a single entity can be expanded into a wider network of potentially related digital entities.

The investigation followed a structured process:

### 1. Configure the Investigation

Maltego was configured with the required plugins/transforms for the investigation.

### 2. Create a New Graph

A new Maltego graph was created to act as the investigation workspace.

### 3. Add an Entity

A person entity was selected from the entity palette and added to the investigation graph.

### 4. Enter the Investigation Identifier

The selected alias was entered into the person entity.

### 5. Run Transforms

Available transforms were used to search for potentially related information.

### 6. Analyse Relationships

The resulting entities were represented visually within the Maltego graph.

### 7. Investigate Online Presence

The project examined potential connections to online platforms and repositories, including GitHub and Instagram.

### 8. Interpret the Results

The resulting relationships were analysed to determine how effectively Maltego could support the investigation.

The practical report documents this workflow through screenshots of the Maltego interface, entity selection, transforms, graph creation, and resulting mappings.

---

## 📊 Maltego vs Shodan

| Feature                       | Maltego                             | Shodan                              |
| ----------------------------- | ----------------------------------- | ----------------------------------- |
| Primary purpose               | Graphical link analysis             | Internet-connected device discovery |
| Relationship mapping          | ✅ Strong                            | ⚠️ Limited                          |
| Entity visualisation          | ✅ Yes                               | ❌ Limited                           |
| Infrastructure discovery      | ✅ Supported                         | ✅ Strong                            |
| Social/online entity analysis | ✅ Supported through data sources    | ⚠️ Limited                          |
| Graph-based investigations    | ✅ Yes                               | ❌ No                                |
| Simple searches               | ⚠️ Requires learning                | ✅ Yes                               |
| Data-source dependency        | ✅ Yes                               | ✅ Yes                               |
| Investigation complexity      | Can become resource-intensive       | Generally simpler                   |
| Main strength                 | Connecting and visualising entities | Discovering exposed infrastructure  |

The project identified several advantages and limitations for each tool. Maltego provides graphical link analysis and automated transforms but has a steeper learning curve and depends on available data sources. Shodan provides relatively straightforward infrastructure discovery but focuses more heavily on technical metadata and can produce outdated or potentially false-positive results.

---

## 📈 Key Findings

The investigation demonstrated that Maltego can act as a **link-analysis platform for OSINT investigations**, allowing an investigator to begin with an individual lead and expand the investigation through related entities.

Key observations included:

* Graph-based analysis can make complex relationships easier to interpret.
* Automated transforms can accelerate information discovery.
* Multiple OSINT sources can provide a broader investigative picture.
* Entity mapping can help identify relationships between online identities and other digital entities.
* The effectiveness of results depends heavily on the availability and quality of underlying data sources.
* OSINT tools require appropriate training to be used effectively.
* Publicly available information can still present privacy and ethical concerns.
* Results should be analysed and verified rather than automatically treated as evidence.

The project concluded that Maltego was particularly suitable for the demonstrated investigation because of its ability to visually map relationships between entities.

---

## ⚠️ Ethical & Legal Considerations

OSINT investigations must be conducted responsibly.

Information being publicly accessible does not automatically mean that it should be collected, stored, or used without restrictions.

Important considerations include:

* Privacy
* Data protection
* Legal authority
* Accuracy of information
* False positives
* Source reliability
* Evidence integrity
* Responsible disclosure
* Avoiding unnecessary collection of personal information

This project recognises the dual-use nature of OSINT: the same publicly available information that can support investigators can potentially be abused by malicious actors.

For this reason, this repository should **not contain unnecessary personal information, private credentials, sensitive identifiers, or unrestricted copies of investigative data**.

---

## 🔐 Responsible Use

This project is intended for:

* Cybersecurity education
* OSINT research
* Digital-forensics learning
* Security research
* Academic demonstration
* Investigative methodology development

It should **not** be used to:

* Harass individuals.
* Dox individuals.
* Obtain unauthorised access to accounts or systems.
* Circumvent access controls.
* Collect sensitive personal information unnecessarily.
* Conduct unauthorised reconnaissance against systems.
* Facilitate malicious activity.

Only information that is lawfully accessible and appropriate for the investigation should be collected and analysed.

---

## 📁 Repository Structure

```text
.
├── README.md
├── report/
│   └── OSINT_Digital_Forensics_Report.pdf
│
├── methodology/
│   ├── methodology-diagram.png
│   └── investigation-workflow.png
│
├── screenshots/
│   ├── maltego-main-screen.png
│   ├── entity-search.png
│   ├── transform-selection.png
│   └── investigation-graph.png
│
├── findings/
│   └── investigation-summary.md
│
├── references/
│   └── references.md
│
├── LICENSE
└── .gitignore
```

> **Note:** Update the filenames above to match the actual files included in the repository.

---

## 📷 Screenshots

Screenshots from the practical investigation can be placed in the `screenshots/` directory.

Example:

```markdown
![Maltego Investigation Graph](screenshots/investigation-graph.png)
```

Recommended screenshots include:

* Maltego main interface
* Entity palette
* New investigation graph
* Person entity
* Transform selection
* Transform results
* Relationship/alias mapping
* Final investigation graph

**Before publishing screenshots, remove or anonymise personal information that does not need to be publicly displayed.**

---

## 📚 Research Areas

This project covers several areas of cybersecurity and digital investigation:

```text
Cybersecurity
│
├── Open-Source Intelligence
│   ├── Search Intelligence
│   ├── Social Media Intelligence
│   ├── Public Records
│   └── Digital Footprinting
│
├── Digital Forensics
│   ├── Evidence Analysis
│   ├── Investigation Methodology
│   └── Evidence Verification
│
├── Threat Intelligence
│   ├── Entity Analysis
│   ├── Infrastructure Discovery
│   └── Relationship Mapping
│
└── Investigative Technology
    ├── Maltego
    ├── Shodan
    ├── Google Dorks
    └── Social Media Analysis
```

---

## 💡 Skills Demonstrated

This project demonstrates practical and research-based skills in:

* 🔎 OSINT investigation
* 🕵️ Digital investigation methodology
* 🧩 Link and relationship analysis
* 🌐 Digital footprint analysis
* 📊 Data interpretation
* 🔗 Entity correlation
* 🛡️ Cybersecurity research
* 📚 Academic research
* ⚖️ Ethical considerations in cybersecurity
* 🧠 Critical evaluation of investigative tools

---

## 📖 References

The project was informed by research and sources including:

* Cybervie — *What is Maltego? | How to use it for Information Gathering*
* Cyber Defense Magazine — *The Shodan as The Scariest Search Engine of Today*
* SANS Institute — *What is OSINT (Open-Source Intelligence?)*
* Authentic8 — *OSINT for law enforcement and crime prevention*
* Barracuda — *Understanding the importance of OSINT in modern research*
* Imperva — *Open-Source Intelligence (OSINT) | Techniques & Tools*
* Larsen, O.H., Ngo, H.Q. and Le-Khac, N.-A. (2023) — research on law-enforcement use of OSINT techniques
* Pai U., Y. and K., K.P. (2021) — *Open Source Intelligence and its Applications in Next Generation Cyber Security*
* Vaughan, A. (2024) — *The Role of OSINT in Criminal Investigations*
* Wells, D. and Gibson, H. (2017) — *OSINT from a UK perspective*

The complete bibliography is available in the accompanying project report.

---

## 🚀 Future Improvements

Potential future development could include:

* Expanding the comparison to additional OSINT platforms.
* Developing a repeatable OSINT investigation framework.
* Adding automated data-processing components.
* Introducing structured evidence-recording procedures.
* Evaluating additional social-media intelligence techniques.
* Comparing different approaches to entity resolution.
* Investigating machine-learning and AI applications within OSINT.
* Developing improved methods for validating OSINT findings.

The original research also identifies the potential for machine learning, deep learning, and AI to support future OSINT and digital-forensics applications.

---

## ⚖️ Disclaimer

This repository is intended for **educational, research, and cybersecurity portfolio purposes**.

All investigation techniques should be performed only against information and systems that you are legally authorised to investigate.

Any examples, screenshots, identities, or investigative data published in this repository should be appropriately anonymised where necessary.

The author does not endorse the misuse of OSINT techniques for harassment, unauthorised access, privacy violations, or other unlawful activity.

---

## 👤 Author

**[FAISAL SALEEM]**



**Topics:** `cybersecurity` `osint` `digital-forensics` `maltego` `shodan` `threat-intelligence` `cyber-investigation` `information-security` `open-source-intelligence`
