# Nutrition_Agent
🧠 Nutrition Agent using IBM watsonx.ai

This notebook demonstrates how to build and use an AI-powered agent using IBM watsonx.ai and the LangGraph framework. The agent utilizes IBM’s Foundation Models to interactively respond to nutrition-related prompts.

🚀 Features
✅ Connect to IBM watsonx.ai using API credentials

✅ Define and use a ReAct agent powered by LangGraph

✅ Customize tools using the LangChain-IBM ecosystem

✅ Perform natural language interactions with the model

✅ Demonstrate memory and conversational flow in agents

🛠️ Prerequisites
Before running this notebook, make sure you have:

Python 3.11+

IBM Cloud API key (for watsonx.ai)

An active IBM Cloud account

🛠️ Tools Integrated
The agent is configured with the following tools for enhanced query capabilities:

Tool	Description
🔍 Google search	Retrieves information from the internet via Google
🦆 DuckDuckGo search	Retrieves information via DuckDuckGo engine
📚 Wikipedia search	Retrieves information from Wikipedia articles
📄 Document search - nutrition_dataset	Searches documents using vector indexing (internal dataset)
🌐 Webcrawler	Retrieves information directly from a given website

🤖 How It Works
Credentials & Token Setup
Get and store API credentials securely using getpass.

Model Initialization
Select the appropriate model ID for generation.

Agent Creation
Instantiate a LangGraph ReAct agent with selected tools.

Interaction
Use natural language to query the model through the agent pipeline.

