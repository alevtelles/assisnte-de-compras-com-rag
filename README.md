# 🛍️ Assistente de Compras com RAG (LangChain + Pinecone + Gemini)

Este projeto implementa um Assistente de Compras com Inteligência Artificial, utilizando a técnica de RAG (Retrieval-Augmented Generation), voltado para catálogos de produtos no setor de varejo e e-commerce.

O assistente é alimentado com dados reais da loja, permitindo respostas precisas, relevantes e personalizadas com base no próprio catálogo de produtos.

---

## 💡 Visão Geral

- Implementação de um pipeline RAG (Retrieval-Augmented Generation) com arquitetura robusta e escalável
- Ingestão e indexação de dados de produtos a partir de um banco de dados MySQL para o Pinecone
- Integração com LangChain e o modelo Gemini 1.5 Flash, fornecendo geração de respostas contextuais com alto grau de relevância
- Interface interativa via Streamlit para demonstração do assistente em tempo real

---

## 📁 Tecnologias Utilizadas

| Ferramenta                  | Propósito                                                                 |
|----------------------------|---------------------------------------------------------------------------|
| **LangChain**              | Orquestração do pipeline RAG                                              |
| **Gemini 1.5 Flash**       | Modelo LLM para geração de linguagem natural                              |
| **Pinecone**               | Banco vetorial para indexação e busca semântica                           |
| **MySQL**                  | Fonte de dados dos produtos                                               |
| **Streamlit**              | Interface web para interação com o assistente                            |
| **Python**                 | Linguagem principal da aplicação                                          |
| **Docker** (opcional)      | Containerização do ambiente (em desenvolvimento)                         |

---

## 🚀 Execução

1. Configure as variáveis de ambiente (`.env`) com as credenciais apropriadas (Pinecone, Gemini, MySQL)
2. Execute o pipeline de ingestão de dados
3. Inicie a interface com Streamlit:

```bash
streamlit run app.py
