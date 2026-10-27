# GenAI Cold Outreach Email Generator

An AI-powered cold email generator built with **Python, Groq, LangChain, and Streamlit** to help service-based companies streamline business development outreach.

## Overview

The application takes a company's careers-page URL, extracts relevant job listings, and generates personalized cold emails based on the identified hiring requirements. It uses a vector database to retrieve relevant portfolio projects and incorporates matching portfolio links into each email.


### Use Case

Nike is hiring a **Purchasing Analyst** in Beaverton, Oregon, with responsibilities related to purchasing, supply chain, data management, and reporting. The role highlights skills such as Excel, pivot tables, VLOOKUPs, SAP S/4HANA Cloud, and purchase order management.

A business development executive at AtliQ, a company providing technology and data services, could use this application to identify Nike's requirements and generate a personalized cold email highlighting relevant capabilities and portfolio projects.

The application matches portfolio links to the job description using a vector database, helping create targeted outreach rather than generic sales emails.

<img width="1842" height="856" alt="image" src="https://github.com/user-attachments/assets/74965fc0-99c6-4aa6-823c-872330404f04" />


## Key Features

- **Job Listing Extraction:** Retrieves job postings from a company's careers page.
- **AI-Powered Email Generation:** Generates personalized cold outreach emails based on job descriptions.
- **Semantic Portfolio Matching:** Uses a vector database to find relevant portfolio projects.
- **Contextual Personalization:** Includes matching portfolio links to make outreach more relevant.

## Architecture

The application combines job extraction, LLM-powered email generation, and vector-based portfolio retrieval into a streamlined workflow.  
<img width="1060" height="352" alt="image" src="https://github.com/user-attachments/assets/ef92156b-3e08-4bb8-8ecd-7e833e64d276" />




## Setup and Installation

### 1. Clone the repository

```bash
git clone https://github.com/rahatmulla/cold-outreach-email-generator.git
cd cold-outreach-email-generator
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Configure the API key

Create an `app/.env` file and add your Groq API key:

```env
GROQ_API_KEY=your_groq_api_key
```

Get an API key from the [Groq Console](https://console.groq.com/keys).

### 4. Run the application

```bash
streamlit run app/main.py
```

## Technology Stack

- **Language:** Python
- **LLM Provider:** Groq
- **LLM Framework:** LangChain
- **User Interface:** Streamlit
- **Retrieval:** Vector database for portfolio matching

##
