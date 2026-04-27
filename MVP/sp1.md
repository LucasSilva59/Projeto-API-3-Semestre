# 📌 MVP - NexusLog

## 🎯 Objetivo do MVP
> O objetivo é resolver o problema de falta de intregridade das bases de dados, dessa forma, gerar um Dashboard para melhor visualização e analise. Poderiamos também com esses dados gerar mapas, filtros, indicativos e dentre outros. O valor é apresentar os estados com a maior taxa de letalidade envolvendo veículos pesados.  
 
---

## 📝 Descrição da Solução
> Nesta etapa, focaremos na extração e tratamento de dados do SENATRAN, PRF e IBGE para criar um dashboard interativo. A ferramenta terá filtros (ano, região e veículo) e exibirá métricas de sinistros, vítimas, frota, população e tendências (2024-2025). A principal limitação é a dificuldade de cruzar as bases de dados devido às suas divergências estruturais. Por fim, o escopo foi reduzido para responder a questão: "Quais estados apresentam a maior taxa de letalidade envolvendo veículos pesados?".

---

## 👥 Personas / Usuários-Alvo
- **Persona 1:** O Observatório é um núcleo de inteligência focado em monitorar cenários e fornecer informações estratégicas para empresas, startups e o ecossistema de inovação da região. A sua necessidade central envolve a captação, estruturação e o cruzamento de bases de dados complexas para gerar indicadores confiáveis que apoiem a tomada de decisão do mercado. Já as suas dores são atendidas na medida em que o projeto automatiza o tratamento de dados públicos massivos e dispersos, centraliza essas informações em um dashboard interativo e transforma dados brutos sobre frota e sinistros em análises visuais de alto valor estratégico.
- **Persona 2:** O Coordenador de Curso atua como o mentor estratégico focado em monitorar o desenvolvimento técnico e fornecer suporte especializado para a equipe e o ecossistema de inovação da Fatec. A sua necessidade central envolve a análise crítica, a validação e o acompanhamento das bases de dados exploradas no projeto para garantir que os indicadores gerados sejam tecnicamente sólidos e apoiem a tomada de decisão acadêmica e mercadológica.

---

## 🔑 User Stories (Backlog do MVP)
| ID  | User Story                                                                 | Prioridade | Estimativa |
|-----|-----------------------------------------------------------------------------|------------|------------|
| US1 | Como Coordenador de Curso , quero que os dados da PRF, SENATRAN e IBGE sejam extraídos e feito um tratamento e filtragem no Google Colab usando Python, para garantir que o dashboard seja alimentado com informações integradas e confiáveis.         | Alta       | 13   |
| US2 |    Como Diretor de Operações, quero visualizar um dashboard no Power BI, para analisar de forma eficiente as informações das bases de dados.      | Média    | 5   |
|US3|Como Diretor de Operações, quero um protótipo do dashboard final, para ter uma noção de como o Power BI ficará ao término do projeto. | Baixo | 3|

---

## 📅 Sprint(s) Relacionadas
| Sprint | Entregas Principais                          | Status   |
|--------|----------------------------------------------|----------|
| 01     | quero que os dados da PRF, SENATRAN e IBGE sejam extraídos e feito um tratamento e filtragem no Google Colab usando Python      | Concluído|
| 02     | quero visualizar um dashboard no Power BI                           | Concluído |
| 03 | quero um protótipo do dashboard final | Concluído |

---

## 📊 Critérios de Aceitação
- O MVP deve permitir que o usuário aplique filtros (ano, região e veículo) no dashboard para visualizar e identificar facilmente quais estados apresentam a maior taxa de letalidade envolvendo veículos pesados.  
- O sistema deve registrar o cruzamento e o tratamento correto dos dados extraídos do SENATRAN, PRF e IBGE, garantindo a integridade das informações (A documentação detalhada do tratamento de cada base de dados está disponível em formato PDF na pasta 'Docs', com acesso aos arquivos originais garantido via link para o Google Drive.).
- Métricas coletadas: taxa de letalidade, quantidade de sinistros, número de vítimas, tamanho da frota, dados da população e tendências (2024-2025).  

---

## 📈 Métricas de Validação
- Validação com Stakeholders: Número de apresentações e rodadas de homologação realizadas com o cliente (Observatório) ou orientadores para validar as funcionalidades e a precisão do dashboard.  
- Avaliação de Usabilidade e Clareza: Coleta de percepções sobre a facilidade de navegação pelos filtros (ano, região, veículo) e a clareza na interpretação dos indicadores de letalidade apresentados.  
- Aderência aos Objetivos de Negócio: Capacidade técnica do MVP em responder de forma direta à pergunta central dessa sprint (Quais estados apresentam a maior taxa de letalidade envolvendo veículos pesados?) e garantir a precisão total no cruzamento das bases de dados.
---

## 🚀 Próximos Passos
- Melhorias planejadas após feedback  
- Ajustes de usabilidade  
- Expansão de funcionalidades para próximo incremento  

---

## 📂 Anexos / Evidências
![Protótipo do Dashboard de Segurança Viária](https://github.com/LucasSilva59/Projeto-API-3-Semestre/blob/main/Imagens/Prot%C3%B3tipo%20de%20Dashboard.jpeg)
![Dashboard Inícial](https://github.com/LucasSilva59/Projeto-API-3-Semestre/blob/main/Imagens/Dashboard%20In%C3%ADcial.png)
![Demonstração do Script Python](https://github.com/LucasSilva59/Projeto-API-3-Semestre/blob/main/Imagens/GIFSENATRAN.gif)
![Demonstração do Script Python](https://github.com/LucasSilva59/Projeto-API-3-Semestre/blob/main/Imagens/GIFSENATRANv2.gif)
![Demonstração do Script Python](https://github.com/LucasSilva59/Projeto-API-3-Semestre/blob/main/Imagens/GIFPRF.gif)
![Demonstração do Script Python](https://github.com/LucasSilva59/Projeto-API-3-Semestre/blob/main/Imagens/GIFIBGE.gif)
- Prints de tela  
- Fluxos ou protótipos  
- Vídeo (MVP)  
