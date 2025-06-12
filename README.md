# 🛍️ Chatbot Assistente de Compras com RAG (LangChain + Pinecone + Gemini)

Este projeto demonstra como construir um robusto Chatbot Assistente de Compras com Inteligência Artificial, utilizando a técnica de RAG (Retrieval-Augmented Generation) — ideal para catálogos de produtos no varejo e e-commerce.

Ao contrário de chatbots genéricos, este assistente é alimentado com os dados reais da sua loja, permitindo gerar respostas precisas, relevantes e personalizadas com base nas informações do seu próprio catálogo de produtos.


---

## 💡 O que você vai aprender

- Como construir um pipeline RAG profissional
- Como importar dados de produtos do MySQL e indexá-los no Pinecone
- Como usar o LangChain com o Google Gemini 1.5 Flash para gerar respostas contextuais
- Como criar uma interface de chatbot com o Streamlit

---

## 📁 Tecnologias Utilizadas

| Ferramenta        | Finalidade                                |
|--------------------|--------------------------------------------|
| **MySQL**          | Base de dados com informações dos produtos |
| **Pinecone**       | Armazenamento vetorial (vector store)      |
| **LangChain**      | Orquestração do pipeline RAG               |
| **Google Gemini**  | Modelo de linguagem (LLM) da Google        |
| **Streamlit**      | Interface web do chatbot                   |

---

## 🚀 Funcionalidades

- 🔍 Geração aumentada por recuperação (RAG) para perguntas sobre produtos
- 🛒 Integração com banco de dados MySQL da sua loja
- 📚 Criação de embeddings e busca vetorial com Pinecone
- 💬 Interface de chatbot em tempo real com Streamlit
- ⚡ Respostas rápidas e inteligentes com Gemini 1.5 Flash

---

## ⚙️ Como executar

1. **Clone o repositório**  
   ```bash
   git clone https://github.com/seu-usuario/chatbot-assistente-compras.git
   cd chatbot-assistente-compras
