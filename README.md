# Anime Recommender System
<img width="860" height="484" alt="image" src="https://github.com/user-attachments/assets/42834738-18bd-474a-a64c-b9e4becbbd0a" />

Um sistema de recomendação é um tipo de modelo de inteligência artificial projetado para prever preferências e sugerir itens relevantes aos usuários com base em seu comportamento, histórico ou características semelhantes a outros usuários. Ele atua como um filtro inteligente em meio ao excesso de informações, ajudando pessoas a descobrirem produtos, músicas, filmes, cursos, ou qualquer conteúdo de interesse de forma personalizada.

# Descrição do Projeto
O objetivo do projeto é construir um sistema de recomendação de animes, usando LLMs. O foco do projeto consiste em obter uma lista de animes para outros animes semelhantes, por padrão o webapp retorna três recomendações.

## Steps
1. Setup do projeto
2. Obter Dados
3. Criar Data Ingestion
4. Criar e Construir Pipeline para as seguintews etapas:  carregador dados, processar e transformar, criar vectordb, aplicar embedding, guardar embedding dentro do database
5. Deploy no Amazon EC2
6. Monitorar com Grafana
7. Obter recomendações

## Requirements
- Python. Python is an interpreted, high-level and general-purpose programming language.
- AWS Accout Free Tier
- Grafana Account Free Tier

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
Run the app.py file

## Authors
Cllpsy

## License
This project is licensed under the MIT License.
