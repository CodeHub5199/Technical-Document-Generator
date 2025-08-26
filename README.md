# Technical-Document-Generator

A powerful AI-powered Streamlit application that automatically generates comprehensive technical documentation for code changes. Leveraging CrewAI agents, this tool analyzes differences between original and modified code to produce professional Word documents with detailed explanations.

**📋 Project Overview**
The Technical Document Generator transforms code changes into well-structured technical documentation. It's designed for developers, technical writers, and teams who need to maintain clear records of code modifications with minimal effort.

**Primary Features:**
- AI-Powered Analysis: Utilizes CrewAI with Llama-3.3-70B model for intelligent code change analysis
- Professional Documentation: Generates Microsoft Word documents with proper formatting
- Context-Aware Processing: Extracts relevant code sections for focused analysis
- User Story Integration: Connects code changes to user requirements and stories
- Customizable Instructions: Accepts additional context for tailored documentation
- Streamlit Interface: User-friendly web application accessible to technical and non-technical users

**🚀 Installation and Setup**

**Prerequisites**
- Python 3.8 or higher
- Groq API account (for LLM access)
- Git

**Installation Steps**
1. Clone the repository
 - git clone https://github.com/CodeHub5199/Technical-Document-Generator.git
 - cd Technical-Document-Generator

2. Create a virtual environment (recommended)
 - python -m venv venv
 - source venv/bin/activate  # On Windows: venv\Scripts\activate

3. Install dependencies
 - pip install -r requirements.txt

4. Set up environment variables
 - Create a .env file in the root directory:
 - GROQ_API_KEY=your_groq_api_key_here

5. Run the application
 - streamlit run app.py

**Required Python Packages**
The application requires the following packages (included in requirements.txt):
- streamlit
- crewai
- python-docx
- python-dotenv
- langchain

**💻 Usage Guidelines**
Basic Usage
1. Start the application by running streamlit run app.py
2. Fill in user story details (name and description)
3. Provide additional context in the instructions section (optional but recommended)
4. Upload original code file (if available)
5. Paste the modified code in the text area
6. Click "Explain Code Changes" to generate documentation
7. Download the Word document with the analysis

**Example**
Suppose you've modified a function to improve performance:
1. User Story Name: "Optimize data processing performance"
2. User Story Description: "Reduce processing time for large datasets by implementing caching."
3. Additional Instructions: "Focus on memory vs performance tradeoffs and thread safety considerations"
4. Upload original data_processor.py
5. Paste the optimized function code
6. Generate and download the analysis

The resulting document will include:
1. User story context
2. Technical explanation of changes
3. Performance impact analysis
4. Implementation details
5. Potential side effects

**Advanced Features**
- Code Chunking: Automatically handles large files by splitting them into manageable chunks
- Smart Context Extraction: Identifies relevant parts of the original code for comparison
- Custom Formatting: Generates professionally formatted Word documents with proper headings
- Adaptive Analysis: Incorporates additional instructions for targeted documentation

**Areas for Contribution**
- Additional LLM provider integrations
- Support for more programming languages
- Enhanced document templates and formatting options
- Test suite development
- UI/UX improvements
- Documentation translations

**Acknowledgments**
- Built with Streamlit
- Powered by CrewAI
- LLM services provided by Groq
- Documentation generation with python-docx

**Screenshots**

<img width="959" height="445" alt="1" src="https://github.com/user-attachments/assets/f263997a-0191-4618-b84f-dd2fb85e9426" />
<img width="959" height="502" alt="6" src="https://github.com/user-attachments/assets/99300be0-2fde-4af7-a4f9-89d2e583bec4" />
<img width="959" height="505" alt="5" src="https://github.com/user-attachments/assets/e88feeb2-be00-4186-ae8e-5c630d76db68" />
<img width="956" height="445" alt="4" src="https://github.com/user-attachments/assets/94801b17-c0da-4adb-981c-49401662a1a7" />
<img width="957" height="443" alt="3" src="https://github.com/user-attachments/assets/614392ba-ce3a-4f5b-8c7f-dcfd0da5e140" />
<img width="959" height="445" alt="2" src="https://github.com/user-attachments/assets/ae6f05db-7bb7-4376-b9cf-15b6e64ffc0d" />
