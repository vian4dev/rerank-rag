<div align="center">
  <a href="https://github.com/vian4dev/rerank-rag/stargazers">
    <img alt="Stargazers" src="https://img.shields.io/github/stars/vian4dev/rerank-rag?style=social">
  </a>
  
  <img alt="PRs welcome!" src="https://img.shields.io/static/v1?label=PRs&message=welcome&color=7159c1&labelColor=000000" />
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=7159c1&labelColor=000000">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/vian4dev/rerank-rag?color=%2304D361">
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/vian4dev/rerank-rag">
	
  <a href="https://github.com/vian4dev/rerank-rag/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/vian4dev/rerank-rag">
  </a>
  
  <a href="https://www.linkedin.com/in/vianadev/">
    <img alt="Made by vian4dev" src="https://img.shields.io/badge/made%20by-vian4dev-%2304D361">
  </a>
</div>

<div align="center">
  <img src="https://raw.githubusercontent.com/vian4dev/vian4dev/bfae0da7d97ab8f10a008d3fdea6f2e2181fa3ca/.github/rocketseat.svg" width="250" height="250" alt="Rocketseat">
</div>

# Rerank RAG

## ✒️ Descrição
Neste projeto, exploramos o uso do Rerank, uma etapa que reclassifica os trechos recuperados do documento do Projeto de Lei de Inteligência Artificial (PL 2338/2023), organizando-os por relevância contextual antes de serem enviados ao modelo de linguagem. Isso melhora significativamente a precisão e a utilidade das respostas geradas.

As tecnologias utilizadas incluem a Cohere API, responsável pela geração de embeddings e reranking, e um VectorDB (banco de dados vetorial) para o armazenamento e a busca eficiente dos vetores semânticos.

## 🚀 Tecnologias utilizadas
<div style="display: inline_block"><br>
  <img align="center" alt="img-html" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg">    <img align="center" alt="img-html" height="30" width="40" src="https://github.com/devicons/devicon/blob/master/icons/jupyter/jupyter-original-wordmark.svg">
</div>

## 📷 Demostração
Apresentação do esquema da aplicação.
<div align="center">
  <img src="./.github/arquitetura-rerank-rag-01.png" alt="arquitetura-rerank-rag" />
  <img src="./.github/arquitetura-rerank-rag-02.png" alt="arquitetura-rerank-rag" />
</div>

## 🔥 Instalação
Clone o repositório.
~~~
git clone git@github.com:vian4dev/rerank-rag.git
~~~
Acesse o diretório do projeto.
~~~
cd rerank-rag/
~~~
Crie o arquivo .env na raiz do diretório.
~~~
OPENAI_API_KEY=""
COHERE_API_KEY=""

⚠️ Será necessário gerar um token na OpenAI platform.
⚠️ Será necessário gerar um token na Cohere platform.
~~~
Instale as dependências.
~~~
pip install -r requirements.txt
~~~
Execute a aplicação no Jupyter Notebook ou VScode.
~~~
main.ipynb
~~~

## 📝 Licença
Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---
<div align="center"> 
 <p>Desenvolvido por - <a href="https://github.com/vian4dev">Gabriel Viana</a> 🤖</p>
 
 <a href="https://www.linkedin.com/in/vianadev" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 
</div>
