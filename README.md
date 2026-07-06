# 🛡️ Mapeamento de Engenharia Social com IA através da Matriz MITRE ATT&CK e filosofia clássica de Kevin Mitnick
[![Licença: Direitos Reservados](https://shields.io)](LICENSE)
[![Bootcamp: Bradesco GenAI](https://shields.io)](https://dio.me)

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

Para alimentar o ecossistema de dados do NotebookLM, foi reunida uma robusta base de conhecimento composta por fontes técnico-conceituais atualizadas até 2026, incluindo PDFs históricos, relatórios de ameaças globais (Threat Intelligence) e artigos científicos recentes de segurança de IA:

<details>
<summary>📂 Clique aqui para visualizar a lista estruturada das fontes do Caderno</summary>

### 🌐 Documentos Fundamentais e Frameworks
*   **MITRE ATT&CK® (Página Principal)**
    *   https://attack.mitre.org/
*   **Initial Access, Tactic TA0001 - Enterprise | MITRE ATT&CK®**
    *   https://attack.mitre.org/tactics/TA0001/
*   **Initial Access, Tactic TA0108 - ICS | MITRE ATT&CK®**
    *   https://attack.mitre.org/tactics/TA0108/
*   **Enterprise Tactics - MITRE ATT&CK®**
    *   https://attack.mitre.org/tactics/enterprise/
*   **CAPEC - Common Attack Pattern Enumeration and Classification (CAPEC™)**
    *   https://capec.mitre.org/index.html

### 📖 Livros e Manuais de Kevin Mitnick (Arquivos Locais)
*   **A_Arte_de_Enganar.pdf**
    *   *Referência técnica sobre o fator humano na segurança.*
*   **A_Arte_de_invadir.pdf**
    *   *Histórias reais de invasões e análise de vulnerabilidades.*
*   **The History of Social Engineering (Mitnick Security)**
    *   https://www.mitnicksecurity.com/resources

### 📈 Inteligência de Ameaças (Threat Intelligence)
*   **X-Force Threat Intelligence Index 2026.pdf (IBM)**
    *   *Análise de tendências globais e abusos de credenciais de IA.*
*   **Relatório global do Kaspersky Security Services 2026.pdf**
    *   *Estatísticas de vetores de ataque e eficácia de detecção.*
*   **Resecurity | Trinity of Chaos: LAPSUS$, ShinyHunters, and Scattered Spider**
    *   *Análise de campanhas de extorsão de dados corporativos.*
*   **Tracking the Expansion of ShinyHunters-Branded SaaS Data Theft (Google Cloud)**
    *   https://cloud.google.com/blog/topics/threat-intelligence
*   **From LinkedIn to Tailored Attack in 30 Minutes: How AI Accelerates Target Profiling (Trend Micro)**
    *   https://www.trendmicro.com/vinfo/br/security/news/
*   **A Closer Look at the LAPSUS$ Data Extortion Group – Krebs on Security**
    *   https://krebsonsecurity.com/

### 🔬 Pesquisas Acadêmicas e IA (LLM/Jailbreak)
*   **TRYLOCK: Defense-in-Depth Against LLM Jailbreaks (arXiv)**
    *   *Código e avaliação de engenharia de preferência em camadas.*
*   **Comprehensive Assessment of Jailbreak Attacks Against LLMs (arXiv)**
    *   https://arxiv.org/abs/2404.02151 *(Ref. cruzada)*
*   **Making Them Ask and Answer: Jailbreaking LLMs (USENIX)**
    *   *Estudo sobre ataques DRA (Disguise and Reconstruction).*
*   **Jailbreak Attacks and Defenses in LLMs: A Beginner-Friendly Survey (MDPI)**
    *   https://www.mdpi.com/journal/preprints
*   **Guardrails for LLMs - Arize AI**
    *   https://arize.com/docs/ax
*   **LLM Jailbreak Robustness Overview - Emergent Mind**
    *   https://www.emergentmind.com/
*   **Daily Papers - Hugging Face**
    *   https://huggingface.co/papers

### 🏢 Guias de Prevenção e Governamentais
*   **Phishing Guidance: Stopping the Attack Cycle at Phase One (CISA)**
    *   *Download e diretrizes de mitigação corporativa.*
*   **How to Protect Against Evolving Phishing Attacks (NSA)**
    *   *Artigo completo com frentes táticas da agência nacional de segurança.*
*   **Cartilha de Segurança para Internet (CERT.br)**
    *   https://cartilha.cert.br/
*   **Avoiding Social Engineering and Phishing Attacks | CISA**
    *   http://www.cisa.gov/news-events/news/avoiding-social-engineering-and-phishing-attacks
*   **Access Denied (CISA Advisory aa23-320a)**
    *   http://www.cisa.gov/news-events/cybersecurity-advisories/aa23-320a
*   **In Cyber, Differentiating Between State Actors, Criminals Is a Blur (DOW/War.gov)**
    *   *Análise do Departamento de Defesa dos EUA.*

### 🛠️ Artigos Técnicos e Estudos de Caso
*   **Decrypting credentials from SCCM site servers (IBM X-Force)**
    *   https://www.ibm.com/think/x-force/decrypting-credentials-from-sccm-site-servers
*   **Oh non! Spear phishing campaign targets users in France (IBM)**
    *   *Análise de vazamento massivo de dados e engenharia social.*
*   **Hive0145 back in German inboxes with Strela Stealer (IBM)**
    *   *Análise tática de campanhas ativas de infostealers.*
*   **North Korean Hackers Adopt Infostealer Spreading Tactics (InfoStealers)**
    *   https://www.infostealers.com/
*   **Abuse of Cloud-Native Infrastructure in Modern Phishing (Cyfirma)**
    *   https://www.cyfirma.com/
*   **Silver Fox APT Targets Public Sector via Trojanized Medical Software (Picus)**
    *   https://www.picussecurity.com/resource/tag/reports
*   **What Is Phishing and How Can You Stop It? (Vectra AI)**
    *   https://www.vectra.ai/research
*   **What is MITRE ATT&CK Initial Access (TA0001)? (Netscout)**
    *   https://www.netscout.com/learning-center
*   **Initial Access in Cybersecurity: The Attack Stage Most Businesses Miss (Huntress)**
    *   https://www.huntress.com/blog
*   **25+ Spear Phishing Examples & How to Prevent Them**
    *   *[Recurso educacional sobre engenharia de e-mail]*
*   **Phishing & Security Awareness Glossary**
    *   *[Dicionário corporativo de conscientização de ameaças]*


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
*   **Desafio de Escopo:** Ao interagir inicialmente com o notebooklm junto com todas as fontes, percebi que perguntas muito diretas ou simples (como *"Como a IA ajuda no phishing?"*) geravam respostas corretas, porém superficiais e resumidas, sem o rigor técnico exigido na área de Cyber Security.
*   **Como foi resolvido:** Para extrair o máximo de inteligência e precisão analítica do ecossistema, refinei a estratégia de Engenharia de Prompts. Injetei um papel de atuação explícito de uma persona com a mentalidade hacker de Kevin Mitnick agindo como um Analista Sênior de Cyber Threat Intelligence, delimitei as fronteiras das fontes a serem cruzadas (Mitnick + MITRE) e configurei a saída em estrutura de tabela Markdown amarrada às IDs técnicas. Isso direcionou as conexões lógicas do modelo de forma robusta e evitou respostas simples.

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
