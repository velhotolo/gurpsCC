# 🎲 GURPS Character Creator (`gurpsCC`)

A dedicated desktop character creator for the **GURPS 4th Edition** roleplaying game system.

---

## 📖 Overview

While established character tools exist for GURPS, I wanted a project that combined an exciting domain problem with hands-on practice in modern **Java** desktop architecture. 

Drawing from nearly three decades of experience as a tabletop Game Master, I designed `gurpsCC` to streamline character generation while staying true to 4th Edition rules and calculations. The core pipeline manages attributes, point accounting, and trait modifiers, ultimately stamping the final character data directly onto the official PDF character sheet using **Apache PDFBox**.

The project is currently built as a standalone desktop client using **JavaFX**, with potential plans for a web-based iteration down the line.

---

## 🛠 Tech Stack

* **Language:** Java (JDK 17+)
* **GUI Toolkit:** [JavaFX](https://openjfx.io/)
* **Document Processing:** [Apache PDFBox](https://pdfbox.apache.org/)
* **Build Tool:** Maven / Gradle

---

## ✨ Key Features & Architecture

* **Automated Point Accounting:** Real-time tracking of character point totals, campaign power levels, and sub-pools.
* **Native PDF Stamping:** Uses PDFBox to inject calculated stats, skills, and advantages directly into form fields or precise coordinate layers of official GURPS sheets.
* **Desktop-first UX:** Responsive UI designed with JavaFX for local character management.

---

## 🗺️ Development Roadmap

- [ ] Open Character (`.json` / native save parser)
- [ ] Save Character state
- [ ] Advantages & Perks cost calculation engine
- [ ] Disadvantages & Quirks cost calculation engine
- [ ] Skill types, difficulty tiers, and point progression
- [ ] Comprehensive Points Summary dashboard
- [ ] Language proficiency tiers & costs
- [ ] Cultural Familiarities workflow & costs
- [ ] Swing & Thrust damage lookup table / progression
- [ ] Undo / Redo history stack
- [ ] Application "About" view & license info
- [ ] Complete technical documentation

---

## 🚀 Getting Started

### Prerequisites

* Java Development Kit (JDK) 17 or higher
* Maven or Gradle installed

### Running Locally

```bash
# Clone the repository
git clone [https://github.com/your-username/gurpsCC.git](https://github.com/your-username/gurpsCC.git)
cd gurpsCC

# Run with Maven
mvn clean javafx:run

# Or run with Gradle
./gradlew run
