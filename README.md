# 🎓 Estud-AI: Aprendizado Personalizado com IA Generativa

## 📒 Descrição
O **Estud-AI** é uma IA educacional generativa desenvolvida com **Amazon Bedrock**, projetada para analisar o perfil de cada aluno e criar **planos de estudo personalizados**.  
Hoje, ele gera conteúdos textuais detalhados (planos de estudo) e imagens educativas ilustrativas, demonstrando a capacidade multimodal da ferramenta.  

## 🤖 Tecnologias Utilizadas
- Amazon Bedrock
  - Claude 3 Haiku (Anthropic) – geração de conteúdo textual e prompts de imagens
  - Titan Image Generator G1 (Amazon) – geração de imagens educativas
- AWS Console (Free Tier)

## 🧐 Processo de Criação
1. Criei um **agente Claude 3 Haiku** no Amazon Bedrock para analisar o perfil do aluno e gerar planos de estudo detalhados.  
2. Usei o **Titan Image Generator G1** no Playground para criar imagens educativas a partir dos prompts gerados pelo Claude.  
3. Capturei prints do fluxo de geração de conteúdo e imagens para demonstrar o funcionamento multimodal do projeto.  

## 🚀 Resultados

**prompt para o Claude 3:**
 <img src="https://github.com/cauafreirealves/lab-natty-or-not/blob/main/Captura%20de%20tela%20prompt%20claude%203%20haiku.jpeg">
 
**Plano de estudos personalizado (Claude 3):**
   <img src="https://github.com/cauafreirealves/lab-natty-or-not/blob/main/Captura%20de%20tela%20resposta%20claude%203%20haiku%20pt1.jpeg">
   <img src="https://github.com/cauafreirealves/lab-natty-or-not/blob/main/Captura%20de%20tela%20resposta%20claude%203%20haiku%20pt2.jpeg">
   <img src="https://github.com/cauafreirealves/lab-natty-or-not/blob/main/Captura%20de%20tela%20resposta%20claude%203%20haiku%20pt3.jpeg">
   <img src="https://github.com/cauafreirealves/lab-natty-or-not/blob/main/Captura%20de%20tela%20resposta%20claude%203%20haiku%20pt4.jpeg">
   <img src="https://github.com/cauafreirealves/lab-natty-or-not/blob/main/Captura%20de%20tela%20resposta%20claude%203%20haiku%20pt5.jpeg">
   
   **Imagens educativas geradas automaticamente (Titan Image Generator):**
   <img src="https://github.com/cauafreirealves/lab-natty-or-not/blob/main/Captura%20de%20tela%20titan%20image%20generator%201.jpeg">
   <img src="https://github.com/cauafreirealves/lab-natty-or-not/blob/main/Captura%20de%20tela%20titan%20image%20generator%202.jpeg">
   <img src="https://github.com/cauafreirealves/lab-natty-or-not/blob/main/Captura%20de%20tela%20Titan%20Image%20Generator%203.jpeg">
   

## 💭 Próximos Passos / Upgrade Futuro
O objetivo futuro é evoluir o **Estud-AI** para gerar **conteúdos multimídia completos** e totalmente personalizados, incluindo:
- Vídeo-aulas e podcasts  
- PDFs e e-books automatizados  
- Infográficos avançados  
- Análise profunda do perfil do aluno para personalização ainda maior  

Para isso, planejo integrar:
- **AWS Lambda** – para orquestrar as chamadas aos modelos de IA generativa  
- **API Gateway** – para disponibilizar o Estud-AI como API acessível via front-end  
- **S3 / DynamoDB** – para armazenamento de conteúdos e dados de alunos  

Este upgrade permitirá que o Estud-AI se torne um **sistema educacional completo, escalável e multimodal**, entregando conteúdos personalizados de forma automática para cada aluno.
