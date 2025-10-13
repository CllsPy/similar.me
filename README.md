# Anime Recommender System
<img width="860" height="484" alt="image" src="https://github.com/user-attachments/assets/42834738-18bd-474a-a64c-b9e4becbbd0a" />

### Tech Stack

![Grafana](https://img.shields.io/badge/Grafana%20Cloud-%23F46800?style=for-the-badge&logo=grafana&logoColor=white)
![MiniKube](https://img.shields.io/badge/MiniKube-%23326ce5?style=for-the-badge&logo=kubernetes&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-%2300A67E?style=for-the-badge&logo=databricks&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-%23006B8F?style=for-the-badge&logo=openai&logoColor=white)

Um sistema de recomendação é um tipo de modelo de inteligência artificial projetado para prever preferências e sugerir itens relevantes aos usuários com base em seu comportamento, histórico ou características semelhantes a outros usuários. Ele atua como um filtro inteligente em meio ao excesso de informações, ajudando pessoas a descobrirem produtos, músicas, filmes, cursos, ou qualquer conteúdo de interesse de forma personalizada.

# Descrição do Projeto
O objetivo do projeto é construir um sistema de recomendação de animes, o algoritmo de recomendação terá como motor o [llama-3.1-8b-instant](https://console.groq.com/docs/model/llama-3.1-8b-instant), através da api do [Groq](https://console.groq.com/home). O foco do projeto consiste em obter uma lista de animes para outros animes semelhantes, por padrão o webapp retorna três recomendações. Finalizado, o projeto será enviado a núvem [(EC2)](https://aws.amazon.com/pt/ec2/) e monitorado via [Grafana](https://grafana.com/).

## Steps
1. Setup do projeto
2. Obter Dados
3. Criar Data Ingestion
4. Criar e Construir Pipeline para as seguintews etapas:  carregador dados, processar e transformar, criar vectordb, aplicar embedding, guardar embedding dentro do database
5. Deploy no Amazon EC2
6. Monitorar com Grafana
7. Obter recomendações

## Requirements
- Python | 3.11.9
- AWS Accout | Free Tier
- Grafana Account | Free Tier

### Packages
Install the following packages in Python prior to running the code.

```python
langchain
langchain-community
langchain-groq
chromadb
pandas
python-dotenv
sentence-transformers
langchain-huggingface
streamlit
```
## Launch
1. Fork this repo
2. Create a mew env
3. Run: Pip install -e .
4. Run: streamlit run app/app.py

## Authors
[Cllpsy](https://github.com/CllsPy)

## License
This project is licensed under the MIT License.
