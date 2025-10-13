# Sistema de Recomendação de Animes

![Sistema de Recomendação de Animes](https://github.com/user-attachments/assets/42834738-18bd-474a-a64c-b9e4becbbd0a)

## Stack Tecnológica
**Grafana Cloud** • **MiniKube** • **Chroma DB** • **LangChain**

## Descubra Animes do Seu Interesse

Um sistema de recomendação é um modelo de inteligência artificial que prevê suas preferências e sugere conteúdos relevantes com base no seu comportamento, histórico ou similaridades com outros usuários. Funciona como um filtro inteligente que te ajuda a descobrir animes, filmes, músicas e outros conteúdos de maneira personalizada, eliminando o excesso de informações.

## Sobre Este Projeto

Vamos construir juntos um sistema de recomendação de animes que utiliza o modelo **[llama-3.1-8b-instant](https://console.groq.com/docs/model/llama-3.1-8b-instant)** através da API do **[Groq](https://console.groq.com/home)**. O sistema irá recomendar animes semelhantes ao que você escolher, retornando três sugestões personalizadas. Ao final, implantaremos a aplicação na nuvem **[Amazon EC2](https://aws.amazon.com/pt/ec2/)** e monitoraremos seu desempenho com **[Grafana](https://grafana.com/)**.

## Roteiro de Desenvolvimento

Siga estes passos para implementar o sistema:

1. **Configuração do Ambiente** - Prepare a base do projeto
2. **Coleta de Dados** - Obtenha informações sobre os animes
3. **Processamento de Dados** - Estruture as informações coletadas
4. **Pipeline de Recomendação** - Implemente as etapas de:
   - Carregamento de dados
   - Processamento e transformação
   - Criação do banco vetorial
   - Aplicação de embeddings
   - Armazenamento no database
5. **Deploy na Nuvem** - Implante no Amazon EC2
6. **Monitoramento** - Configure o Grafana
7. **Teste as Recomendações** - Execute e valide o sistema

## Pré-requisitos

- **Python** | Versão 3.11.9
- **Conta AWS** | Camada gratuita
- **Conta Grafana** | Camada gratuita

### Pacotes Necessários

Instale estes pacotes no Python antes de executar o código:

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
