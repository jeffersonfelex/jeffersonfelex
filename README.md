## Jefferson Felex de Faria

**Cientista de dados** em Goiânia (GO). Uso Python e SQL para transformar rotinas manuais em pipelines confiáveis e dados brutos em modelos que dá para auditar.

- **Engenharia e automação de dados:** pipelines de backup/restore em PostgreSQL e Oracle Data Pump, com SFTP, agendamento, idempotência e alertas no Teams
- **Analytics de risco e auditoria:** regras em SQL, grafos de vínculos entre fornecedores e modelos com validação temporal
- **Pesquisa:** iniciação científica no Laboratório de Computação Científica (LCC) da PUC Goiás com imagens hiperespectrais SWIR e XGBoost
- **IA generativa:** agentes com Google ADK/Gemini e sistemas RAG

<p>
  <a href="https://www.linkedin.com/in/jeffersonfelexdefaria"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:felexmc22@gmail.com"><img src="https://img.shields.io/badge/E--mail-333333?style=for-the-badge&logo=gmail&logoColor=white" alt="E-mail"></a>
</p>

### Projetos em destaque

| Projeto | O que faz | Stack |
|---|---|---|
| [**hsi-swir-bacteria-xgboost**](https://github.com/jeffersonfelex/hsi-swir-bacteria-xgboost) | Classificação espectral de bactérias multirresistentes em imagens hiperespectrais SWIR (256 bandas). Validação cruzada agrupada por imagem para evitar pseudo-replicação, seleção de atributos só no treino e limitações documentadas. | Python · XGBoost · scikit-learn · Airflow |
| [**procurement-risk-analytics**](https://github.com/jeffersonfelex/procurement-risk-analytics) | Auditoria contínua de compras: 8 regras em SQL (fracionamento, conflito de interesse, empresa de fachada…), grafo de vínculos, lista única de casos priorizados e modelo de risco de fornecedor sem vazamento temporal. | SQL · pandas · networkx · scikit-learn |
| [**postgres-backup-restore-pipeline**](https://github.com/jeffersonfelex/postgres-backup-restore-pipeline) | Baixa backups de dezenas de GB via SFTP com retomada, extrai e restaura no PostgreSQL em paralelo. Modo agendado só reprocessa o que mudou; lock com heartbeat e host key fixada (TOFU). | Python · PostgreSQL · Paramiko · pytest |
| [**oracle-datapump-automation**](https://github.com/jeffersonfelex/oracle-datapump-automation) | Substitui um procedimento manual de importação Oracle por um pipeline idempotente de 8 etapas, com análise de erros `ORA-`, retenção e notificações no Teams. | Python · Oracle · SSH/SFTP · SQLite |
| [**RecruitFlow**](https://github.com/jeffersonfelex/RecruitFlow) | Plataforma de recrutamento com agentes de IA que analisam currículos, calculam compatibilidade com vagas e automatizam o contato via WhatsApp. | Google ADK · Gemini · React · Supabase · n8n |
| [**proj_rag_manu**](https://github.com/jeffersonfelex/proj_rag_manu) | Sistema RAG modular para responder perguntas sobre documentos privados: chunking, embeddings e busca vetorial. | Python · LangChain · Azure OpenAI · Pinecone |

### Ferramentas

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=flat-square)
![Apache Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
