# Anime Recommendation System

![Anime Recommendation System](https://github.com/user-attachments/assets/42834738-18bd-474a-a64c-b9e4becbbd0a)

## Tech Stack
![Grafana](https://img.shields.io/badge/Grafana%20Cloud-%23F46800?style=for-the-badge&logo=grafana&logoColor=white)
![MiniKube](https://img.shields.io/badge/MiniKube-%23326ce5?style=for-the-badge&logo=kubernetes&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-%2300A67E?style=for-the-badge&logo=databricks&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-%23006B8F?style=for-the-badge&logo=openai&logoColor=white)

## Discover Anime That Matches Your Interests

A recommendation system is an artificial intelligence model that predicts your preferences and suggests relevant content based on your behavior, history, or similarities with other users. It works as an intelligent filter that helps you discover anime, movies, music, and other content in a personalized way, reducing information overload.

## About This Project

![Diagramme sans nom](https://github.com/user-attachments/assets/e98a1e72-a0e3-4c00-8c5a-503f2f91b67b)

We will build an anime recommendation system using the **[llama-3.1-8b-instant](https://console.groq.com/docs/model/llama-3.1-8b-instant)** model through the **[Groq API](https://console.groq.com/home)**.  
The system will recommend anime similar to the one you choose, returning three personalized suggestions.  
Finally, we will deploy the application on **[Amazon EC2](https://aws.amazon.com/ec2/)** and monitor its performance with **[Grafana](https://grafana.com/)**.



## Development Roadmap

Follow these steps to implement the system:

1. **Environment Setup** - Prepare the project base  
2. **Data Collection** - Gather anime information  
3. **Data Processing** - Structure the collected data  
4. **Recommendation Pipeline** - Implement the following stages:
   - Data loading  
   - Processing and transformation  
   - Vector database creation  
   - Embedding application  
   - Database storage  
5. **Cloud Deployment** - Deploy on Amazon EC2  
6. **Monitoring** - Set up Grafana  
7. **Test Recommendations** - Run and validate the system

## Prerequisites

- **Python** | Version 3.11.9  
- **AWS Account** | Free tier  
- **Grafana Account** | Free tier  

### Required Packages

Install these Python packages before running the code:

```bash
langchain
langchain-community
langchain-groq
chromadb
pandas
python-dotenv
sentence-transformers
langchain-huggingface
streamlit
