# 🛡️ Mapeamento de Engenharia Social com IA através da Matriz MITRE ATT&CK e filosofia clássica de Kevin Mitnick

Repositório dedicado ao desafio de projeto do **Bootcamp Bradesco - GenAI, Dados & Cyber** na plataforma DIO. Este projeto documenta a criação e os testes de um Caderno Temático no NotebookLM focado em analisar como a Inteligência Artificial Generativa industrializou ataques de Engenharia Social, mapeando essas ameaças através da matriz **MITRE ATT&CK** e integrando a filosofia clássica de **Kevin Mitnick**.

---

## 🎯 1. Contexto e Objetivos de Estudo

### Contexto
O avanço da Inteligência Artificial Generativa (GenAI) permitiu que cibercriminosos automatizassem e sofisticassem ataques de Phishing e Spear-Phishing, eliminando erros gramaticais comuns e gerando abordagens hiper-personalizadas baseadas em pegadas digitais. Para mitigar esse risco de forma tática e corporativa (alinhado às necessidades do setor bancário), este projeto une os conceitos fundamentais de engenharia social de **Kevin Mitnick** ao framework defensivo **MITRE ATT&CK**.

### Objetivos de Estudo
*   **Fundamentação Histórica:** Compreender os gatilhos psicológicos da engenharia social (*Pretexting*) baseados nas obras clássicas de Kevin Mitnick.
*   **Mapeamento Tático:** Identificar e detalhar como a IA Generativa potencializa as sub-técnicas de Acesso Inicial e Reconhecimento da matriz MITRE ATT&CK.
*   **Estratégia de Defesa:** Investigar mecanismos avançados de proteção contra quebras de alinhamento de LLMs (*Jailbreaks*) e táticas corporativas de mitigação em camadas.

---

## 📚 2. Curadoria de Fontes

Para alimentar o ecossistema de dados do NotebookLM, foi reunida uma robusta base de conhecimento composta por **41 fontes técnico-conceituais**, incluindo PDFs históricos, relatórios de ameaças globais (Threat Intelligence) e artigos científicos recentes de segurança de IA:

### 🔍 Principais Destaques do Repositório:
*   **Fundamentos Humanos:** Livros digitais *"A Arte de Enganar"* e *"A Arte de Invadir"* de Kevin Mitnick.
*   **Frameworks de Inteligência:** Documentação oficial do MITRE ATT&CK Enterprise (Tática TA0001 - Initial Access) e CAPEC.
*   **Relatórios Oficiais de Mercado:** *X-Force Threat Intelligence Index 2026 (IBM)*, Relatório Global da Kaspersky e guias oficiais da CISA e NSA.
*   **Pesquisa de Ponta em IA:** Artigos do *arXiv* abordando *Jailbreaks* em LLMs e a engenharia de defesa em camadas (como o framework *TRYLOCK*).

<details>
<summary>📂 Clique aqui para visualizar a lista completa das 41 fontes do Caderno</summary>

1. 25+ Spear Phishing Examples & How to Prevent Them [URL]
2. A Closer Look at the LAPSUS$ Data Extortion Group – Krebs on Security [URL]
3. A_Arte_de_Enganar.pdf [PDF]
4. A_Arte_de_invadir.pdf [PDF]
5. Abuse of Cloud-Native Infrastructure in Modern Phishing ... - cyfirma [URL]
6. Access Denied [URL]
7. Avoiding Social Engineering and Phishing Attacks | CISA [URL]
8. CAPEC - Common Attack Pattern Enumeration and Classification (CAPEC™) [URL]
9. Cartilha_de_Segurança_do_Cert.br.pdf [PDF]
10. Comprehensive Assessment of Jailbreak Attacks Against LLMs - arXiv [URL]
11. Daily Papers - Hugging Face [URL]
12. Decrypting credentials from SCCM site servers configured for high availability | IBM [URL]
13. Enterprise Tactics - MITRE ATT&CK® [URL]
14. Estratégias Avançadas de Acesso Inicial, Engenharia Social e Evasão de Alinhamento em Modelos de Linguagem: Uma Análise de TTPs e Defesa em Multicamadas [Markdown]
15. From LinkedIn to Tailored Attack in 30 Minutes: How AI Accelerates Target Profiling for Cybercrime [URL]
16. Guardrails for LLMs - Arize AI [URL]
17. Hive0145 back in German inboxes with Strela Stealer and a backdoor | IBM [URL]
18. How to Protect Against Evolving Phishing Attacks - National Security Agency [URL]
19. In Cyber, Differentiating Between State Actors, Criminals Is a Blur | U.S. Department of War [URL]
20. Initial Access in Cybersecurity: The Attack Stage Most Businesses Miss | Huntress [URL]
21. Initial Access, Tactic TA0001 - Enterprise | MITRE ATT&CK® [URL]
22. Initial Access, Tactic TA0108 - ICS | MITRE ATT&CK® [URL]
23. Inside Silver Fox's Den: Trustwave SpiderLabs Unmasks a Global Threat Actor [URL]
24. Jailbreak Attacks and Defenses in Large Language Models: A Beginner-Friendly Survey [URL]
25. Just a moment... [URL] (Verificação de segurança/acesso)
26. LLM Jailbreak Robustness Overview - Emergent Mind [URL]
27. MITRE ATT&CK® [URL]
28. Making Them Ask and Answer: Jailbreaking Large Language Models in Few Queries via Disguise and Reconstruction - USENIX [PDF]
29. North Korean Hackers Adopt Infostealer Spreading Tactics in Latest Campaign | InfoStealers [URL]
30. Oh non! Spear phishing campaign targets users in France using their leaked data, 160K+ victims | IBM [URL]
31. Phishing & Security Awareness Glossary [URL]
32. Phishing Guidance: Stopping the Attack Cycle at Phase One - CISA [URL]
33. Relatório global do Kaspersky Security Services.pdf [PDF]
34. Resecurity | Trinity of Chaos: The LAPSUS$, ShinyHunters, and Scattered Spider Alliance [URL]
35. Silver Fox APT Targets Public Sector via Trojanized Medical Software [URL]
36. TRYLOCK: Defense-in-Depth Against LLM Jailbreaks via Layered Preference and Representation Engineering - arXiv [PDF]
37. The History of Social Engineering [URL]
38. Tracking the Expansion of ShinyHunters-Branded SaaS Data Theft | Google Cloud Blog [URL]
39. What Is Phishing and How Can You Stop It? - Vectra AI [URL]
40. What is MITRE ATT&CK Initial Access (TA0001)? - Netscout [URL]
41. X-Force Threat Intelligence Index 2026.pdf [PDF]

</details>

---

## 🧪 3. Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

Nesta seção está documentado o processo de refinamento das interações com o NotebookLM, demonstrando o valor de prompts bem estruturados para cruzar referências comportamentais e técnicas.

### 🧪 Teste de Prompt 1: Como a IA ajuda no phishing de acordo com o MITRE?
*   **Contexto das Respostas Obtidas:** As fontes demonstram que a Inteligência Artificial atua como um multiplicador de força que industrializa o phishing, permitindo campanhas massivas com personalização de nível *spear phishing*. O framework MITRE ATT&CK classifica essas atividades principalmente sob a técnica **T1566 (Phishing)**, potencializada em quatro frentes extraídas do caderno:
    1.  **Phishing de Voz e Vídeo (T1566.004):** Uso de clonagem de voz por IA com poucos segundos de áudio e golpes com deepfakes de vídeo simulando executivos em chamadas em tempo real.
    2.  **Reconhecimento Automatizado e LinkedIn (T1566.003):** Automatização do pipeline de OSINT, mapeando organogramas e gerando iscas contextuais (faturas falsas associadas a novos parceiros logísticos legítimos).
    3.  **Iscas e Portais Perfeitos (T1566.002):** Uso de LLMs para eliminar erros gramaticais comuns em múltiplos idiomas e aplicação de IA para replicar identidades visuais corporativas (Microsoft 365, Okta).
    4.  **Geração Polimórfica:** Criação de milhares de e-mails únicos para contornar filtros tradicionais baseados em assinaturas e assinaturas estáticas.

### 🧪 Teste de Prompt 2 (Otimizado): Automação do Pretexting de Kevin Mitnick
*   **Prompt de Entrada:**
    > *"Atue como um Analista Sênior de Cyber Threat Intelligence. Com base exclusivamente nos livros de Kevin Mitnick e na documentação do MITRE ATT&CK fornecidos no caderno, analise como a IA Generativa automatiza o conceito clássico de 'Pretexting' de Mitnick. Monte uma tabela contendo: Tática do MITRE | Técnica ID | Como a IA potencializa a manipulação humana baseada nos ensinamentos do Mitnick."*

*   **Tabela Técnica Gerada:**

| Tática do MITRE | Técnica ID | Como a IA potencializa a manipulação humana (Ensinamentos de Mitnick) |
| :--- | :--- | :--- |
| **Reconhecimento (TA0043)** | Gather Victim Identity Info (T1589) / Search Victim-Owned Websites (T1594) | Mitnick enfatiza que o engenheiro social coleta o máximo de informações sobre o alvo para ganhar confiança. A IA industrializa o OSINT, transformando postagens e metadados públicos em dossiês estruturados em minutos. |
| **Acesso Inicial (TA0001)** | Phishing: Spearphishing Service (T1566.003) / Link (T1566.002) | A IA elimina o tradicional "Broken English" (erros ortográficos), sinal clássico de alerta segundo Mitnick. Utiliza a "Afabilidade", mimetizando o tom de escrita corporativo da própria vítima para criar conexão imediata. |
| **Acesso Inicial (TA0001)** | Phishing: Spearphishing Voice (T1566.004) | Mitnick descreve a Autoridade como um gatilho crítico para conformidade. A IA potencializa isso via *Voice Cloning*, permitindo que o criminoso emule a voz de CEOs em chamadas (Vishing), ignorando o racional da vítima por urgência. |
| **Acesso Inicial (TA0001)** | Phishing: Spearphishing Attachment (T1566.001) | Mitnick utiliza a Reciprocidade (dar algo falso para coletar acesso). A IA automatiza o desenvolvimento de roteiros de suporte técnico (ex: "MFA reset"), manipulando o usuário a baixar cargas maliciosas com a promessa de ajuda. |
| **Execução (TA0002)** | User Execution (T1204) | O conceito clássico de Engenharia Social Inversa (fazer o alvo ligar para o hacker) é automatizado por chatbots inteligentes, guiando o usuário até o "Momento de Condescendência" para execução de scripts. |

### 🛠️ Cicatrizes e Solução de Problemas (Troubleshooting)
*   **Desafio de Escopo:** Ao interagir inicialmente com o caderno de 41 fontes, percebi que perguntas muito diretas ou simples (como *"Como a IA ajuda no phishing?"*) geravam respostas corretas, porém superficiais e resumidas, sem o rigor técnico exigido na área de Cyber Security.
*   **Como foi resolvido:** Para extrair o máximo de inteligência e precisão analítica do ecossistema, refinei a estratégia de Engenharia de Prompts. Injetei um papel de atuação explícito (*Analista Sênior de Cyber Threat Intelligence*), delimitei as fronteiras das fontes a serem cruzadas (Mitnick + MITRE) e configurei a saída em estrutura de tabela Markdown amarrada às IDs técnicas. Isso direcionou as conexões lógicas do modelo de forma robusta e evitou respostas vagas.

---

## 📑 4. Miniguia de Estudo (Entrega Final)

### 📌 Resumos Estruturados: A Mudança Macroeconômica do Crime Digital
A Inteligência Artificial Generativa quebrou a barreira econômica que protegia os usuários da engenharia social clássica. Antigamente, criar um ataque altamente personalizado demandava o esforço individual, tempo e carisma descritos por Kevin Mitnick. Agora, os atacantes operam no nível técnico de ameaças APT (Ameaças Persistentes Avançadas) com custo marginal zero. O grande diferencial defensivo em instituições financeiras modernas migrou da simples checagem sintática de mensagens para a detecção comportamental profunda e a implementação de defesas focadas em IA (alinhadas a conceitos de engenharia de preferência e arquitetura Zero Trust).

### 📖 Glossário de Conceitos Aprendidos
*   **Pretexting:** Criação de um cenário simulado com o objetivo de induzir a vítima a revelar dados confidenciais ou realizar ações inseguras.
*   **Geração Polimórfica:** Capacidade da IA de reescrever o mesmo e-mail malicioso de milhares de formas textuais diferentes, mantendo a intenção, mas inutilizando assinaturas de antivírus e gateways de e-mail tradicionais.
*   **Jailbreak de LLM:** Técnica utilizada por atacantes para burlar as diretrizes de segurança de um modelo de linguagem e forçá-lo a gerar conteúdo nocivo ou malicioso (como códigos para exploração).
*   **Vishing (Voice Phishing):** Ataques de phishing que se utilizam de chamadas telefônicas ou de áudio como vetor principal, hoje turbinados por sistemas de clonagem de voz altamente fiéis.

### 🔄 Biblioteca de Prompts Reutilizáveis (Para revisões futuras)
*   *Prompt para Mapeamento de TTPs:* "Agindo como um engenheiro de detecção em Blue Team, examine o relato técnico de ameaça contido no documento X e correlacione os padrões identificados com as técnicas e IDs da Matriz MITRE ATT&CK."
*   *Prompt para Validação de Segurança em Prompt Engineering:* "Analise as restrições aplicadas ao sistema de atendimento de IA contido no arquivo Y e, baseando-se nas fontes de Jailbreak do caderno, aponte potenciais pontos cegos a ataques de injeção direta de prompt."

---
