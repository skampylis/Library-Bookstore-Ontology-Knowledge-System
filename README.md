# **Library Bookstore Ontology Knowledge System**

## **📚 Description**

Ontology in **RDFS** & **OWL** for a library–bookstore chain featuring hierarchies, constraints, logical relationships, and SPARQL usage. Includes an extension with **Reasoning** (HermiT) for inconsistency detection, functional properties, and automatic object classification.

---

### 🧠 **Key Features**

* **Ontology with RDFS (Phase 1)**:

  * Definition of 42 classes (e.g., `Book`, `Client`, `Club`) and 53 properties (`BookAuthor`, `ScheduleTime`, etc.)
  * Design of hierarchies and relationships among entities.

* **Extension with OWL (Phase 2)**:

  * Use of **Protégé** and **TopBraid Composer** for advanced modeling.
  * Implementation of:

    * **Logical conditions** (`unionOf`, `intersectionOf`)
    * **Restrictions** (necessary/sufficient)
    * **Symmetric**, **transitive**, and **functional** properties

* **SPARQL Queries**:

  * Information retrieval examples such as:
    📖 *“Which books has a specific customer borrowed?”*

* **Reasoning & Inconsistency Handling**:

  * Use of **HermiT Reasoner** for:

    * Detection of artificial inconsistencies
    * Automatic object classification
    * Model correctness validation

---

### ⚙️ **Technologies**

* **Protégé**, **TopBraid Composer**
* **RDFS**, **OWL**, **SPARQL**
* **HermiT Reasoner**

---

### 📝 **Notes**

* **Educational Context**: Ideal for familiarization with semantic web, ontology modeling, and reasoning.
* **Files**: Includes a report with **screenshots**, **logical explanations**, and **test inconsistencies**.

---

**🏷️ Tags**: `Ontology`, `RDFS`, `OWL`, `SPARQL`, `Reasoning`, `Semantic Web`
**🔧 Open for Contributions**: Suggestions, improvements, and extensions via *Pull Requests* or *Issues* are welcome.

*"An ontological model for a network of libraries/bookstores with emphasis on semantic representation and analysis."* 🧩📖💡
