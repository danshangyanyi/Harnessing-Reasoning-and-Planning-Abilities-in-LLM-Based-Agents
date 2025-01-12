# Harnessing-Reasoning-and-Planning-Abilities-in-LLM-Based-Agents

Last update: 12/05/2024

<img src="./img/time.png" width="96%" height="96%">

<font size=5><center><b> Table of Contents </b> </center></font>
- [Papers](#Apapers)
  - [Scenarios](#scenarios)
  - [Framework](#framework)
    - [During Perception](#Perception)
        - [Selection](#Selection)
        - [Preprocessing](#Preprocessing)
        - [Perception Planning](#Perception_Planning)
    - [During Action](#Action)
        - [Dynamic Tool Selection](#Dyanamic_Tool_Selection)
        - [Adjustment](#Adjustment)
        - [Long Term Task](#Long_Term_Task)
    - [During Reasoning](#Reasoning)
        - [Result Analyse](#Result_Analyse)
        - [Trajectory Analyse](#Trajectory_Analyse)
        - [Thinking Summarize](#Thinking_Summarize)
  - [Application](#application)
    - [Social Simulation](#Social)
    - [Game](#Game)
    - [Visual Task](#Visual)
    - [Economy Simulation](#Economy_Simulation)
    - [Multi-Agent Application](#Multi-Agent)
- [Benchmark](#benchmark)
---

## Papers

### Scenarios

<img src="./img/table.png" width="96%" height="96%">

### Framework

<img src="./img/table.png" width="96%" height="96%">

#### Perception

<img src="./img/table.png" width="96%" height="96%">

##### Selection

- [**Synapes**](https://arxiv.org/pdf/2306.07863.pdf) - Synapse: Trajectory-as-exemplar prompting with memory for computer control. [Github](https://ltzheng.github.io/Synapse/)
  
- [**MT-Mind2Web**](https://arxiv.org/pdf/2402.15057.pdf) - On the Multi-turn Instruction Following for Conversational Web Agents. [Github](https://github.com/magicgh/self-map)

- [**KAFT**](https://arxiv.org/pdf/2211.05110.pdf) - Large language models with controllable working memory.

##### Preprocessing

- [**Steve-eye**](https://arxiv.org/pdf/2310.13255.pdf) - Steve-eye: Equipping llm-based embodied agents with visual perception in open worlds. [Project](https://sites.google.com/view/steve-eye)

- [**Seeclick**](https://arxiv.org/pdf/2401.10935.pdf) - Seeclick: Harnessing gui grounding for advanced visual gui agents. [Github](https://github.com/njucckevin/SeeClick)

- [**PerceptiveAgent**](https://arxiv.org/pdf/2406.12707.pdf) - Talk With Human-like Agents: Empathetic Dialogue Through Perceptible Acoustic Reception and Reaction. [Github](https://github.com/Haoqiu-Yan/PerceptiveAgent)

- [**Auto-GUI**](https://arxiv.org/pdf/2309.11436.pdf) - You only look at screens: Multimodal chain-of-action agents. [Github](https://github.com/cooelf/Auto-GUI.)

- [**OPAL**](https://aclanthology.org/2024.findings-acl.12/.pdf) - Text2DB: Integration-Aware Information Extraction with Large Language Model Agents.

##### Preception_Planning

- [**GeoAgent**](https://aclanthology.org/2024.findings-acl.362.pdf) - GeoAgent: To Empower LLMs using Geospatial Tools for Address Standardization. [Github](https://github.com/chenghuahuang/GeoAgent)

- [**OPAL**](https://aclanthology.org/2024.findings-acl.12/.pdf) - Text2DB: Integration-Aware Information Extraction with Large Language Model Agents.

- [**HTTP**](https://aclanthology.org/2024.acl-long.716.pdf) - Visualization recommendation with prompt-based reprogramming of large language models.

- [**DDCoT**](https://arxiv.org/pdf/2310.16436.pdf) - DDCoT: Duty-Distinct Chain-of-Thought Prompting for Multimodal Reasoning in Language Models [Github](https://github.com/SooLab/DDCOT)


#### Action

<img src="./img/table.png" width="96%" height="96%">

##### Dynamic Tool Selection

- [**Codeagent**](https://arxiv.org/pdf/2401.07339.pdf) - Codeagent: Enhancing code generation with tool-integrated agent systems for real-world repo-level coding challenges.

- [**MLLM-Tool**](https://arxiv.org/pdf/2401.10727.pdf) - MLLM-Tool: A Multimodal Large Language Model For Tool Agent Learning [Github](https://github.com/MLLM-Tool/MLLM-Tool)

- [**TPTU**](https://arxiv.org/pdf/2311.16714.pdf) - TPTU: large language model-based AI agents for task planning and tool usage. [Github](https://github.com/stevenyangyj/Emma-Alfworld)
![Star](https://img.shields.io/github/stars/stevenyangyj/Emma-Alfworld.svg?style=social&label=Star)

- [**Autoact**](https://arxiv.org/pdf/2401.05268.pdf) - Autoact: Automatic agent learning from scratch via self-planning. [Github](https://github.com/zjunlp/AutoAct)

- [**UALA**](https://arxiv.org/pdf/2401.14016.pdf) - Towards Uncertainty-Aware Language Agent. [Github](https://uala-agent.github.io/)

- [**TPTU-v2**](https://arxiv.org/pdf/2311.11315.pdf) - TPTU-v2: Boosting Task Planning and Tool Usage of Large Language Model-based Agents in Real-world Systems.

##### Adjustment

- [**ReAct**](https://arxiv.org/pdf/2210.03629.pdf) - React: Synergizing reasoning and acting in language models. [Github](https://github.com/ysymyth/ReAct)

- [**Generative agents**](https://arxiv.org/pdf/2304.03442.pdf) - Generative agents: Interactive simulacra of human behavior.

- [**SYNAPSE**](https://arxiv.org/pdf/2306.07863.pdf) - SYNAPSE: TRAJECTORY-AS-EXEMPLAR PROMPTING WITH MEMORY FOR COMPUTER CONTROL. [Github](https://ltzheng.github.io/Synapse)

- [**RaDA**](https://aclanthology.org/2024.findings-acl.802.pdf) - RaDA: Retrieval-augmented Web Agent Planning with LLMs. [Github](https://github.com/ldilab/RaDA)

- [**WebVoyager**](https://arxiv.org/pdf/2401.13919.pdf) - WebVoyager : Building an End-to-End Web Agent with Large Multimodal Models. [Github](https://github.com/MinorJerry/WebVoyager)

- [**Retroformer**](https://arxiv.org/pdf/2308.02151.pdf) - RETROFORMER: RETROSPECTIVE LARGE LANGUAGE AGENTS WITH POLICY GRADIENT OPTIMIZATION. [Github](https://github.com/weirayao/Retroformer)

- [**LATS**](https://arxiv.org/pdf/2310.04406.pdf) - Language Agent Tree Search Unifies Reasoning, Acting, and Planning in Language Models. [Github](https://github.com/lapisrocks/LanguageAgentTreeSearch)

- [**RAFA**](https://arxiv.org/pdf/2309.17382.pdf) - Reason for Future, Act for Now: A Principled Architecture for Autonomous LLM Agents. [Github](https://github.com/agentification/RAFA_code)

- [**QueryAgent**](https://arxiv.org/pdf/2403.11886.pdf) - QueryAgent: A Reliable and Efficient Reasoning Framework with Environmental Feedback-based Self-Correction. [Github](https://github.com/cdhx/QueryAgent)

- [**Auto-GUI**](https://arxiv.org/pdf/2309.11436.pdf) - You only look at screens: Multimodal chain-of-action agents. [Github](https://github.com/cooelf/Auto-GUI)

- [**Readi**](https://arxiv.org/pdf/2403.08593.pdf) - Call Me When Necessary: LLMs can Efficiently and Faithfully Reason over Structured Environments. [Github](https://github.com/microsoft/Readi)

- [**UALA**](https://arxiv.org/pdf/2401.14016.pdf) - Towards Uncertainty-Aware Language Agent. [Github](https://uala-agent.github.io/)

##### Long_Term_Task

- [**GITM**](https://arxiv.org/pdf/2305.17144.pdf) - Ghost in the Minecraft: Generally Capable Agents for Open-World Environments via Large Language Models with Text-based Knowledge and Memory. [Github](https://github.com/OpenGVLab/GITM)

- [**Voyager**](https://arxiv.org/pdf/2305.16291.pdf) - VOYAGER: An Open-Ended Embodied Agent with Large Language Models.

- [**EconAgent**](https://arxiv.org/pdf/2310.10436.pdf) - EconAgent: Large Language Model-Empowered Agents for Simulating Macroeconomic Activities. [Github](https://github.com/tsinghua-fib-lab/ACL24-EconAgent)


#### Reasoning

<img src="./img/table.png" width="96%" height="96%">

##### Result_Analyse

- [**Retroformer**](https://arxiv.org/pdf/2308.02151.pdf) - RETROFORMER: RETROSPECTIVE LARGE LANGUAGE AGENTS WITH POLICY GRADIENT OPTIMIZATION. [Github](https://github.com/weirayao/Retroformer)

- [**SELF-REFINE**](https://arxiv.org/pdf/2303.17651.pdf) - SELF-REFINE: Iterative Refinement with Self-Feedback. [Github](https://github.com/madaan/self-refine)

- [**QueryAgent**](https://arxiv.org/pdf/2403.11886.pdf) - QueryAgent: A Reliable and Efficient Reasoning Framework with Environmental Feedback-based Self-Correction. [Github](https://github.com/cdhx/QueryAgent)

##### Trajectory_Analyse

- [**ExpeL**](https://arxiv.org/pdf/2308.10144.pdf) - ExpeL: LLM Agents Are Experiential Learners. [Github](https://github.com/LeapLabTHU/ExpeL)

- [**Autoact**](https://arxiv.org/pdf/2401.05268.pdf) - Autoact: Automatic agent learning from scratch via self-planning. [Github](https://github.com/zjunlp/AutoAct)

- [**ETO**](https://arxiv.org/pdf/2403.02502.pdf) - Trial and Error: Exploration-Based Trajectory Optimization for LLM Agents. [Github](https://github.com/Yifan-Song793/ETO)

##### Thinking_Summarize

- [**Reflexion**](https://arxiv.org/pdf/2303.11366.pdf) - Reflexion: Language Agents with Verbal Reinforcement Learning. [Github](https://github.com/noahshinn/reflexion)

- [**TiM**](https://arxiv.org/pdf/2311.08719.pdf) - Think-in-Memory: Recalling and Post-thinking Enable LLMs with Long-Term Memory.

- [**Agent-pro**](https://arxiv.org/pdf/2402.17574.pdf) - Agent-Pro: Learning to Evolve via Policy-Level Reflection and Optimization. [Github](https://github.com/zwq2018/Agent-Pro)

## Application

<img src="./img/app.png" width="96%" height="96%">

#### Social Simulation and Dialogues

- [**PerceptiveAgent**](https://arxiv.org/pdf/2406.12707.pdf) - Talk With Human-like Agents: Empathetic Dialogue Through Perceptible Acoustic Reception and Reaction. [Github](https://github.com/Haoqiu-Yan/PerceptiveAgent)

- [**Generative agents**](https://arxiv.org/pdf/2304.03442.pdf) - Generative agents: Interactive simulacra of human behavior.

- [**Intention-inInteraction**](https://arxiv.org/pdf/2402.09205.pdf) - Tell Me More! Towards Implicit User Intention Understanding of Language Model Driven Agents. [Github](https://github.com/thunlp/Tell_Me_More)

- [**Rec4Agentverse**](https://arxiv.org/pdf/2402.18240.pdf) - Prospect Personalized Recommendation on Large Language Model-based Agent Platform. [Github](https://github.com/jizhi-zhang/Rec4Agentverse_Case)

- [**Harnessing the power of llms for normative reasoning in mass.**](https://arxiv.org/pdf/2403.16524.pdf)

- [**Exploring Collaboration Mechanisms for LLM Agents: A Social Psychology View**](https://arxiv.org/pdf/2310.02124.pdf) [Github](https://zjunlp.github.io/project/MachineSoM/)

- [**Polarization of Autonomous Generative AI Agents Under Echo Chambers**](https://arxiv.org/pdf/2402.12212.pdf)

#### Game 

- [**PsychoGAT**](https://arxiv.org/pdf/2402.12326.pdf) - PsychoGAT: A Novel Psychological Measurement Paradigm through Interactive Fiction Games with LLM Agents

- [**Steve-eye**](https://arxiv.org/pdf/2310.13255.pdf) - Steve-eye: Equipping llm-based embodied agents with visual perception in open worlds. [Project](https://sites.google.com/view/steve-eye)

- [**Voyager**](https://arxiv.org/pdf/2305.16291.pdf) - VOYAGER: An Open-Ended Embodied Agent with Large Language Models.

- [**ProAgent**](https://arxiv.org/pdf/2308.11339.pdf) - ProAgent: Building Proactive Cooperative Agents with Large Language Models [Github](https://pku-proagent.github.io)

- [**Agent-pro**](https://arxiv.org/pdf/2402.17574.pdf) - Agent-Pro: Learning to Evolve via Policy-Level Reflection and Optimization. [Github](https://github.com/zwq2018/Agent-Pro)

- [**GITM**](https://arxiv.org/pdf/2305.17144.pdf) - Ghost in the Minecraft: Generally Capable Agents for Open-World Environments via Large Language Models with Text-based Knowledge and Memory. [Github](https://github.com/OpenGVLab/GITM)

- [**Exploring Large Language Models for Communication Games: An Empirical Study on Werewolf**](https://arxiv.org/pdf/2309.04658.pdf)

- [**LLM as a Mastermind: A Survey of Strategic Reasoning with Large Language Models**](https://arxiv.org/pdf/2404.01230.pdf)

#### Visual Reasoning and Web Reasoning with Figure

- [**Seeclick**](https://arxiv.org/pdf/2401.10935.pdf) - Seeclick: Harnessing gui grounding for advanced visual gui agents. [Github](https://github.com/njucckevin/SeeClick)

- [**Auto-GUI**](https://arxiv.org/pdf/2309.11436.pdf) - You only look at screens: Multimodal chain-of-action agents. [Github](https://github.com/cooelf/Auto-GUI)

- [**WebVoyager**](https://arxiv.org/pdf/2401.13919.pdf) - WebVoyager : Building an End-to-End Web Agent with Large Multimodal Models. [Github](https://github.com/MinorJerry/WebVoyager)

- [**DDCoT**](https://arxiv.org/pdf/2310.16436.pdf) - DDCoT: Duty-Distinct Chain-of-Thought Prompting for Multimodal Reasoning in Language Models [Github](https://github.com/SooLab/DDCOT)

- [**MT-Mind2Web**](https://arxiv.org/pdf/2402.15057.pdf) - On the Multi-turn Instruction Following for Conversational Web Agents. [Github](https://github.com/magicgh/self-map)

- [**MM-REACT**](https://arxiv.org/pdf/2303.11381.pdf) - MM-REACT: Prompting ChatGPT for Multimodal Reasoning and Action [Github](https://github.com/microsoft/MM-REACT)
![Star](https://img.shields.io/github/stars/microsoft/MM-REACT.svg?style=social&label=Star)

#### Economy Simulation
- [**TRADINGGPT**](https://arxiv.org/pdf/2309.03736.pdf) - TRADINGGPT: MULTI-AGENT SYSTEM WITH LAYERED MEMORY AND DISTINCT CHARACTERS FOR ENHANCED FINANCIAL TRADING PERFORMANCE.

- [**EconAgent**](https://arxiv.org/pdf/2310.10436.pdf) - EconAgent: Large Language Model-Empowered Agents for Simulating Macroeconomic Activities. [Github](https://github.com/tsinghua-fib-lab/ACL24-EconAgent)

#### Multi-Agent
- [**ChatDev**](https://arxiv.org/pdf/2307.07924.pdf) - ChatDev: Communicative Agents for Software Development. [Github](https://github.com/OpenBMB/ChatDev)

- [**MetaGPT**](https://arxiv.org/pdf/2304.07590.pdf) - Self-collaboration Code Generation via ChatGPT. [Github](https://github.com/YihongDong/Self-collaboration-Code-Generation)

- [**AutoGen**](https://arxiv.org/pdf/2308.08155.pdf) - AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversation. [Github]("https://github.com/microsoft/autogen")

- [**CAMEL**](https://arxiv.org/pdf/2303.17760.pdf) - CAMEL: Communicative Agents for “Mind” Exploration of Large Language Model Society [Github](https://github.com/camel-ai/camel)

- [**MEDAGENTS**](https://arxiv.org/pdf/2311.10537.pdf) - MEDAGENTS: Large Language Models as Collaborators for Zero-shot Medical Reasoning [Github](https://github.com/gersteinlab/MedAgents)
  
- [**Rethinking the Bounds of LLM Reasoning: Are Multi-Agent Discussions the Key?**](https://arxiv.org/pdf/2402.18272.pdf)



