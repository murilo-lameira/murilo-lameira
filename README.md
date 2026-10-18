<div align="center">

# 👋 Olá! Eu sou o Murilo Lameira

### ⚙️ Engenharia de Controle e Automação (SENAI) • 🤖 IA Evolutiva, Gêmeos Digitais & IoT • 📊 Inteligência de Dados

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Murilo%20Lameira-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/murilo-lameira)
[![Gmail](https://img.shields.io/badge/Email-murilolameira14%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:murilolameira14@gmail.com)
[![Mirage Paper](https://img.shields.io/badge/Artigo%20IEEE%2FSBC-Mirage%20(PDF)-008080?style=for-the-badge&logo=latex&logoColor=white)](https://github.com/murilo-lameira/Mirage/blob/main/paper/Mirage_Artigo_SENAI.pdf)
[![Location](https://img.shields.io/badge/Localiza%C3%A7%C3%A3o-ABC%20Paulista%2C%20SP-2ea44f?style=for-the-badge)](https://github.com/murilo-lameira)

</div>

---

## 🎯 Sobre Mim

Sou estudante do 8º semestre de **Engenharia de Controle e Automação** no **Centro Universitário SENAI SP (UNISENAI)**, Técnico em Eletroeletrônica pelo SENAI e atualmente **Estagiário de Engenharia na Toledo do Brasil** (*Unidade de Negócios Fast Factory & Automação*).

Minha atuação conecta a **engenharia de chão de fábrica** (modelagem dinâmica de processos, sintonia de controladores PID, instrumentação industrial, OPC UA, sistemas embarcados e normas NR-12) à **inteligência computacional e engenharia de software** (Algoritmos Genéticos, Gêmeos Digitais, Agentes de IA, pipelines de dados em Python e dashboards executivos em Power BI).

---

## 🌟 Destaque Principal — Publicação Científica & Simulador *Mirage*

<div align="center">

### 🌌 [Mirage: Adaptação Evolutiva de NPCs sob Restrição Orçamentária com Esquiva Preditiva](https://github.com/murilo-lameira/Mirage)

[![Status](https://img.shields.io/badge/Artigo%20Cient%C3%ADfico-IEEE%20%2F%20SBC%20Short%20Paper-success?style=flat-square)](https://github.com/murilo-lameira/Mirage/blob/main/paper/Mirage_Artigo_SENAI.pdf)
[![PDF](https://img.shields.io/badge/📄%20Baixar%20Artigo%20(PDF)-Mirage__Artigo__SENAI.pdf-EC1C24?style=flat-square)](https://github.com/murilo-lameira/Mirage/blob/main/paper/Mirage_Artigo_SENAI.pdf)
[![LaTeX](https://img.shields.io/badge/📝%20C%C3%B3digo--Fonte%20LaTeX-Mirage__Artigo__SENAI.tex-008080?style=flat-square)](https://github.com/murilo-lameira/Mirage/blob/main/paper/Mirage_Artigo_SENAI.tex)
[![Repo](https://img.shields.io/badge/💻%20Reposit%C3%B3rio%20Oficial-murilo--lameira%2FMirage-181717?style=flat-square&logo=github)](https://github.com/murilo-lameira/Mirage)

</div>

> **Autores:** Murilo Lameira da Silva, Henry Matheus Fregolente Ferreira, Murilo Romualdo da Silva, Leonardo Retori Apolônio e Prof. Me. Ricardo Martinez Vicentini.  
> **Instituição:** Engenharia de Controle e Automação — Centro Universitário SENAI SP (UNISENAI), São Caetano do Sul, SP.

O **Mirage** é um framework de computação evolucionária e inteligência cinemática vetorial desenvolvido em arquitetura híbrida (**Python / Pygame / NumPy / SciPy** e **MATLAB / GNU Octave**) para sintetizar comportamentos de evasão tática em Agentes Não-Jogáveis (*NPCs*) imersos em ambientes de *Bullet Hell* a $50\text{ FPS}$.

<p align="center">
  <img src="https://raw.githubusercontent.com/murilo-lameira/Mirage/main/data/graficos/demonstracao_npc.gif" alt="Demonstração do NPC Mirage em Combate" height="260">
  &nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/murilo-lameira/Mirage/main/data/graficos/fig_map_elites.png" alt="Heatmap MAP-Elites 3x3 Mirage" height="260">
</p>

### 🔬 Contribuições Científicas & Resultados Experimentais ($N = 90$ rodadas | $135.000$ combates)

1. **Mitigação Analítica de *Reward Hacking* via Orçamento Homotético ($B \le 1,80$):**
   * Algoritmos genéticos irrestritos colapsam em "esponjas de dano" estáticas ($100\%$ com $200\text{ HP}$ e variância de velocidade $\sigma^2 = 0,004$).
   * A projeção homotética sobre o simplex contínuo força todos os campeões à **fronteira de Pareto** ($\sum u_i \approx 1,78\text{--}1,79 \le 1,80$), originando autonomamente **3 arquétipos ecológicos** conforme o regime balístico:
     * 🎯 **Fácil ($D_1$) — *Sniper / Glass Cannon*:** Maximiza ataque ($u_2 = 0,99$) e cadência ($2,47\text{ Hz}$) para neutralização imediata.
     * ⚖️ **Médio ($D_2$) — *Combatente Equilibrado*:** Balanceia poder de fogo ($u_2 = 0,79$) com mobilidade intermediária ($1,69\text{ m/s}$).
     * ⚡ **Difícil ($D_3$) — *Bruiser / Ladino*:** Triplica a velocidade ($3,21\text{ m/s}$) e reserva de vida ($72,73\text{ HP}$) com alta taxa de esquivas ($83,80$ desvios/episódio).
2. **Cinemática Preditiva Dual (CPA + *Lead-Aiming* + *Steering Behaviors* de Reynolds):**
   * Dedução analítica do instante de Maior Aproximação ($t_{\text{cpa}} = -(\mathbf{p}_{\text{rel}} \cdot \mathbf{v}_{\text{rel}}) / \|\mathbf{v}_{\text{rel}}\|^2$) combinada à interceptação balística de 1ª ordem.
   * **Estudo de Ablação:** Redução de **77,5% na frequência de colisões** ($0,48$ vs $2,14\text{ hits/s}$; $t = 18,72, p < 10^{-24}$) e **aumento de +103,7% no tempo de sobrevivência** no nível Difícil ($23,22\text{ s}$ vs $11,40\text{ s}$) frente à repulsão euclidiana reativa.
3. **Iluminação Fenotípica com MAP-Elites & Rigor Estatístico:**
   * Preenchimento de **100% da grade comportamental ($9/9$ nichos)** com $\text{QD-Score} = \mathbf{39.114,40}$, viabilizando Ajuste Dinâmico de Dificuldade (*DDA*) sem retreinamento.
   * Separação fenotípica comprovada por **ANOVA One-Way** ($F = 184,55, p = 2,12 \times 10^{-32}$), **Kruskal-Wallis** ($H = 61,80, p < 10^{-13}$) e tamanho de efeito de **Cohen ($d = 18,61$)**.

<details>
<summary>📌 <b>Citação BibTeX do Artigo</b> (clique para expandir)</summary>

```bibtex
@inproceedings{silva2026mirage,
  title     = {Mirage: Adapta{\c{c}}{\~a}o Evolutiva de NPCs sob Restri{\c{c}}{\~a}o Or{\c{c}}ament{\'a}ria com Esquiva Preditiva},
  author    = {Silva, Murilo Lameira da and Ferreira, Henry Matheus Fregolente and Silva, Murilo Romualdo da and Apol{\^o}nio, Leonardo Retori and Vicentini, Ricardo Martinez},
  booktitle = {Simp{\'o}sio Brasileiro de Jogos e Entretenimento Digital (SBGames) / IEEE CoG},
  year      = {2026},
  address   = {S{\~a}o Caetano do Sul, SP, Brasil}
}
```
</details>

---

## 🚀 Portfólio de Projetos de Engenharia & Software

| Projeto | Domínio & Tecnologias | Destaques Técnicos & Impacto |
| :--- | :--- | :--- |
| 🧬 **[Genetic PID Tuning & Digital Twin](https://github.com/murilo-lameira/genetic-pid-tuning)** | `Python` `NumPy` `Scikit-Learn` `Control Systems` `Altair Compose` | **Gêmeo Digital ($R^2 \ge 99,7\%$)** e sintonia evolutiva de controladores PID via Algoritmo Genético (critério ITAE). Aplicado em refrigeração IoT e na **Planta Industrial Multiprocesso SENAI** (OPC UA / Elipse E3, $R^2 = 99,96\%$), reduzindo o índice **ITAE em 93,4%** com **0% de sobressinal** e tempo de acomodação **$4\times$ menor** ($143,5\text{ s}$ vs $561,5\text{ s}$ IMC), com estabilidade assintótica provada via **Routh-Hurwitz**. |
| ❄️ **[Thermal Freezer IoT](https://github.com/murilo-lameira/Thermal-Freezer-IoT)** | `C++` `ESP32` `PID` `MQTT` `Node-RED` `Peltier` | Sistema embarcado de controle térmico em malha fechada operando até $-19\,^\circ\text{C}$ com módulos termoelétricos Peltier, sensores Dallas OneWire, telemetria em tempo real via broker MQTT e dashboard supervisório em Node-RED. |
| 📱 **[Stream Deck Mobile (Mi 9)](https://github.com/murilo-lameira/Stream-Deck)** | `FastAPI` `WebSockets` `Win32 API` `React PWA` `Pycaw` | Transforma um smartphone em um controlador de mídia, áudio por processo e automação de janelas para Windows 11 com latência sub-milissegundo via WebSockets e proteção anti-*burn-in* para telas OLED. |
| ⚡ **[Bidding Monitor Automation](https://github.com/murilo-lameira/bidding-monitor-automation)** | `n8n` `JavaScript` `Web Scraping` `REST APIs` | Pipeline automatizado de inteligência comercial que monitora portais de compras públicas do setor elétrico, filtra editais por escopo técnico em JavaScript e estrutura relatórios executivos. |
| 🩺 **[Projeto CheckUP Windows](https://github.com/murilo-lameira/projeto-checkup-windows)** | `PowerShell` `JavaScript` `HTML/CSS` `Windows Internals` | Ferramenta de diagnóstico automatizado e reparo de sistemas Windows (saúde de bateria, S.M.A.R.T., integridade de rede e memória) com emissão de relatórios HTML interativos e autônomos. |
| 🎮 **[LoL Elo Tracker](https://github.com/murilo-lameira/lol-elo-tracker)** | `Python` `SQLite` `Data Science` `CLI` | Sistema de telemetria e análise de dados para rastreamento de evolução de performance competitiva com persistência relacional em SQLite. |

---

## 💼 Experiência Profissional

* 🏢 **Toledo do Brasil** — *Estagiário de Engenharia (Unidade Fast Factory & Automação)* `(Set/2026 – Presente)`
  * Automação de fluxos de trabalho e processos operacionais de engenharia com **Microsoft Power Automate**.
  * Suporte técnico ao desenvolvimento e acompanhamento de projetos industriais de engenharia e automação.
  * Estruturação de KPIs operacionais, rastreamento de cronogramas e gestão de documentação técnica de engenharia.
* 🛠️ **FTS Serviços Especializados de Manutenção** — *Estagiário de Engenharia* `(Abr/2026 – Set/2026)`
  * Desenvolvimento de agentes de Inteligência Artificial para automação de fluxos comerciais e operacionais.
  * Construção de dashboards gerenciais em **Power BI (DAX)** e automação de ETL em **VBA/Excel**.
* ⚙️ **SSI Automação** — *Consultor Técnico* `(Fev/2024 – Out/2025)`
  * Liderou a automatização da emissão de laudos técnicos de segurança de máquinas (**NR-12**), reduzindo o tempo operacional em **30%**.
  * Desenvolvimento de aplicação interna em **Python** e **MySQL** para geração automatizada de relatórios de engenharia.

---

## 🛠️ Tecnologias & Ferramentas

<p align="left">
  <b>Linguagens & Computação Científica:</b><br>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/MATLAB%20%2F%20Octave-0076A8?style=for-the-badge&logo=mathworks&logoColor=white" alt="MATLAB/Octave">
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="SQL">
  <img src="https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white" alt="PowerShell">
  <img src="https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white" alt="LaTeX">
</p>

<p align="left">
  <b>IA, Ciência de Dados & Power Platform:</b><br>
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI">
  <img src="https://img.shields.io/badge/Power%20Automate-0066FF?style=for-the-badge&logo=powerautomate&logoColor=white" alt="Power Automate">
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white" alt="SciPy">
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-Learn">
  <img src="https://img.shields.io/badge/Genetic%20Algorithms%20%26%20MAP--Elites-FF6F00?style=for-the-badge" alt="Genetic Algorithms">
</p>

<p align="left">
  <b>Automação Industrial, IoT & Arquitetura de Software:</b><br>
  <img src="https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white" alt="ESP32">
  <img src="https://img.shields.io/badge/MQTT-660066?style=for-the-badge&logo=mqtt&logoColor=white" alt="MQTT">
  <img src="https://img.shields.io/badge/Node--RED-8F0000?style=for-the-badge&logo=nodered&logoColor=white" alt="Node-RED">
  <img src="https://img.shields.io/badge/OPC%20UA%20%2F%20Elipse%20E3-004B87?style=for-the-badge" alt="OPC UA">
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white" alt="n8n">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="AWS">
</p>

---

## 🎓 Formação & Certificações

* 🎓 **Bacharelado em Engenharia de Controle e Automação** — *Centro Universitário SENAI SP (UNISENAI)* `(2023 – 2027)`
* ⚡ **Técnico em Eletroeletrônica** — *Escola SENAI A. Jacob Lafer* `(2018 – 2020)`
* 🏅 **Certificações:** Lean Seis Sigma Yellow Belt • AWS Academy Graduate (Cloud Foundations) • Python 3 & Collections

---

<div align="center">
  <sub>📫 Vamos conversar sobre <b>Engenharia de Controle, Automação Industrial, IA Evolutiva ou Inteligência de Dados</b>? Conecte-se comigo no <a href="https://www.linkedin.com/in/murilo-lameira">LinkedIn</a>!</sub>
</div>
