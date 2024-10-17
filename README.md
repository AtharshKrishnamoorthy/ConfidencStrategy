# ConfidenStrategy: AI-Driven Strategy Analysis Platform

## Demo Video

[![ConfidenStrategy Demo](https://github.com/user-attachments/assets/6175cbf5-9d6c-48b5-b148-0cfaccab279d)](https://youtu.be/_nFEyKvajJ8?si=t2GKVf45zZS3AV3m)

### Live Demo

Access the live demo of the ConfidenStrategy application:\
[ConfidenStrategy App](https://confidenstrategy.streamlit.app/)

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Core Functionality](#core-functionality)
- [Technical Details](#technical-details)
- [Output](#output)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

ConfidenStrategy offers the following cutting-edge features to revolutionize strategic planning:

1. **AI-Powered Market Analysis**: Leverages AI models to gather, analyze, and generate insights from market and competitor data.
2. **Strategic Recommendations**: Provides customized AI-driven strategies that focus on resource allocation, market entry, and competitive positioning.
3. **Interactive Visualizations**: Interactive charts and graphs provide real-time data insights for scenario planning and decision-making.
4. **Chat Assistant**: A Chatbot is integrated where users can ask questions about the strategies generated and about the listed company too.
5. **Voice Enabling Feature**: For each sections generated in the strategy and the chats  - voice feature is avalible where the chats can be turned into voice and can be downloaded too.
6. **RAG Integration**: The Company can add addtional info about their profits made and things like that to create a additional knowledge base for the agents generating strategies.
7. **Multi-Agent Collaboration**: Different AI agents analyze various facets of strategic data, ensuring comprehensive insights across multiple domains.

## Prerequisites

Before running the platform, ensure you have the following:

- Python 3.7+ installed.
- **API keys** for services such as Alpha Vantage, Finnhub, Groq, and Deepgram for market data and voice capabilities.
- Required Python libraries as mentioned in the `requirements.txt` file.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/YourGitHubUsername/ConfidenStrategy
   cd ConfidenStrategy
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Set up environment variables:

   - Create a `.env` file in the project root directory.
   - Add your API keys and configurations:
     ```plaintext
     ALPHA_VANTAGE_API_KEY=your_alpha_vantage_key
     FINNHUB_API_KEY=your_finnhub_key
     GROQ_API_KEY=your_groq_key
     DEEPGRAM_API_KEY=your_deepgram_key
     ```

## Usage

To launch the ConfidenStrategy platform:

1. Navigate to the project directory.

2. Run the Streamlit app:

   ```bash
   streamlit run ConfidenStrategy.py
   ```

3. Open your browser at `http://localhost:8501` (or the address specified in the terminal).

### Input Parameters

- **Company Stock Symbol**: Enter the stock symbol of the target company.
- **Industry Focus**: Specify the industry to refine the competitive analysis.
- **Strategic Focus**: Choose strategic areas like market expansion, product development, or cost optimization.

## Core Functionality

1. **Company and Competitor Analysis**: Analyzes the company’s financial health and market position, with a deep dive into competitor strategies.
2. **AI-Driven Market Insights**: Predicts market trends and potential growth opportunities through AI models.
3. **Strategic Planning**: Provides actionable strategies, including resource allocation, market entry tactics, and competitive advantage points.
4. **Interactive Dashboard**: Real-time visual representation of data such as market share projections, key performance indicators (KPIs), and financial metrics.
5. **Chat Assistant**: A Chatbot is integrated where users can ask questions about the strategies generated and about the listed company too.

## Technical Details

ConfidenStrategy is built with AI frameworks and Cryptographic Libraries which ensures AI integration with Security about the company details too.

1. **Multi-Agent AI Framework**: Utilizes the **Crew AI Framework**, where each AI agent specializes in a specific area of strategic planning, such as:

   - **Market Trends Analysis**
   - **Competitor Strengths/Weaknesses**
   - **Resource Allocation Optimization**

   The framework's **multi-agent collaboration** and **decision fusion** ensure accurate and comprehensive strategy generation, as seen in the flowchart where different agents handle specific strategy domains.

2. **Orchestration**: Uses **LangChain** for orchestration combining the agents with the prompts creating a chain, creating a chat Assitant.
                      **Groq** for utilizing the open sourced LLMs with greater inference - These groq LLMs (Used **LLama 3.1-70B-versatile**) are used as the LLM for the agents.

4. **Voice Capabilities**: Integration with the **Deepgram API** offers text-to-speech functionalities, enabling the users to hear the startegies generated and further it can be downloaded too.

5. **Data Integration and Market Data Retrieval**: Real-time financial and market data are gathered using **Alpha Vantage** and **Finnhub** APIs.

6. **Vector Storage and Embeddings**: For the RAG it uses -> **Document Loaders**, **Langchain Hugging Embeddings** as Embeddings, and utilizes **FAISS** as vector store to handle high-dimensional data efficiently, supporting the embedding generation and retrieval process to drive LLM-based context retrieval.

## Output

ConfidenStrategy generates an in-depth strategy report containing:

1. **Executive Summary**: Overview of strategic findings and insights.
2. **Market Analysis**: Detailed market trend and competitor analysis, including forecasts.
3. **Strategic Initiatives**: Actionable steps to improve market standing, growth, and operational efficiency.
4. **Risk Analysis**: Identifies potential risks and suggests mitigation strategies.
5. **Resource Allocation Plan**: Recommendations on financial, human, and technological resource distribution.

## Contributing

We welcome contributions to ConfidenStrategy! Here's how to get involved:

1. Fork the repository.

2. Create a new branch:

   ```bash
   git checkout -b feature-branch
   ```

3. Make your changes and commit them:

   ```bash
   git commit -m 'Added new feature'
   ```

4. Push your branch:

   ```bash
   git push origin feature-branch
   ```

## License

This project is licensed under the MIT License. See the [LICENSE.md](LICENSE.md) file for more details.

## Contact

For any inquiries, feel free to reach out to the team:

- **Email**: [atharshkrishnamoorthy@gmail.com](mailto\:atharshkrishnamoorthy@gmail.com)
- **Team Members**:
  - [Ranil Mukesh MJ](https://github.com/ranilmukesh)
  - [Sanjith M](https://github.com/Sanjith-3)
  - [Tharun Pranav M](https://github.com/TharunPranavM)
  - [Siddarth S](https://github.com/SiddharthWayne)
- **GitHub Repository**: [ConfidenStrategy](https://github.com/AtharshKrishnamoorthy/ConfidencStrategy)

