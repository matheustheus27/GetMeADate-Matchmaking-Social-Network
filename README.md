# Get Me A Date — Matchmaking Social Network Engine 🗓️❤️

An interactive, desktop-driven matchmaking platform engine engineered utilizing Object-Oriented Programming (OOP) paradigms. The system analyzes user behavioral profiles, personal preferences, and biographical markers to dynamically calculate compatibility and pair matching social profiles. This application was developed as the final practical project for the **Computer Programming II** course in the Computer Engineering curriculum at CEFET-MG.

---

## 👥 Authorship & Faculty

* **Professor:** Dr Luciana Campos
* **Student:** Matheus Thiago de Souza Ferreira

---

## 🛠️ Software Architecture & Directory Layout

The application architecture features strong encapsulation and package grouping patterns natively configured within the NetBeans build lifecycle environment.

```text
├── src/                          # System Source Files
│   ├── generalAccessPackage/     # Global access configurations & business routers
│   │   ├── classSubSystem/       # Domain business entities (Users, Profiles, Matches)
│   │   └── databaseSubSystem/    # Persistence abstraction and file simulation scripts
│   ├── gui/                      # Desktop Presentation Layer (Swing/AWT components)
│   ├── build.xml                 # Apache Ant modular script routine definition
│   └── manifest.mf               # Jar executable specification manifest
├── nbproject/                    # NetBeans local IDE metadata structures
│   ├── private/
│   ├── build-impl.xml
|   ├── genfiles.properties
│   ├── project.properties
|   └── project.xml
└── README.md
```
### Subsystem Breakdown:
* Presentation Layer (`gui/`): Manages interactive user interface frames, registration fields, dashboard panels, and reactive window rendering loops.
* Domain Subsystem (`classSubSystem/`): Implements the primary core logic rules of the network (e.g., matching calculation algorithms, profile validation routines, and interest category evaluation matrices).
* Storage Abstraction (`databaseSubSystem/`): Dedicated context layer simulating system persistence controls and data flow management to insulate operations from volatile runtime states.

## ⚙️ Core Technical Capabilities
* Profile Scoring Matching Engine: Programmatically scores multi-attribute profile matrices to sort and compute compatibility indexing scores between distinct active users.
* Modular Encapsulation: Strict architectural isolation across data schemas, graphical elements, and logical rules via native Java packaging definitions (`generalAccessPackage`).
* Relational Mock Persistence: Decoupled persistence controller operations making the underlying core rules completely database-agnostic.

## 🚀 Compilation & Local Execution
1. Prerequisites
Ensure you have the Java Development Kit (**JDK 8 or higher**) configured alongside an Apache Ant building environment (**bundled by default inside NetBeans IDE or IntelliJ IDEA**).

2. Loading the IDE Project Environment
  1. Launch **NetBeans IDE**.
  2. Select **File -> Open Project** from the task navigation menu.
  3. Locate and select the root directory container folder (`GetMeADate`). The IDE will automatically recognize the underlying metadata inside `nbproject/`.

3. Build & Run Execution
* Compilation: Right-click the root project folder node in the project explorer toolbar panel and select Clean and Build. This executes the `build.xml` Ant script pipelines, compiling code modules into the `build/classes/` directory target.
* Execution: Run the application directly from the editor environment canvas by clicking the Run Project button icon or typing `F6`.

## 🔧 Core Tech Stack
* **Programming Language Platform:** Java Standard Edition (Java SE)
* **Design Paradigm:** Object-Oriented Programming (OOP Architecture)
* **Build Automation Suite:** Apache Ant Compiler Infrastructure
