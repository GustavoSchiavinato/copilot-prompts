# Copilot Prompts de Carreira


# 🚀 Sistema de Orientação de Carreira em Tecnologia  

Este projeto utiliza **dois agentes especializados** para ajudar pessoas interessadas em tecnologia a descobrirem seu melhor caminho profissional e seguirem um plano de estudos personalizado.  

---

## 👤 AGENT 1 - Entrevistador de Carreira em Tecnologia  

### 🎯 Missão  
O **Agent 1** conduz uma entrevista estruturada de **7 perguntas** para entender:  
- Interesses e motivações  
- Experiência prévia  
- Disponibilidade de estudo  
- Preferências de trabalho  
- Objetivos profissionais  

Após coletar as informações, ele sugere **3 carreiras ranqueadas** e transfere o usuário para o **Agent 2**.  

### 📝 Fases  

**Fase 1: Entrevista (7 perguntas)**  
- Perguntas feitas uma de cada vez  
- Sempre aguarda a resposta antes de prosseguir  
- Após 7 perguntas, encerra a coleta de dados  

**Fase 2: Análise e Sugestão**  
- Avalia carreiras com base em afinidade, mercado, tempo de ramp-up e aproveitamento da experiência prévia  
- Apresenta as 3 melhores opções com vantagens, desafios e contexto de mercado  

**Fase 3: Handoff para Agent 2**  
- Quando o usuário escolhe uma carreira, o Agent 1 transfere os dados para o Agent 2:  
  - Nome da carreira escolhida  
  - Horas disponíveis por semana  
  - Nível de experiência  
  - Objetivo profissional  
  - Preferência (pessoas/dados/código)  
  - Interesses técnicos mencionados  

---

## 👤 AGENT 2 - Planejador de Carreiras  

### 🎯 Missão  
O **Agent 2** recebe as informações do Agent 1 e gera um **plano completo de estudos personalizado**, incluindo:  
- Visão do dia a dia da carreira escolhida  
- Mapa de skills essenciais e complementares  
- Roadmap de 90 dias adaptado à disponibilidade do usuário  
- Projeto de portfólio  
- Roteiro de entrevistas  
- Trilha DIO recomendada  

### 📥 Dados recebidos do Agent 1  
- **CARREIRA_ESCOLHIDA**  
- **HORAS_SEMANA**  
- **EXPERIENCIA**  
- **OBJETIVO**  
- **PREFERENCIA**  
- **INTERESSES**  

### 📦 Estrutura do Plano  
- **🧩 Visão do Dia a Dia**: atividades típicas da carreira  
- **🧠 Mapa de Skills**: core skills, nice-to-have e ferramentas  
- **📅 Roadmap de 90 dias**: dividido em fundamentos, prática e portfólio  
- **🚀 Projeto de Portfólio**: escopo, entregáveis e critérios de aceitação  
- **💬 Roteiro de Entrevistas**: perguntas comuns e exemplos de resposta  
- **🎓 Trilha DIO Recomendada**: bootcamp ou trilha específica para consolidar os estudos  

---

## ⚙️ Regras de Personalização  

- **Horas/semana**: ajusta intensidade do roadmap  
- **Experiência**: adapta explicações e foco (fundamentos, prática ou portfolio)  
- **Objetivo**: enfatiza portfolio, transferência de skills ou crescimento avançado  

---

## 🎬 Fluxo de Uso  

1. O usuário inicia com o **Agent 1** e responde às 7 perguntas.  
2. O Agent 1 sugere 3 carreiras e o usuário escolhe uma.  
3. O Agent 1 transfere os dados para o **Agent 2**.  
4. O Agent 2 gera o **plano completo de estudos** e acompanha o usuário na execução.  

---

✨ Esse sistema garante uma jornada estruturada: primeiro **descobrir o perfil ideal** e depois **seguir um roadmap personalizado** para alcançar a carreira escolhida em tecnologia.  

---

Quer que eu já monte um **exemplo prático de README.md preenchido** com sua escolha de carreira (**Machine Learning Engineer**) para ficar ainda mais ilustrativo?
