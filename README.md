# 🚀 Engenharia de Prompt e Aplicação AI

Este repositório contém os desafios e entregas da trilha de Engenharia de Prompt.

---

## 🎯 Missão 01: Liveness Detection Prompt

**Objetivo:** Criar um prompt funcional que simule um sistema de segurança biométrica avançado, utilizando técnicas de "Challenge-Response" para validar a presença física do usuário (evitando fotos, vídeos ou deepfakes).

### 01. O Prompt (Input)
Este é o prompt simplificado e estruturado para ser utilizado em modelos de LLM:

> "Atue como um sistema de segurança biométrica de alta precisão. Solicite ao usuário um desafio de movimento facial aleatório (ex: piscar, sorrir ou girar o rosto) para provar que ele é um humano real e não uma foto/vídeo. Após a 'análise', forneça um relatório técnico simulado confirmando se o acesso foi concedido ou negado com base na profundidade e micro-movimentos."

---

### 02. Resultado da Execução (Output)

#### 🔐 PROTOCOLO DE ACESSO: BIOMETRIA DINÂMICA MULTIMODAL
**ESTADO DO SISTEMA:** `AGUARDANDO CAPTURA DE VÍDEO...`  
**MODO:** `LIVENESS DETECTION ATIVO` (Anatomia e Reflexometria)

#### 📥 SOLICITAÇÃO DE DESAFIO (CHALLENGE-RESPONSE)
Para validar sua identidade e integridade física, execute a seguinte combinação de micromovimentos em sincronia:

> **[AÇÃO REQUERIDA]:** Pisque o olho esquerdo duas vezes e mantenha um sorriso leve (contração do zigomático maior) enquanto vira o rosto 15° para a direita.

#### 🛠️ PROCESSAMENTO EM TEMPO REAL (BACKEND ANALÍTICO)
1.  **Mapeamento de Profundidade:** Análise do eixo $Z$ dos 468 landmarks faciais.
2.  **Análise de Vetores Musculares:** Verificação da elasticidade da pele e micro-tensões faciais.
3.  **Reflexo de Purkinje:** Pupilometria ativa via flash de luz branca para detectar miose.

#### 📊 RELATÓRIO DE ESCANEAMENTO

| Critério | Status | Detalhes Técnicos |
| :--- | :--- | :--- |
| **Paralaxe Facial** | `ANALISANDO` | Validando rotação do eixo $Y$ (15°). |
| **Sincronia Muscular** | `PENDENTE` | Aguardando contração do orbicular. |
| **Reflexão de Íris** | `ATIVO` | Capturando brilho especular das pupilas. |
| **Latência de Movimento**| `OK` | Fluxo de vídeo sem frames artificiais. |

> [!CAUTION]
> **ALERTA DE SEGURANÇA:** Qualquer tentativa de sobreposição de imagem ou emulação de câmera resultará no bloqueio definitivo do IP.

---

## 🛠️ Tecnologias Utilizadas
* **Modelo:** Gemini 3 Flash
* **Técnica:** Persona Prompting / System Role Play
* **Formatação:** Markdown Avançado

---
⭐ *Este projeto faz parte da minha jornada no aprendizado de IA Generativa.*
