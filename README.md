# RexSci-An AI-Driven Research Assistant



## Overview

This AI-powered research assistant system leverages multiple specialized agents to facilitate various research tasks such as hypothesis generation, data analysis, visualization, and report writing. By integrating LangChain, OpenAI's GPT models, and LangGraph, the system coordinates complex research workflows, employing diverse AI architectures for maximum efficiency and accuracy.

## Key Features

- Hypothesis generation and validation
- Data processing and analysis
- Visualization creation
- Web search and information retrieval
- Code generation and execution
- Report writing
- Quality review and revision
- **Diverse Architectural Integration**: 
  - Supervisor agents for overseeing the analysis process
  - Chain-of-thought reasoning for complex problem-solving
  - Critic agents for quality assurance and error checking
- **Innovative Note Taker Agent**: 
  - Continuously records the current state of the project
  - Provides a more efficient alternative to transmitting complete historical information
  - Enhances the system's ability to maintain context and continuity across different analysis stages
- **Adaptive Workflow**: Dynamically adjusts its analysis approach based on the data and task at hand


## Main Components

- `hypothesis_agent`: Generates research hypotheses
- `process_agent`: Supervises the entire research process
- `visualization_agent`: Creates data visualizations
- `code_agent`: Writes data analysis code
- `searcher_agent`: Conducts literature and web searches
- `report_agent`: Writes research reports
- `quality_review_agent`: Performs quality reviews
- `note_agent`: Records the research process

## Workflow

The system uses LangGraph to create a state graph that manages the entire research process. The workflow includes the following steps:

1. Hypothesis generation
2. Human choice (continue or regenerate hypothesis)
3. Processing (including data analysis, visualization, search, and report writing)
4. Quality review
5. Revision as needed

