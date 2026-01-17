# myProjects

A mix of public and private projects ranging from backend systems, data engineering, PLC simulation, to frontend web apps.

---

## Public Projects

- [MERN_stack](https://github.com/cell32/MERN_stack) – MERN stack exploration and deployment basics.
- [ETL_noCode_Approach_SSIS](https://github.com/cell32/ETL_noCode_Approach_SSIS) – ETL pipeline using SSIS with no-code transformations.
- [ETL_CodedApproach_noSSIS](https://github.com/cell32/ETL_CodedApproach_noSSIS) – ETL logic using Python and MySQL for data transformations.
- [2024-RT-107-Roberto](https://github.com/cell32/2024-RT-107-Roberto) – Miscellaneous project/code work from early 2024.
- [Gravitational-Pull-master](https://github.com/cell32/Gravitational-Pull-master) – C# physics-based simulation.
- [boilerplate-npm](https://github.com/cell32/boilerplate-npm) – Forked boilerplate used in FreeCodeCamp's curriculum.
- [ProjectTests](https://github.com/cell32/ProjectTests) – Sample test projects across different stacks.
- [Fibonacci-Asynchronus](https://github.com/cell32/Fibonacci-Asynchronus) – C# async Fibonacci sequence generator.
- [JUnit-testing-on-ArrayList-JAVA](https://github.com/cell32/JUnit-testing-on-ArrayList-JAVA) – Basic JUnit testing examples.

---

## Private Projects (Titles Only)

> These are available by request or in demo format only.

- **AETHER Project** - AI-Enhanced Turbulence-Based Hypersonic & Elusive Response

  **Key Advances:**
  
  *Military-Grade Realism:*
  - Launch → Boost → Glide phases
  - Plasma wake effects >20km altitude
  - Sensor-type specific detection
  
  *Scientific Validation:*
  - Quadratic rocket ascent (step^1.5)
  - Speed-dependent confidence scaling
  - Kalman-filtered tracking

- **Clinical Support Tool** - Exploring both rules-based and AI-driven engines to generate diagnosis suggestions from symptom descriptions. The backend (Ollama) runs on Windows, while the frontend runs in a Python venv on WSL due to LLM integration constraints. I'll be posting this experimental tool soon for people to try out — just for fun!

  Rules-based engines are deterministic, auditable, and reliable for well-known, common diagnosis patterns.
  
  *AI models (LLMs) can handle ambiguity and edge cases but:*
  - They may hallucinate or return non-validated diagnoses.
  - They are not medically certified.
  - They can introduce a level of uncertainty that, in a medical support tool, needs careful handling.
  
  *So, the best architecture (especially for clinical tools) is often:*
  - Primary layer: rules_engine.py
    - Fast, Reliable and Fully explainable
  - Fallback layer: ai_engine.py
    - If no match is found via rules, call the AI.

  Upgraded and fully functional clinical decision support tool using rules-based/ai-based suggested treatment(s). After some research, I fine-tuned some of the inference parameters for the intended purpose of the ai_engine to achieve the following:
  - Reduced hallucinations, ensuring deterministic, evidence-based outputs.
  - Restricts suggestions to the most medically plausible options.
  - Guarantees reproducibility for audits.

- **ai_agents_suite** - A growing suite of modular AI agents built to automate complex tasks — from customer support to intelligent trading.

  *Current Modules:*
  - Support Ticket Generator: Extracts structured data (customer, issue type, urgency, etc.) from natural language messages using local LLMs (Ollama) and stores them in MongoDB via a FastAPI backend.
  - Smart Trading Agent (coming soon): AI-powered trading assistant capable of analyzing market trends, simulating strategies, and making informed buy/sell decisions.

- **ufos** – Fun project to record and view UFO sightings. Built with Python + lightweight DB.
- **air-bnb-test** – Basic Airbnb data test project using Python.
- **shipwrech** – Data project analyzing shipwreck records.
- **FastAPI_Modbus-PLC-Simulation** – Real-time PLC simulation with FastAPI + frontend dashboard + CSV logging.
- **air-bnb-app** – Airbnb-inspired Python web app.
- **skynet_bank** – Full-stack Per Scholas capstone project simulating a banking system.
- **airbnb-jupyter** – Data analysis of Airbnb data using Jupyter notebooks.
- **maintenance_management** – Preventive maintenance tracking system in Python.
- **git-test** – Full-stack exploration project using React.
- **Mock_Website** – Frontend HTML/CSS/JS/TS web project (in progress).
- **Gravitational-Pull** – C# and XAML-based physics project on WPF.

---

## Notes

- Feel free to explore the **public repos** and reach out if you're interested in a demo of any **private** one.
- Some private projects are still under development or used for learning/experiments.
