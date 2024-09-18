# Automated Multi-Agent Research System

## Overview

The **Automated Multi-Agent Research System** is an advanced platform designed for generating comprehensive research reports. Leveraging a multi-agent architecture, this system automates the process of research report generation by integrating distinct agents with specialized roles. The project utilizes state-of-the-art technologies such as LangGraph, LangChain, and the OpenAI API to produce detailed reports in multiple formats including PDF, Markdown, and DOCX.

## Features

- **Multi-Agent Architecture**: Incorporates distinct agents to handle different aspects of the research report creation process:
  - **Researcher**: Gathers and curates research data.
  - **Writer**: Compiles the research data into a structured report.
  - **Reviewer**: Provides feedback on the draft report.
  - **Reviser**: Incorporates review feedback into the draft.
  - **Publisher**: Finalizes and publishes the report in various formats.

- **Output Formats**: Generates reports in PDF, Markdown, and DOCX formats.

- **Technologies Used**:
  - **LangGraph**: For managing and coordinating multi-agent workflows.
  - **LangChain**: To streamline data processing and interaction between agents.
  - **OpenAI API**: Provides natural language processing capabilities.

## Installation

To set up the project locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/Automated-Multi-Agent-Research-System.git
   ```

2. **Navigate to the Project Directory**:
   ```bash
   cd Automated-Multi-Agent-Research-System
   ```

3. **Create and Activate a Virtual Environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

4. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

5. **Set Up Environment Variables**: Add your API keys and other environment-specific configurations. Create a `.env` file and include necessary keys as shown in `.env.example`.

## Usage

To run the system, execute the following commands:

1. **Run the Main Script**:
   ```bash
   python main.py
   ```

2. **Configure Your Project**: Update the `ChiefEditorAgent` initialization in `main.py` with your specific parameters, such as `query`, `max_sections`, `follow_guidelines`, `model`, and `verbose`.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. **Fork the Repository** and create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```

2. **Commit Your Changes**:
   ```bash
   git commit -m "Add a new feature"
   ```

3. **Push to Your Fork**:
   ```bash
   git push origin feature/your-feature-name
   ```

4. **Create a Pull Request** on GitHub.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
