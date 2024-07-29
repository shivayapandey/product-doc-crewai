# GitHub Repository Product Documentation Generator

## Overview
This project leverages AI tools to automate the process of fetching code from a GitHub repository and generating comprehensive documentation for it. The primary goal is to streamline the workflow of code review and documentation creation using state-of-the-art language models and semantic search capabilities.

## Key Features

1. **GitHub Code Search**:
   - Perform semantic searches within a specified GitHub repository.
   - Extract and analyze code files for issues and necessary corrections.

2. **Automated Documentation Generation**:
   - Use AI agents to fetch repository data and write detailed documentation.
   - Create user-friendly documentation that includes code snippets and a user guide.

3. **AI Agent Collaboration**:
   - Deploy specialized AI agents for research and writing tasks.
   - Enable agents to work collaboratively to achieve the project goals.

## Components

### GitHub Search Tool
- Initializes a tool to search and fetch code from a specified GitHub repository.
- Configured to use OpenAI's GPT-4-turbo model for semantic searches.

### AI Agents
- **Researcher**: 
  - Fetches all required data from the repository.
  - Ensures all code and documentation files are ready for further processing.
- **Writer**: 
  - Composes comprehensive documentation based on the fetched data.
  - Expert in creating detailed and user-friendly documentation.

### Task Management
- **Research Task**: 
  - Description: Fetch all necessary data from the repository.
  - Expected Output: All required files for writing documentation.
- **Writing Task**: 
  - Description: Compose detailed documentation for the repository.
  - Expected Output: Comprehensive documentation with code snippets and user guide.

### Process Execution
- Form a crew of AI agents to perform tasks sequentially.
- Execute tasks with enhanced feedback and configurations for optimal performance.

## Usage
1. **Install Dependencies**:
   ```sh
   pip install crewai
   pip install 'crewai[tools]'
   pip install langchain-community
   ```

2. **Set Environment Variables**:
   - Provide OpenAI API key and GitHub Access Token when prompted.

3. **Run the Script**:
   - The script initializes the GitHub search tool, configures AI agents, and defines tasks for fetching and documenting the repository.
   - Execute the crew of AI agents to complete the tasks and generate the documentation.

## Output
- The final output is a comprehensive documentation file (`documentation.txt`) that includes detailed descriptions, code snippets, and usage guidelines for the repository.

This project simplifies the code review and documentation process, making it easier and faster to maintain high-quality documentation for GitHub repositories.
