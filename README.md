### Sexto Semestre (2025-1)

# Plataforma de Treinamento de IA — Comparação e Avaliação de LLMs com Feedback Humano

## Descrição do Projeto
**Semestre:** Sexto Semestre – 2025-1  
**Empresa Parceira:** Dom Rock  
**Área de Atuação:** A Dom Rock oferece serviços ágeis de diagnóstico e análise na implementação de soluções e agentes de IA de acordo com as estratégias e demandas das áreas de negócio.  
**Professor responsável:** **José Walmir Gonçalves Duque** (P2)  
**Contato do Parceiro:** Andre F. de Almeida

---

### ![Problem Icon](https://img.shields.io/badge/-Problema-E74C3C?style=flat&logo=issue-tracking&logoColor=white)

Com a crescente adoção de modelos de linguagem (LLMs) em setores como saúde, jurídico e análise de risco, empresas como a Dom Rock enfrentam o desafio de garantir que esses modelos entreguem respostas coerentes, confiáveis e adaptadas ao seu contexto de atuação.

Entretanto, a simples integração de modelos genéricos não supre essa necessidade, visto que muitos desses LLMs apresentam limitações de veracidade, imparcialidade e naturalidade, impactando negativamente a credibilidade das análises geradas e a experiência do usuário final.

Além disso, sem mecanismos estruturados de coleta de feedback humano, torna-se inviável realizar ajustes finos nos modelos por meio de técnicas como RLHF (Reinforcement Learning with Human Feedback), o que compromete a evolução contínua dessas soluções.

---

### ![Solution Icon](https://img.shields.io/badge/-Solução-27AE60?style=flat&logo=solution&logoColor=white)

A equipe desenvolveu uma **Plataforma de Treinamento de IA**, que permite:

- Comparação entre respostas geradas por diferentes LLMs (como OpenAI, Gemini, DeepSeek, Grog).
- Avaliação das respostas com base em critérios definidos (ex: coerência, naturalidade, veracidade).
- Registro e análise de feedback humano, com uso de RLHF (Reinforcement Learning with Human Feedback).
- Interface responsiva e acessível desenvolvida com Vue.js e prototipada no Figma.
- Backend robusto em FastAPI, com Langchain e integração com banco vetorizado.


### **Imagens do Sistema**
#### **[Demonstração do projeto em execução]**

<p align="center">
  <img src="https://github.com/tsilvadev89/Portfolio/blob/API6S/img/RespostaLLMsAPI6s.jpg" alt="Interface da Plataforma" width="800" height="400">
  <br>
</p>

---

### **Link do Repositório Git**  
<a href="https://github.com/FATEC-FULLSTACK/API6" target="_blank">
  <img src="https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white&style=flat-square" alt="GitHub link">
</a>

---

### ![Tech Icon](https://img.shields.io/badge/-Tecnologias%20Utilizadas-3498DB?style=flat&logo=stackshare&logoColor=white)

- ![Vue.js](https://img.shields.io/badge/-Vue.js-42b883?logo=vue.js&logoColor=white&style=flat) **Vue.js**: Desenvolvimento da interface frontend com foco em responsividade.
- ![FastAPI](https://img.shields.io/badge/-FastAPI-009688?logo=fastapi&logoColor=white&style=flat) **FastAPI**: Backend ágil com endpoints assíncronos e integrados ao Langchain.
- ![Langchain](https://img.shields.io/badge/-Langchain-3eaf7c?logo=openai&logoColor=white&style=flat) **Langchain**: Orquestração das respostas LLMs e integração com sistemas RAG.
- ![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?logo=mongodb&logoColor=white&style=flat) **MongoDB**: Armazenamento NoSQL das avaliações e logs de uso.
- ![Figma](https://img.shields.io/badge/-Figma-F24E1E?logo=figma&logoColor=white&style=flat) **Figma**: Protótipos e validação de usabilidade.
- ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white&style=flat) **Python**: Linguagem base do backend e lógica de avaliação de feedback.

---

### ![Contribution Icon](https://img.shields.io/badge/-Contribuições%20Pessoais-F39C12?style=flat&logo=contribution&logoColor=white)

Atuei como **desenvolvedor**. Minhas principais contribuições:

- Implementei a lógica responsável pelo envio da requisição das perguntas às api's dos sistemas de inteligência artificial.
- Desenvolvi a interface pela qual as respostas dadas pelas API's são sorteadas e então selecionadas randomicamente para serem apresentadas ao usuário.
- Desenvolvi o sistema de sorteio de respostas que serão mostradas ao usuário.
- Refatorei o código de recebimento dos dados retornados das API's para otimizar a velocidade da resposta final ao usuário.
- Manutenção e Aprimoramento da lógica de recebimento dos dados das API's

---

### ![Hard Skills Icon](https://img.shields.io/badge/-Hard%20Skills-2ECC71?style=flat&logo=skillshare&logoColor=white)

- ![FastAPI](https://img.shields.io/badge/-FastAPI-009688?logo=fastapi&logoColor=white&style=flat) **FastAPI**: Estruturamento das rotas de requisição às API's e envio para o frontend. (Faço/uso com ajuda)
- ![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?logo=mongodb&logoColor=white&style=flat) **MongoDB**: Armazenamento de coleções e índices para feedback e sessões. (Faço/uso com autonomia)
- ![Langchain](https://img.shields.io/badge/-Langchain-3eaf7c?logo=openai&logoColor=white&style=flat) **Langchain**: Auxilio na estruturação dos prompts de envio e análise de respostas. (Faço/uso com ajuda)
- ![Vue.js](https://img.shields.io/badge/-Vue.js-42b883?logo=vue.js&logoColor=white&style=flat) **Vue.js**: Interface visual para utilização pelo usuário. (Faço/uso com autonomia)
- ![ChromaDB](https://img.shields.io/badge/-ChromaDB-red) **ChromaDB**: Banco de dados vetorial para armazenamento da base de dados utilizada para auxiliar as respostas por Inteligência Artificial. (Faço/uso com ajuda)
---

### ![Soft Skills Icon](https://img.shields.io/badge/-Soft%20Skills-9B59B6?style=flat&logo=meetup&logoColor=white)

- **Resolução de problemas:** Ao final da primeira entrega, foi notado que o tempo de resposta das LLM's para o usuário estava demorando demais. Então alterei nos códigos a maneira conforme os dados eram recebidos pela aplicação, o que resultou num ganho de mais de 80% de velocidade no retorno das respostas.
- **Adaptabilidade:** Com demandas por um padrão de organização diferente do qual a equipe usou ao longo do curso. Adaptei o padrão de commits do projeto. Os quais antes eram segmentados por area de atuação, para o padrão de segmentação por tarefa específica.

---

### ![Video Icon](https://img.shields.io/badge/-Vídeo%20Tutorial-FF0000?style=flat&logo=youtube&logoColor=white)

Um vídeo tutorial foi produzido para demonstrar o uso da plataforma por usuários com ou sem familiaridade técnica. [Acesse o vídeo aqui](https://www.youtube.com/watch?v=C3ySkVufNRI).

---
